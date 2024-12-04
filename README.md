# DRIVER-DROWSINESS-DETECTION-SAFETY-MONITORING-SYSTEM
Develop a system that can detect drowsiness in real-time to prevent accidents or unsafe behaviors.
# Driver Drowsiness Monitoring System  

## Overview  
This project implements a **Driver Drowsiness Monitoring System** using Python. The application detects drowsiness in real-time using a webcam and alerts the driver with an alarm if they appear drowsy.

## Features  
- Real-time drowsiness detection using webcam input.  
- Plays an alert sound when the driver is detected as drowsy.  
- User authentication system (Login and Registration).  
- Interactive GUI built using Tkinter.

## How It Works  
The system leverages computer vision and a pre-trained face landmark detector to monitor the driver's eyes.  
- **Eye Aspect Ratio (EAR)**: Calculates the eye aspect ratio to detect if the eyes are closed.  
- **Threshold**: If the EAR falls below 0.25 for 20 consecutive frames, an alert sound is triggered.

## Prerequisites  
Make sure you have Python installed. Install the necessary libraries using the following command:  
```bash
pip install -r requirements.txt
