# Edge-Linking-using-Hough-Transformm
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## Output

### Input image and grayscale image
<img width="1391" height="423" alt="image" src="https://github.com/user-attachments/assets/13feec51-3927-49ac-a6a2-263f832a09ef" />


### Canny Edge detector output
<img width="1390" height="422" alt="image" src="https://github.com/user-attachments/assets/da05ac33-b2bd-48cc-a7c7-94558230effe" />


### Display the result of Hough transform
<img width="1105" height="673" alt="image" src="https://github.com/user-attachments/assets/69d206f9-6dfa-426d-b01a-2d001fad7a75" />
