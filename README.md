# Spot-Difference-between-images

# Aim:
To find out difference between two images using SSIM and fill the images with the part missing.

# Analysis Of The Code:

1. Importing all necessary libraries like numpy, matplotlib,sklearn etc.
2. Loading the images and converting them to grayscale
3. Compute SSIM (Structural Similairty Index) using the in-built functions.
4. The diff image contains the actual image differences between the two images and is represented as a floating point data type in the range [0,1] so we must convert the array to 8-bit unsigned integers in the range [0,255] before we can use them.
5. Threshold the difference image, followed by finding contours to obtain the regions of the two input images that differ.
6. Plot the images showing the difference.


