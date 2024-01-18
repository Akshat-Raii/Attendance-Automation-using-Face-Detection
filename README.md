# Attendance Automation using Face Detection
## Introduction
This project implements an attendance automation system using face detection. The system utilizes computer vision techniques, Firebase Realtime Database, and Firebase Storage to manage student information, attendance records, and images.

## Features
* **Face Detection:** Utilizes the face_recognition library to detect faces in the webcam feed.
* **Firebase Integration:** Connects to Firebase Realtime Database and Firebase Storage to store student data and images.
* **Attendance Portal:** Displays an interactive attendance portal with real-time face recognition.
* **GUI:** Basic Tkinter based GUI to enter data in databse.
* **Lighting:** Works in low-light conditions.
## Requirements
Ensure you have the following dependencies installed:

### In windows machines download Visual Studio with Development in C++ to successfully install these libraries .

* firebase-admin==5.0.1
* opencv-python==4.5.3
* cvzone==1.5.3
* face-recognition==1.3.0
* numpy==1.21.2
* Pillow==8.3.2


You can install them using:

  `pip install -r requirements.txt`
## Usage

1. **Firebase Configuration:**
   - Add your Firebase service account key (JSON) to the project.
   - Update the Firebase Realtime Database and Storage URLs in the code.

2. **Run Database Maker:**

`python databaseMaker.py`
* If you want to initialize the database with the provided data, run the databaseMaker.py file.
3. Run Admin Portal :

`python adminPortal.py`
* Use the Admin Portal to add additional student data. Upload student images through the portal.

4. Run Encodings Generator :

`python encode.py`
* Generate face encodings based on the uploaded images

5. Run Main script :

`python main.py`
* Execute the main script to start the attendance automation system.

## Acknowledgments
This project utilizes the face_recognition library by Adam Geitgey. Special thanks to the author and contributors for providing an excellent face recognition tool.

## Contributing
Feel free to contribute to the project by opening issues or submitting pull requests. Follow our Contribution Guidelines.

## License
This project is licensed under the MIT License.


