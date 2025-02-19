IMAGE-BASED STEGANOGRAPHY WITH ENCRYPTION AND DECRYPTION
This project implements a simple form of steganography using Python and OpenCV. It allows users to hide a secret message in an image, using pixel manipulation. The message is encrypted and hidden inside the image, and a passcode is required for decryption.
FEATURES:
Hide a secret message inside an image file.
Encrypt the message using a passcode.
Decrypt the message using the correct passcode.
The image file will be saved with the hidden message embedded in it.
You can install OpenCV using pip:
                    pip install opencv-python
HOW IT WORKS:
The secret message is converted to its ASCII values and embedded into the image’s RGB pixel values. A passcode is used to secure the encryption and decryption processes.

1. Encryption:
Enter a secret message and a passcode.
The message is converted into ASCII values and embedded into the image pixels.
The modified image is saved with the embedded message.
You can view the encrypted image using your default image viewer.
 2. Decryption:
Enter the passcode.
If the passcode is correct, the secret message will be extracted from the image.
The message is printed on the console.

Usage:
1. Encryption Process:
Modify the mypic.jpg path with the image file you want to use.
Run the script and input your secret message and passcode when prompted.
The image with the hidden message will be saved as encryptedImage.jpg.
2. Decryption Process:
After the image is encrypted, run the script again.
When prompted, enter the correct passcode for decryption.
If the passcode matches, the hidden message will be printed to the console.
