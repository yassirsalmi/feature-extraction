# LBP, ULBP and HOG algorithms for Feature Extraction

This repository contains implementations of three widely used feature extraction techniques in computer vision: Local Binary Patterns (LBP), Uniform Local Binary Patterns (ULBP), and Histogram of Oriented Gradients (HOG).

## Local Binary Patterns (LBP)

Local Binary Patterns (LBP) is a simple yet efficient texture operator which labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number.

## Uniform Local Binary Pattern (ULBP)

A local binary pattern is uniform if it contains at most two 0-1 or 1-0 transitions. In the LBP histogram, each uniform pattern is assigned to a separate bin, while all non-uniform patterns are assigned to a single bin.

## Histogram of Oriented Gradients (HOG)

Histogram of Oriented Gradients (HOG) is a feature descriptor technique widely used in computer vision and image processing for object detection. It focuses on capturing the local object shape and appearance by analyzing the distribution of oriented gradients.

## Requirements

- Python 3
- numpy
- matplotlib
- cv2
- numpy

