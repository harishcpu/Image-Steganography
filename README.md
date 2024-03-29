# Image-Steganography
A system, popularly used in cryptographic applications, which conceals confidential message that needs to be kept secret/transferred secretly. Here a text information is being concealed within an image.

### Introduction
Steganography is the art of hiding the fact that communication is taking place, by hiding information in other information. Many carrier file formats can be used, but digital images are the most popular because of their frequency on the internet.

 Steganography is the practice of hiding private or sensitive information within something that appears to be nothing out of the usual. Steganography is often confused with cryptology because the two are similar in the way that they both are used to protect important information. The difference between two is that steganography involves hiding information so it appears that no information is hidden at all. If a person views the object in which the information is hidden he or she will have no idea that there is any hidden information, therefore the person will not attempt to decrypt the information.

![titleimage](ScreenShots/image-steganography.jpeg#center)

What steganography essentially does is exploit human perception, human senses are not trained to look for files that have information inside them, although this software is available that can do what is called Steganography. The most common use of steganography is to hide a file inside another file.

### Requirement Details
1. The application accepts an image file say .bmp along with a text file that contains the message to be steged
2. Analyze the size of the message file to check whether the message could fit in the provided .bmp image
3. Provide an option to steg a magic string which could be useful to identify whether the image is steged or not
4. The application should provide an option to decrypt the file
5. This has to be a command-line application and all the options shall be passed as a command-line argument

### Design
![design](ScreenShots/Design.jpg)

### Sample output
##### Usage:
![helpmenu](ScreenShots/cmdline_usage_with_arguments.jpg)

##### Encoder o/p:
![encoder](ScreenShots/encoding_steps_and_output_at_different_stages.jpg)

##### Decoder o/p:
![decoder](ScreenShots/decoding_steps_and_output_at_different_stages.jpg)

### References
1. [Wikipedia – Steganography](https://en.wikipedia.org/wiki/Steganography)
2. [Image – What is a BMP image](https://en.wikipedia.org/wiki/BMP_file_format)
3. [Download project specification in pdf](DesignDoc/Steganography-Abstract.pdf)
