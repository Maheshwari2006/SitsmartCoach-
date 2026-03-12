# SitSmart Coach

SitSmart Coach is an AI-based posture monitoring desktop assistant that helps users maintain healthy sitting posture while working on a computer.

The application uses computer vision and pose detection to monitor posture, elbow angle, screen distance, and head direction in real time.

Features:

• Real-time posture detection using MediaPipe  
• Smart elbow angle analysis  
• Distance detection from screen  
• Gaze tracking (left / right / center)  
• Floating popup desktop coach  
• Break reminder system  
• Startup automation for Windows  
• Lightweight background monitoring  

Technologies Used:

Python  
OpenCV  
MediaPipe  
Tkinter  
NumPy  

How it Works:

1. Webcam captures the user's posture
2. MediaPipe Pose detects body landmarks
3. Application calculates:
   - Elbow angle
   - Distance from screen
   - Head direction
4. Feedback is displayed in a floating popup window
5. Periodic break reminders encourage healthy work habits

Installation:

Clone the repository
