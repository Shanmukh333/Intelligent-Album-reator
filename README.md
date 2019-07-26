# Intelligent-Album-reator
Image processing using convolutional nearal networks.
INTELLIGENT ALBUM CREATOR
INTRODUCTION
Artificial intelligence is considered to be the trending technology of the future. Already there are a number of applications made on it. Due to this, many companies and researchers are taking interest in it. But the main question that arises here is that in which programming language can these AI applications be developed? There are various programming languages like Lisp, Prolog, C++, Java and Python, which can be used for developing applications of AI. Among them, Python programming language gains a huge popularity and the reasons are as follows −
Python involves very less coding and simple syntax among other programming languages which can be used for developing AI applications. Due to this feature, the testing can be easier and we can focus more on programming
A major advantage for using Python for AI is that it comes with inbuilt libraries. Python has libraries for almost all kinds of AI projects. For example, NumPy, matplotlib, nltk, Pandas are some of the important inbuilt libraries of Python.

OBJECTIVES OF RESEARCH
Intelligent Album Creator is built for speed and ease for use. It automatically gathers photos and displays in our library by using “face detection algorithm” and “LBPHFaceRecoginzer”.By this we seperate and save the pictures of different persons in different folders and can achieve image prediction.

PROBLEM STATEMENT
This project works on gathering pictures into our library using “face detection” technique and by “LBPHFaceRecognizer”.We can consider ‘Google photos’ as a real time application.


DATA COLLECTION
The dataset can be taken from previous existed images from the computer or can be collected using the “face dectection algorithm”.In these two ways the data collection can be done based on the user preference the data can be taken.



METHODOLOGY
EXPLORATORY DATA ANALYSIS:
 
->Installation of opencv using ‘pip install opencv-python’ in               anaconda prompt to import ‘cv2’.

->The images used as dataset are taken from the existing images or can be extracted from “face detection algorithm”.
 
->The “LBPHFaceRecognizer” detects faces from the dataset and labels are created for each person and the dataset is trained using “recognizer.train”.

->The trained dataset is inserted into the “face detection algorithm”.The “recognizer.predict” helps in predicting the output whenever the face is detected.
->Whenever the face is detected it compares the detected face with the trained model and predicts the person that is detected and labels the person on the output screen for the easy understanding of the user.


 

 ->During face detection


->The detected face images are captured one by one and are sorted by the face detected and stored in their respective folders of the given path.








->This is about the face detection and prediction which shows that the image is detected and stored.
DATA MODELLING
“Face Detection”, ”LBPHFaceRecognizer” and ‘prediction’ algorithms are to be applied to achieve our requirements.To implement these algorithms ‘opencv’ which comes with a lot of pre-trained classifiers is to be installed in order to import ‘cv2’.Haar cascade files like ‘face_cascade’ and ‘eye_cascade’ are used to complete the face detection algorithm.Training and testing of the data set is done using “LBPHFaceRecognizer” algorithm.
FINDINGS AND SUGGESTIONS
There are many real time applications like Google Photos, Prime photos from Amazon and A+gallery.
For Example,A+ automatically organizes your photos and lets you to view them by location,date and year.Storing or sync photos to cloud is simple .they include ability to search by colour and favourte albums.
CONCLUSION
This Intelligent Album Creator helps in separating the photos using the Face detection, Recognizer and Prediction algorithms.We can keep all photos in one folder, by using these classifiers we can separate and save the photos of different persons in different folders.




