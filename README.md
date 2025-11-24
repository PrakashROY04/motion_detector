# Motion Detector

A simple computer vision project that detects motion in webcam video using frame differencing.

## Requirements
- Python 3
- OpenCV

Install:
pip install opencv-python


## How it works
- Reads two consecutive video frames.
- Calculates their difference.
- If the difference is large, motion is detected.
- Draws bounding boxes around the moving region.
