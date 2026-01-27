# PRODIGY_CS_02-
Internship Task 2 - Python project to encrypt/decrypt images 


• Overview : 
This project encrypts and decrypts images using a numeric key. It manipulates pixel values to securely transform an image and restores it back to its original form. Developed as part of Internship Task 2.
 
• How It Works: 
Encryption: Each pixel’s RGB values are shifted by a key:
r = (r + key) % 256
g = (g + key) % 256
b = (b + key) % 256
Decryption: The reverse operation restores the original image:
r = (r - key) % 256
g = (g - key) % 256
b = (b - key) % 256
           
 * HOW TO RUN *
Place image_encrypt.py and the image in the same folder.
-Open terminal → run:
(python image_encrypt.py)
-Enter 1 to encrypt or 2 to decrypt, then the key and image file name.                 

#Tools Used
Python 3.x
Pillow (PIL) library
VS Code

•Outcome
encrypted.png → scrambled image
decrypted.png → restored original image