# **Finding Lane Lines on the Road** 




### 1.Pipeline Description

The following steps were done to identify the lane lines

1. Converted the image to grayscale so that the picture wil be seen with respect to brightness value, where 0 equals black and 255 equals white
2. Applied Canny Edge detection to detect the sudden changes in the pixel value
3. Applied Gaussian Blur to remove the noise and smoothen the image
4. selected a region of interest so that the camera output data will only focus on the road
5. Applied probabilistic Hough transform to detect the line segments in the image


### 2. potential shortcomings with your current pipeline

Apply the same pipeline for U bend curve and try to see if the lane detection might work or not

### 3. possible improvements 

1. Detect the centre of the lane
2. generate the left and right lane with respect to the lane length 
3. and use this steps to perfom the challenge video