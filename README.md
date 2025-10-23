# Coin Detection and Annotation using OpenCV
## Project Overview

This project demonstrates coin detection and annotation using computer vision techniques in Python with OpenCV. The system detects coins in an image, marks their centers and boundaries, and visualizes the results. This project is useful for automated coin counting, educational purposes, and image analysis learning.

## Features

• Detects coins in an image using keypoints.

• Applies binary inverse thresholding to separate coins from the background.

• Annotates coins with:

   • Center point (blue dot)

   • Coin outline (green circle)

• Visualizes the annotated image using Matplotlib.

• Easy-to-run Python script with minimal dependencies.

## Installation

• Clone or download the repository.

• Make sure Python 3 is installed.

• Install required packages using pip:

     pip install opencv-python matplotlib numpy

## Usage

•  Place your input image in the project folder (the repository includes a sample image).

• Run the Python script:

    python coin_detection.py


• The output image will display all detected coins annotated with their centers and outlines.

## How it Works

• Image Preprocessing: The input image is converted to grayscale and thresholded using binary inverse thresholding to highlight the coins.

• Keypoint Detection: Coins are detected as blobs/keypoints using OpenCV’s blob detection.

• Annotation: Each coin is annotated with a small blue dot at its center and a green circle showing its boundary.

• Visualization: The final annotated image is displayed using Matplotlib.

## Project Structure

  Since this is a simple project, the repository contains:

    Coin_Detection/
    ├── coin_detection.py    # Main Python code for detection and annotation
    ├── coin.jpg             # Sample input image
    └── README.md            # Project documentation

## Notes

 • Threshold value may need adjustment depending on image lighting and coin color.

 • Keypoints can be customized for detecting coins of different sizes.

 • Morphological operations can improve detection by removing small noise or connecting broken coin regions.

## Future Enhancements

 • Support multiple images or video streams for real-time detection.

 • Count total coins automatically and display the number on the image.

 • Save annotated images to the output folder.

 • Integrate a GUI interface for user-friendly interaction.

## Dependencies

   Python 3.x

   OpenCV (opencv-python)

   NumPy

  Matplotlib
## Applications

• Automated coin counting systems.

• Educational projects for computer vision learning.

• Preprocessing for further image analysis tasks like coin classification or segmentation.

## References

• OpenCV Documentation for image processing and keypoint detection.

• Matplotlib Documentation for image visualization.

• Tutorials and guides on morphological operations and blob detection.
