Human Pose Estimation using MediaPipe :

 Overview:
This project implements human pose estimation on a pre-recorded video using MediaPipe and OpenCV. It detects 33 body landmarks per frame and overlays skeletal connections to visualize full-body posture tracking.

The processed output is saved as an annotated video file.

 Features:
 
Detects full-body pose landmarks
Draws skeletal joint connections
Processes video frame-by-frame
Saves output as MP4 format
Supports high-resolution video input (with resizing optimization)

Tech Stack

Python 3.x
OpenCV
MediaPipe

 Installation:
 
Install required dependencies:
pip install opencv-python mediapipe

How to Run:

Place your input video inside the project directory.
Update the video path inside pose_estimation.py.

Run the script:

python pose_estimation.py
The processed output will be saved as:
output.mp4

Sample Output:

The output video contains:
33 body keypoints detection
Real-time skeletal tracking
Pose connection visualization

(Download output.mp4 from this repository to view the result.)

Future Enhancements:

Real-time webcam pose detection
Exercise repetition counter
Joint angle calculation
Posture correction feedback system
Web-based interface integration
