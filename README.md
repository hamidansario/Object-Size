# Object-Size 
Algorithm

Image pre-processing

Read an image and convert it it no grayscale

Blur the image using Gaussian Kernel to remove un-necessary edges

Edge detection using Canny edge detector

Perform morphological closing operation to remove noisy contours

Object Segmentation

Find contours

Remove small contours by calculating its area (threshold used here is 100)

Sort contours from left to right to find the reference objects

Reference object

Calculate how many pixels are there per metric (centi meter is used here)

Compute results

Draw bounding boxes around each object and calculate its height and width
