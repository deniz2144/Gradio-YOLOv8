# Ultralytics YOLOv8 Gradio Demo

This project presents an interactive Gradio interface that performs object detection in images using the Ultralytics YOLOv8 model.

## Features

- **Image Upload**: Users can upload their own images.
- **Confidence Threshold**: Slider to adjust the accuracy of detections.
- **IOU Threshold (IoU Threshold)**: Slider for non-maximum suppression (NMS) operation.
- **Sample Images**: Sample images for quick start.

## Setup

Follow the steps below to run your project in your local environment:

1. Clone this repository:
   ```bash
   git clone https://github.com/deniz2144/Gradio-YOLOv8

2. Install the required dependencies:
  
  pip install -r requirements.txt

3. Run the Python file:  
   python yolov8_gradio.py

Navigate to the local server URL specified in your browser (usually http://127.0.0.1:7860).

Upload an image via the interface, set the trust and IoU threshold and press the “Submit” button.
