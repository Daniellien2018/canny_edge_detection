# Canny Edge Detection App

## Overview:
Given a single image, calculate and return the edges of the image laid on top of original image for visualization using canny edge detection algorithm.

## Goals:
- Understand how Canny Edge Detection works via double thresholding and Hysteresis.

- Understand the Guassian Blue Operation in respect to filtering, smoothing, and noise reduction (Hysteresis )

- Visualize Images with edges and compare with other edge detection algorithms

- Practice lightweight flask application development.


## MVPs/Features:
- Edge Detector: Given a photo as input, draw edges on the image (Done)

- Threshold Parameters: Be able to adjust thresholding on detection (Done)

- Side by Side Detection: visualize two images side by side, be able to adjust params for this. (Done) 6/28

- Slider to visualize real time thresholding difference 

## Edge Cases / Issues to Fix

- Error handling for when the file passsed is not an image

### Enhancement Ideas (Todo)
- Multiple Input formats
- Real-Time Processing 
- Drag and drop images
- Consider other edge detection algorithms
  - Sobel 
  - Prewitt
  - Laplacian


### How to Run this Repo
- Clone this Repo:
  ```bash
  git clone https://github.com/{username}/canny_edge_detection.git
  cd canny_edge_detection
- Create Virtual Environment 
  ```bash
  python3 -m venv canny_edge_detection
- Instal Requirements 
  ```bash
  pip install -r requirements.txt
- Run Flask App
  ```bash
  flask run app.py
