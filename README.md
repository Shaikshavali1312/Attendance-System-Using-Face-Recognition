# Attendance-System-Using-Face-Recognition
This project is a Python-based automated attendance management system that utilizes facial recognition to uniquely identify individuals and record their presence. It aims to replace traditional manual attendance marking, which is often time-consuming and prone to human error.



# Features

Real-time Face Detection: Detects faces instantly using a camera feed.



Automated Attendance: Automatically records attendance once a face is recognized.



Live Person Identification: Capable of identifying live individuals for secure logging.


Secure Registration: Includes password authentication for saving new user profiles.

# System Requirements
# Software

Operating System: Windows 10 


Language: Python 


Key Libraries: OpenCV (cv2), NumPy, Pandas, Tkinter (for GUI), and Pillow 


Development Tool: Anaconda Prompt or VS Code 


# Hardware

Processor: 2 GHz or faster 


RAM: 4 GB 


Storage: 128 GB Hard Disk 

# How It Works

New Registration: A user enters their Name and ID, then captures approximately 100 images to create a personal dataset.



Training: The system trains on these images using a Local Binary Patterns Histograms (LBPH) recognizer and saves the data as a .yml file.




Attendance: When "Take Attendance" is activated, the system matches live camera frames against the trained dataset to log the person's ID, name, date, and time into a CSV file.

# Project Structure

StudentDetails/: Stores CSV files with registered user information.



TrainingImage/: Contains captured face samples for training.


TrainingImageLabel/: Stores the trained .yml model and password files.
Attendance/: Stores the final attendance logs in CSV format.
# Conclusion
In this project, we have developed a Machine Learning model specifically designed for Student Attendance Systems in educational institutions or any organization where individuals need to record their presence.



Attendance/: Stores the final attendance logs in CSV format.
