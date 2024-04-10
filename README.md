# Intro-to-Digital-Forensics

![SS-1](https://github.com/sayan-125/Intro-to-Digital-Forensics/assets/158836588/8335d2b1-e261-426e-b504-9aecce132f0d)

### Task 1: Introduction To Digital Forensics

Consider the desk in the photo above. In addition to the smartphone, camera, and SD cards, what would be interesting for digital forensics?

	Ans: laptop

### Task 2: Digital Forensics Process

It is essential to keep track of who is handling it at any point in time to ensure that evidence is admissible in the court of law. What is the name of the documentation that would help establish that?

	Ans: Chain of custody

### Task 3: Practical Example of Digital Forensics

	1. Download Task File
	2. unzip Task File (Command: unzip ransom-lettter-2-1645608985174.zip)
	3. cd ransom-lettter-2-1645608985174

Using pdfinfo, find out the author of the attached PDF file, ransom-letter.pdf.

	Ans: 
	1. pdfinfo ransom-letter.pdf
	2. Author: Ann Gree Shepherd

#### Photo EXIF Data

Using exiftool or any similar tool, try to find where the kidnappers took the image they attached to their document. What is the name of the street?

	Ans:
	1. exiftool letter-image.jpg
	2. GPS Position: 51 deg 30' 51.90" N, 0 deg 5' 38.73" W
	3. replace deg with ° and remove the space between the number and the ° symbol then search
 	4. 51°30'51.9"N 0°05'38.7"W
	5. Milk Street

What is the model name of the camera used to take this photo?

	Ans:	
	1. exiftool letter-image.jpg | grep Camera
	2. Camera Model Name: Canon EOS R6

