# SurfaceDetection
This project focuses on surface detection using the OpenCV library in Python. It was developed for a Mars Rover Competition on behalf of Team Inferno DTU to determine the characteristics of the Martian terrain based on video feed or individual images. The code classifies the surface as rough, smooth, or other based on specific visual cues.

The python file TopicToVideo.py is used for the usability of this python code with ROS topics as we were recieving remote video feed from the camera on our Mars rover.

Prerequisites
Before running the code, make sure you have the following dependencies installed:

1) Python 3.x 

2) OpenCV

3) NumPy 

You can install OpenCV and NumPy using pip:
```
pip install opencv-python
pip install numpy
```
Usage
To use the surface detection code, follow the steps below:

For video feed:

1.) Clone the repository:
```
https://github.com/shubhexists/SurfaceDetection
cd surface-detection
```
2.) Run the Python script:
```
python VideoTry.py
```
The script will start capturing video from the default camera feed. Press q to stop the program.

For individual images:

1.) Clone the repository:
```
https://github.com/shubhexists/SurfaceDetection
cd surface-detection
```
2.) Place the image path at the appropriate location in the file.

3.) Run the python file:
```
python ImageTry.py
```
Contact - 

If you have any questions or suggestions, feel free to contact me at shubh622005@gmail.com .
