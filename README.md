# Smart-Vision-AI

SmartVision AI is a modular image processing system that integrates multiple computer vision models through Roboflow's Inference SDK. It demonstrates how to combine various model endpoints—including YOLO-World, Grounding DINO, Segment Anything (SAM), CLIP, and Gaze Estimation—to perform object detection, segmentation, and image understanding in a unified workflow.

## Project Overview

This project showcases the application of vision transformer-based architectures for advanced image analysis. It emphasizes practical usage of hosted inference APIs and highlights how pre-trained models can be used collectively for complex visual tasks such as detection, segmentation, vision-language mapping, and gaze tracking.

## Key Features

- Object detection using YOLO-World
- Image segmentation using SAM (Segment Anything Model)
- Visual grounding with Grounding DINO
- Vision-language understanding using CLIP
- Gaze estimation from images
- Image annotation and visualization using Python

## Technologies Used

- Python 3.8+
- Roboflow Inference SDK
- Supervision library for visualization
- PIL (Python Imaging Library)
- Matplotlib
- Pre-trained transformer-based vision models

## Installation

To set up the environment, install the following dependencies:

```bash
pip install requests pillow requests_toolbelt
pip install roboflow
pip install 'inference[sam]'
pip install 'inference[clip]'
pip install 'inference[gaze]'
pip install 'inference[grounding-dino]'
pip install 'inference[yolo-world]'
pip install 'inference[transformers]'
