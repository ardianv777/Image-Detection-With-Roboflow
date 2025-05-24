# Object Detection Project: Trees, Animals, Stationery, and Transportation

This project demonstrates the use of object detection models to analyze images and visualize predictions. Leveraging the Roboflow API and a pre-trained YOLO-based model, the workflow automates the process of loading images, running inference, and displaying results with annotated bounding boxes and class labels.

## Group Members

| Student Name                     | Student ID   |
|--------------------------|-------------|
| Ardian Vega Carrelino    | 215314161   |
| Prischia Ballo           | 215314166   |

## Project Overview

The goal of this project is to detect and classify objects in images, specifically focusing on four categories:
- Trees
- Animals
- Stationery
- Transportation

The workflow includes:
- Installing required dependencies for object detection and image processing.
- Loading a custom-trained model from Roboflow.
- Predicting objects in a batch of images from a specified directory.
- Visualizing detection results by drawing bounding boxes and class labels directly on the images.

This project is useful for rapid prototyping and evaluation of computer vision models on custom datasets.

## How to Use

1. Install the required dependencies (`yolo`, `ultralytics`, `roboflow`).
2. Set up your Roboflow API key and project name.
3. Place your images in the `images/` directory.
4. Run the notebook to perform object detection and visualize the results.

---

Feel free to fork this repository and adapt it to your own dataset and object categories!
