# **Finding Lane Lines on the Road** 
### Introduction
This project marks left & right lane lines on given input videos of first-person view of a car travelling on a road.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

### 1. Project Pipeline
My pipeline consists of the following steps. Each step takes its input from previous step:-
- convert input image to grayscale
- Apply Gaussian blur
- Apply canny edge detection
- Apply region of interest mask
- Apply hough transform

At this point in the pipeline, the modified image looks like the below:
![After Hough Transform][image1]
# color image with lane lines marked = weighted_img(img with lines drawn, original image) 

![alt text][image1]


### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to ...

Another potential improvement could be to ...
