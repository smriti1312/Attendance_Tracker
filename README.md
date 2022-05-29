 Attendance_Tracker

A Tracker that uses a face recognition system to track your attendance. Here , I have used python and HTML in this project.


 LIBRARIES used :
•	Numpy
•	Pandas
•	Face_recognitiom
•	OS
•	Open CV
•	Datetime
•	Flask
 
 
 
 
PROCESS :
1.	Take some images for training the model.
2.	Convert them into RGB format
3.	Find the Face Encodings ( A Face Encoding is basically a way to represent the face using a set of 128 computer-generated measurements .)
4.	for making this model user-defined we will be using Webcam, 
•	First, Read the Image using a Webcam
•	Resize the image as it will increase the speed of the system.
•	Convert the image to RGB format.
•	Take the Encodings of Image taken by Webcam.
5.	Match the encodings taken by Webcam with the images we have already stored for training the model, if it matches face will be recognized otherwise not.


