
# Drowsiness Detector using OpenCV and dlib

This Python program uses OpenCV, dlib, and pyttsx3 to detect drowsiness in a person's eyes through a webcam feed. When drowsiness is detected, an audio alert is generated to wake up the person.

## Prerequisites

Before running this program, make sure you have the following libraries installed:

- OpenCV
- dlib
- pyttsx3
- scipy

You can install these libraries using `pip`:

```bash
pip install opencv-python-headless
pip install dlib
pip install pyttsx3
pip install scipy
```

## Usage

1. Clone this repository or download the code.

2. Ensure that you have a trained facial landmarks model file (`shape_predictor_68_face_landmarks.dat`). You can download it from the [dlib website](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2) and place it in the same directory as the code.

3. Run the Python script:

   ```bash
   python drowsiness_detector.py
   ```

4. The webcam feed will open, and the program will start detecting drowsiness in your eyes.

5. If drowsiness is detected, an audio alert will be played to wake you up.

6. To exit the program, press the "Backspace" key.

## Configuration

You can adjust the sensitivity of drowsiness detection by changing the threshold value in the code:

```python
if Eye_Rat < 0.25:  # You can change this threshold value
```

