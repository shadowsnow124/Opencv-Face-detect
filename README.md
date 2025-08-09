# openCV face detect

This Project allows you to real-time face detection through a webcam or video. It use the OpenCV library and a pre-trained Haarcascades face detector.

## Requirement

### Minimum

- Webcam
- Python 2.x (Not recommand)
- OpenCV library (`cv2`)

### Recommand ( 30 fps )

- 2Ghz+ CPU
- Python 3.x

## Installation

This script request OpenCV library, You can install the librarie using:

```bash
pip install opencv-python
```

## Usage
1. Clone the repository or download the script.
2. Connect your webcam to your computer
3. Run the script using your IDE or the following command:
```bash
python main.py
```

You can also use a video file instead of using the webcam by modifying the `cap = cv2.VideoCapture(0)` line in the script, And replace it with your video path

## Control
- press `q` while the OpenCV window is in focus.
