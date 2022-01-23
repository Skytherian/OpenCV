# OpenCV
Separate repo for OpenCV projects 

Detecting number plates of cars -> detectnumberplate.ipynb

In this project we try to extract the number plate of a car from an image.
The image is first grayed and blurred, and then the Canny method is applied for edge detection using the OTSU threshold.
Afterwards we grab the largest contours which have four sides. That would be the number plate.


