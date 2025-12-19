# PRODIGY_CS_01
This Python program implements the Caesar Cipher, a basic encryption technique. It takes plaintext and a shift value from the user, encrypts the text by shifting alphabetic characters forward, and decrypts it by reversing the shift. Letter case is preserved and non-alphabetic characters remain unchanged.

How It Works :
Each letter is converted to its ASCII value . 
Shift is applied using modulus (%) 26 .
Ensures wrap-around (Z → A) .
Non-alphabet characters like spaces, numbers, symbols stay same .
