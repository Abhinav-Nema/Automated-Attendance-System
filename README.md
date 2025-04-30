#Automated Attendace System

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)  
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)

##  Getting Started

Follow these steps to set up and run the project on your system:

1. **Clone or download** this repository to your local machine.
2. Open a terminal in the project directory and run: pip install -r requirements.txt
This will install all the required dependencies.
3. Inside the project folder, **create a directory** named `TrainingImage`.
4. Open both `attendance.py` and `automaticAttendance.py` and **update file paths** according to your system if necessary.
5. Now you're ready to run the app by executing the `attendance.py` script.

##  Project Workflow

Here’s a breakdown of how the system works:

- When you run the app, start by registering your face. Click on **Register New Student**.
- A dialog box will open—enter your **ID** and **Name**, then click on **Take Image**.
- A camera window will appear and capture up to 50 face images (you can modify this number). These are stored in the `TrainingImage` folder. Providing more images improves recognition accuracy.
- After capturing images, click on **Train Image**. This step processes the images and converts them into numerical data for facial recognition.
- Training may take a few moments depending on your hardware.
- Once training is done, click on **Automatic Attendance**, enter the subject name, and the system will mark attendance by detecting faces.
- The system generates a `.csv` file for each subject and stores attendance records separately.
- To view records, click on **View Attendance**, which displays attendance data in a table format.

##  Features

- Face image registration and training
- Real-time face recognition
- Automated attendance recording
- Attendance storage in subject-wise `.csv` files
- GUI-based interface for easy use

### Screenshots

### Simple UI
<img src='https://github.com/Abhinav-Nema/Automated-Attendance-System/blob/main/Project%20Snap/1.PNG'>


## Attendance in tabular format 
<img src=''>
---

Feel free to customize the interface and logic as needed for your own enhancements.
