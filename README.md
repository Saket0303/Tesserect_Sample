# OCR in Python with OpenCV, Tesseract and Pytesseract

## Optical Character Recognition (OCR)
Optical Character Recognition (OCR) is a technique of reading or grabbing text from printed or scanned photos,
handwritten images and convert them into a digital format that can be editable and searchable.

## Applications
- Passport recognition in Airports
- Automation of Data Entry
- License plates recognition
- Converting handwritten documents into electronic images
- Create audible files (text to audio)

## Preprocessing of images using OpenCV
- grayscaling
- thresholding
- dilating
- eroding
- opening
- canny edge detection
- noise removal
- deskwing
- template matching.

## Bounding box information using Pytesseract
- on a character level
- on a word level
- based on a regex template

## Page Segmentation Modes
There are several ways a page of text can be analysed. 
Here's a list of the supported page segmentation modes by tesseract.

0 Orientation and script detection (OSD) only.
1 Automatic page segmentation with OSD.
2 Automatic page segmentation, but no OSD, or OCR.
3 Fully automatic page segmentation, but no OSD. (Default)
4 Assume a single column of text of variable sizes.
5 Assume a single uniform block of vertically aligned text.
6 Assume a single uniform block of text.
7 Treat the image as a single text line.
8 Treat the image as a single word.
9 Treat the image as a single word in a circle.
10 Treat the image as a single character.
11 Sparse text. Find as much text as possible in no particular order.
12 Sparse text with OSD.
13 Raw line. Treat the image as a single text line, bypassing hacks that are Tesseract-specific.

To change your page segmentation mode, change the --psm argument in your custom config string to any of the above mentioned mode codes.

## Other Specifications:
- Specifying only digits.
- WhiteListing Characters
- Blacklisting Characters

