# DepthAI-Text-Recognition

# DepthAI Text Detection and Recognition

## Overview
This project uses the Luxonis DepthAI camera to perform real-time text detection and recognition. It leverages OpenCV, DepthAI, and custom scripts to process camera input and recognize text using neural network models. The repository contains two main files:
- **`main.py`**: The primary script that sets up the DepthAI pipeline, captures video frames, detects text using a neural network, and processes recognized text.
- **`east.py`**: A utility module that provides functions for handling bounding boxes, rotated rectangles, and decoding the text detection outputs.

## Requirements
- Python 3.x
- DepthAI-compatible hardware (e.g., Luxonis OAK-D camera)
- Required Python libraries: 
  - `opencv-python` for computer vision processing
  - `depthai` for interacting with the DepthAI camera and running neural networks
  - `numpy` for numerical operations
  - `blobconverter` for managing neural network model blobs
  
Ensure all dependencies are installed before running the project:
```bash
pip install opencv-python depthai numpy blobconverter
