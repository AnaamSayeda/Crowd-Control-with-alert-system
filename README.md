# 👨‍👩‍👧‍👦 Crowd Control with alert system
## 📣 Introduction
The WHO and health organizations have stated that 2m social distancing guidelines have to be met so that the people can move in a safe and comfortable manner. The key to achive this by controlling how many people can be at a place in a given time. This system counts the number of people in the frame and contains an alert system.The number of people that can enter a place at a given time (limited capacity) can be entered. On the detection of an extra person, the system creates and alarm and shows pop warning message.
## 💡 Methodology and Approach
Image processing has been used to detect and count the number of faces.We do not require all the features of the face.Instead,a bounding box is obtained through coordinates of the face in the image and the number of faces are computed by depending on different areas covered by the number of the coordinates.
## 🚨 Required Libraries and module
* **OpenCV** library in python is used for image processing, video processing, and analysis, facial recognition and detection, etc.
* **Dlib** library in python contains the pre-trained facial landmark detector, and is used to detect the (x, y) coordinates that map to facial structures on the face.
* **Tkinter** library in Python is used for a fast and easy way to create GUI applications and is used to show the pop warning message.
* **Beeply** module in python creates musical notes using computer’s characteristic beep sounds and is used to create an alarm.
## 🖥️ Demonstration
![Untitled design (3)](https://user-images.githubusercontent.com/69802048/135669809-8a74aa2b-8cde-4da0-9e46-7fc2508bf326.png)
![Untitled design (4)](https://user-images.githubusercontent.com/69802048/135670088-4f7d96af-5f46-4a5c-9653-dcf05f45bad2.png)






