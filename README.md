# Classical-Encryption-Techniques

## Caesar Cipher
In this problem, you are required to implement the Caesar cipher algorithm. Build a 
function that takes string input of the plaintext and integer for the key, and outputs a 
string containing the ciphertext. Use the following keys to test your function: 3, 6, 12
## Play Fair Cipher
Implement the Play Fair cipher algorithm including the creation of the 5x5 Play Fair matrix 
that you will use to encrypt the input. Use the following guidelines:

*  If a pair is a repeated letter, insert ‘X’ as filler between the two characters.
*   If there is a single trialing letter, attach ‘X’ to the end to complete the two-letter block.
*  If both letters fall in the same row, replace each with letter to right (wrapping back to start from end.)
*  If both letters fall in the same column, replace each with the letter below it (wrapping to top from bottom.)
*  Otherwise, each letter is replaced by the letter in the same row and in the column of the other letter of the pair.

You are required to build a function that takes string input of the plaintext and string input 
of the key, and outputs string output for the ciphertext. Build any other necessary 
functions to help you get the final output (i.e. function to create the Play Fair matrix). Use 
the following keys: rats, archangel

## Hill Cipher
Implement the Hill cipher algorithm. Create a function that takes the plaintext as string 
and the key matrix as an array of integers, and outputs the ciphertext as string. You will 
have to convert the any text to its ASCII representation to multiply with the key matrix.
Use the following formula:

(
𝐶1;
𝐶2
) = (
𝐾1 𝐾2;
𝐾3 𝐾4
) (
𝑃1;
𝑃2
)
Use the following keys to test your algorithm:
(
5 17;
8 3
) , (
2 4 12;
9 1 6;
7 5 3
)
## Vigenere Cipher
Create a function that implements the Vigenere cipher algorithm. The function takes 
three inputs: plaintext as string, key as string, and mode as bool, where true is auto mode 
and false is repeating mode. The output is a string representing the ciphertext. Use the 
following keys: pie (repeating mode), aether (auto mode)
## Vernam Cipher
Create a function that implements Vernam (One Time Pad) cipher algorithm. The function 
takes the plaintext and the key as string inputs. The output ciphertext should also be a
string. Use the following key: SPARTANS
