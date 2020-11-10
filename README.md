# Computer Vision Projects


This repository contains Jupyter Notebook (Python) implementations of several CV exercises. 
These exercises were created during the first year of my graduate studies (April 2020 - Aug 2020).


# Projects

## 1. Homography (Image Rectification)

This is an implementation of image rectifier using "Homemade" homography. Requires text files specifying the pre-rectification coordinates (ideally four or more) and the post-rectification coordinates.

## 2. Image Filtering (Gaussian & Median Filter)

The code will apply Gaussian & Median filter to an image. Gaussian filter is effective at image downsizing, while median filter is effective at salt-and-pepper noise removal. 
2D gaussian filter was implemented by passing 1D gaussian filter twice (once in horizontal, once in a vertical direction), which runs in linear time as opposed to the naive implementation that has the runtime of O(N^2).
(N = size of the filter)

## 3. Mosaicing (Panorama Image)

Image Mosaicing, or image stitching, is a process of connecting multiple images with overlapping field of views. This was implemented mainly using Lucas-Kanade algorithm,
which detects optical flow. 

## 4. Structure from Motion

Using Tomasi-Kanade algorithm, the code approximates the 3D structure from the array of pictures of an object taken in various vantage points.
