# Real-time hand tracking using OpenCV and MediaPipe libraries.

## Files Description

### 1. HandTrackingMinimum.py
A basic implementation of hand tracking that includes:
- Real-time video capture
- Hand landmark detection
- FPS (Frames Per Second) display
- Visualization of hand tracking points
- Specific tracking of index finger tip (landmark #8)

### 2. HandTrackingModule.py
A more structured, object-oriented implementation that provides:
- `handDetector` class with customizable parameters
- Methods for hand detection and landmark position tracking
- Support for multiple hands
- Configurable drawing options
- Easy integration into other projects

## Features
- Real-time hand tracking
- Multiple hand detection support
- FPS monitoring
- Landmark visualization
- Configurable detection parameters
- Easy-to-use hand tracking module

## Requirements
- Python 3.x
- OpenCV (`cv2`)
- MediaPipe (`mediapipe`)
- Time module (`time`)

## Usage

### Basic Implementation
```python
python HandTrackingMinimum.py
```

### Using the Module
```python
python HandTrackingModule.py
```

## Controls
- Press 'q' to quit the application

## Parameters
The `handDetector` class accepts the following parameters:
- `mode`: Static image mode (default: False)
- `maxHands`: Maximum number of hands to detect (default: 2)
- `detectionCon`: Minimum detection confidence (default: 0.5)
- `trackCon`: Minimum tracking confidence (default: 0.5)

## Notes
- The webcam must be properly connected and accessible
- Good lighting conditions will improve tracking accuracy

- The application uses landmark detection to track 21 different points on each hand

