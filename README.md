Here is a project for special surveillance in Python.
This project uses OpenCV and face_recognition libraries to detect and recognize faces. 
It has a folder called 'faces' where you can put images of people you want to monitor. 
The program will encode the faces and compare them with the faces in the webcam feed to mark attendance. 
It also records the time of detection in a CSV file.
Make sure you have the required libraries installed (cv2, numpy, face_recognition). 
Also, create a folder named 'faces' in the same directory as the script and put your face images in it.
Run the script and it will open a window showing the webcam feed with detected faces marked and their names. 
It will also record attendance in the Attendance.csv file.
