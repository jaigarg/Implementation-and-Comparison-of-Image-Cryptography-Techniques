# Implementation-and-Comparison-of-Image-Cryptography-Techniques
<p align= "justify">The main objective of this project involves application and comparison of various Image Cryptography algorithms. Different image cryptography algorithms use different encryption and decryption techniques resulting in varying strength of encrypted output, quality of decrypted image and total time taken. In order to study image cryptography algorithms, following approach is taken: </p>

* **Input Image**: The image that needs to be encrypted is taken as input. The input image is resized into a 300 x 300-pixel image.

* **Image Cryptography Algorithms**: After resizing the image, cryptography algorithms are applied to encrypt the image from the sender’s end. Encrypted image is passed through decryption process of cryptographic algorithm to get decrypted image at receiver’s end. Following cryptographic algorithms are applied: 
    * Chaos Map based Image Cryptography:
        * Arnold Cat Map Encryption
        * Hénon Map Encryption
        * Logistic Map Encryption
    * Hill Cipher Encryption
    * Advanced Encryption Standard (AES)
    * Rubik’s Cube Image Encryption
    * DNA Based Image Encryption


* **Histogram Analysis**: Encrypted Image Histogram is used to analyse the strength and quality of encrypted image. Basically, the more uniform the histogram is, higher the strength of encrypted output is. Intensity Distribution Score is calculated as the mean of standard deviations of three color channels.

* **Adjacent Pixel Auto-Correlation**: It is used to analyse the performance of encryption algorithm. The correlation between some random points of encrypted image are plotted in order to visualize any observable pattern among them. A pattern in Adjacent Pixel Auto-Correlation plot generally refers to low strength and quality of encryption algorithm.

* **Key Sensitivity**: An ideal image encryption procedure should be sensitive to the secret key. It means that a little change in a secret key should produce completely different image.

* **Algorithm Running Time**: The time taken to encrypt and decrypt an image is a major deciding factor among cryptographic algorithms for use in real life applications.

* **Decrypted Image Quality**: The decrypted image is compared to the input image.
