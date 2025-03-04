# Caesar-Cipher
Encrypt or Decrypt your messages by specifying shift number.

## Concepts Implemented

- **Caesar Cipher**: A substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet.
- **String Manipulation**: Handling and modifying strings to perform encryption and decryption.
- **User Input**: Taking input from the user for the message and shift number.
- **Control Flow**: Using loops and conditionals to control the flow of the program.
- **Keyword Arguments**: Using keyword arguments to specify the operation (encrypt or decrypt) and the shift number.

## Features

- Encrypt messages by shifting letters forward in the alphabet.
- Decrypt messages by shifting letters backward in the alphabet.
- Handles both uppercase and lowercase letters.
- Retains non-alphabet characters (e.g., punctuation, spaces) in their original positions.

## Files

- `main.py`: The main script that runs the Caesar Cipher program.
- `art.py`: Contains the ASCII art logo for the program.
- `README.md`: This file.
- `LICENSE`: The license for the project.

## How to Use

1. Run the `main.py` script.
2. When prompted, type `encode` to encrypt a message or `decode` to decrypt a message.
3. Enter the message you want to encrypt or decrypt.
4. Enter the shift number (the number of positions each letter should be shifted).
5. The script will display the encrypted or decrypted message.

## Example

```sh
$ python main.py
           
 ,adPPYba, ,adPPYYba,  ,adPPYba, ,adPPYba, ,adPPYYba, 8b,dPPYba,  
a8"     "" ""     `Y8 a8P_____88 I8[    "" ""     `Y8 88P'   "Y8  
8b         ,adPPPPP88 8PP"""""""  `"Y8ba,  ,adPPPPP88 88          
"8a,   ,aa 88,    ,88 "8b,   ,aa aa    ]8I 88,    ,88 88          
 `"Ybbd8"' `"8bbdP"Y8  `"Ybbd8"' `"YbbdP"' `"8bbdP"Y8 88   
            88             88                                 
           ""             88                                 
                          88                                 
 ,adPPYba, 88 8b,dPPYba,  88,dPPYba,   ,adPPYba, 8b,dPPYba,  
a8"     "" 88 88P'    "8a 88P'    "8a a8P_____88 88P'   "Y8  
8b         88 88       d8 88       88 8PP""""""" 88          
"8a,   ,aa 88 88b,   ,a8" 88       88 "8b,   ,aa 88          
 `"Ybbd8"' 88 88`YbbdP"'  88       88  `"Ybbd8"' 88          
              88                                             
              88           

Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello world
Type the shift number:
5
Here is the encoded result: mjqqt btwqi
Type 'yes' if you want to go again. Otherwise, type 'no'.
no
Goodbye!
