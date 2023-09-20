# Facial Attendance Project

This Python project is designed to perform facial attendance tracking. It uses the `face_recognition` library to detect and recognize faces in real-time through your computer's webcam. The project includes features such as marking attendance for recognized faces and generating a CSV file to record the attendance.

## Requirements

Before running this project, make sure you have the following Python libraries installed:

- cmake (You can install it using `pip install cmake`)
- face_recognition (You can install it using `pip install face_recognition`)
- opencv-python (You can install it using `pip install opencv-python`)
- numpy (You can install it using `pip install numpy`)

## Getting Started

1. Clone or download this repository to your local machine.

2. Navigate to the project directory.

3. Create a `faces` folder in the project directory and add the photos of the individuals whose attendance you want to track. Make sure each photo is labeled with the individual's name (e.g., "harry.jpg" and "rohan.jpg").

## Usage

1. Run the project by executing the Python script.

   ```bash
   python facial_attendance.py
2. The webcam will open, and it will start detecting and recognizing faces in real-time.

3. If a recognized face is detected, the person's name and "Present" will be displayed on the video feed.

4. If a recognized person's name is found in the students list, their attendance will be marked, and the current time will be recorded in a CSV file named with the current date (e.g., "YYYY-MM-DD.csv").

5. To exit the application, press the "q" key.


## Notes

- This project only marks attendance for individuals whose photos are present in the `faces` folder. If an unrecognized face is detected, it will prompt you to add their photo to the folder before marking their attendance.

- The attendance records are stored in CSV files with filenames in the format "YYYY-MM-DD.csv," where "YYYY-MM-DD" is the current date.

- Ensure good lighting and clear photos in the `faces` folder for better recognition results.

Feel free to customize this project to suit your specific needs, such as adding more faces to the `faces` folder or modifying the attendance recording format.
