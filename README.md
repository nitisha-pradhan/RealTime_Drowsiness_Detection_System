# RealTime_Drowsiness_Detection_System

**About the project:** <br>

⭐ Project: Drowsiness from a person's face is detected in real-time from the webcam feed and an alarm is played to alert the person if the person is found to be drowsy. <br>
⭐ It is made using Deep Learning and OpenCV. <br>
:star: Dataset link: https://www.kaggle.com/akshitmadan/eyes-open-or-closed <br>
⭐ A model is trained to determine whether the eyes of a person are open or closed.<br>
⭐ This model is saved as an h5 file and used with OpenCV to do real-time detection. <br>
⭐ Haar cascade files are used to detect the face, left eye, and right eye. <br>
⭐ Webcam is opened and a Score denoting the level of sleepiness of a person is calculated and displayed on the screen. <br>
⭐ When the score goes above an arbitrary threshold, the alarm.wav starts playing and the screen border blinks red to alert the person.<br>

**How to run:**

1. Download or clone the repo.
2. Ensure all the required python libraries are installed.
3. Run the "drowsiness detection.py" file.
