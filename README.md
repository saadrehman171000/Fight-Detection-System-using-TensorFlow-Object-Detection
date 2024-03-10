# Fight Detection System using TensorFlow Object Detection

This repository contains a Python application for detecting fights in videos using TensorFlow object detection. It utilizes a pre-trained EfficientDet model to identify potential instances of fights in input videos. The application provides a user-friendly interface built with Tkinter, allowing users to select a video file and initiate the detection process. When a fight is detected, the application displays a visual notification on the video frame and plays an alarm sound.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- TensorFlow
- tkinter
- Pillow

## Usage

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the `fightDS.py` file.
4. Click on the "Select Video" button to choose a video file.
5. Once the video is selected, the application will start detecting fights in the video.
6. If a fight is detected, a visual notification will be displayed on the video frame and an alarm sound will play.

## Acknowledgements

- TensorFlow Object Detection API: https://github.com/tensorflow/models/tree/master/research/object_detection
- EfficientDet: https://github.com/google/automl/tree/master/efficientdet
