# Number Plate Detection System

## Overview
This project demonstrates the implementation of a Number Plate Detection System using image processing and optical character recognition (OCR) techniques. The system aims to locate number plates in an image and extract the alphanumeric characters from them.

## Dependencies
- OpenCV
- Matplotlib
- NumPy
- Imutils
- EasyOCR

## Process Explanation

1. **Image Loading:** Load the input image for number plate detection.

2. **Preprocessing:** Convert the image to grayscale and apply a bilateral filter for noise reduction.

3. **Edge Detection:** Use Canny edge detection to identify potential contours.

4. **Contour Sorting:** Find and sort contours to identify potential number plate locations.

5. **Number Plate Identification:** Iterate through contours to find a quadrilateral shape indicative of a number plate.

6. **Mask Creation:** Create a mask to isolate the number plate region.

7. **Cropping:** Crop the identified number plate region from the image.

8. **OCR Text Reading:** Use OCR to extract text from the cropped number plate region.

9. **Display Results:** Display the original image with the detected number plate and extracted text.

## Note
Ensure the input image path is correctly specified for successful execution.

Feel free to experiment with different images and further enhance the system for real-world applications.

## Author
**Kusumanjli**
**https://www.linkedin.com/in/kusumanjli-khattar-166b881b1/**

