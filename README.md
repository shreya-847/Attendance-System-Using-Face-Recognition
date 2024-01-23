# Attendance-System-Using-Face-Recognition
This project is an Automatic attendance tracking system. This Python-based application uses `OpenCV` and `face_recognition` for accurate face detection and recognition. The system records attendance with timestamps and is easy to set up and customize.

Requirements:
Python 3.x
OpenCV
face_recognition
numpy

## Project Files:

### 1. `attendance_system.ipynb`

This notebook serves as the core of the Attendance System. It utilizes OpenCV and the face_recognition library for face detection and recognition. The script captures attendance in real-time and provides a Streamlit web interface for monitoring and customization.

### 2. `<currentdate>.csv`

The CSV file, named according to the current date, stores the attendance records for the day. It includes a list of students who were marked present, along with corresponding timestamps.

### Instructions for Customization:

- The system is pre-configured with images of "Navya" and "Shreya" for face recognition. To use images of different individuals, create a folder with the desired images and update the path in the `AttendanceSystem.ipynb` notebook to point to that folder.

- **How to Customize Images:**
    1. Create a folder with your desired images.
    2. Update the image paths in the `AttendanceSystem.ipynb` notebook to the path of your image folder.
    3. Continue with the rest of the notebook, ensuring that the system recognizes the new individuals for attendance tracking.

Feel free to explore and adapt the code to suit your specific requirements. Contributions and enhancements to the project are highly encouraged!


