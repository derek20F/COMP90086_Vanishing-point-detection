# COMP90086_Vanishing-point-detection
## Summary
* Detected the vanishing points from images by canny edge detection, Hough transform, and RANSAC
* Achieved detection errors smaller than 0.54% of the input image dimensions under different lighting conditions, image contrasts, and scenes

## Description

The task of this project is to detect the vanishing points from general images. First, image normalisation and canny edge detection are performed to detect edges in images. Then, the Hough transform is performed on those edges to get the line parameters. Additional post-processing is used to filter out the lines that cannot contribute to vanishing point detection such as horizontal, vertical lines and the lines from texture. Finally, RANSAC is used to locate the vanishing points. The result indicates my model can detect vanishing point locations with errors smaller than 0.54% of the input image dimensions under different lighting conditions, image contrasts, and scenes.

