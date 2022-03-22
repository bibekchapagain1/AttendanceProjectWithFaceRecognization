
# Attendance Project With Face Recognization using OpenCV

This was a project I started back in September 2021 when I was teaching Computer Science in Kathmandu Pragya Kunja School. I started learning more about concept of object detection.
I started looking different tutorial videos regarding object detection, read different articles and blogs.

## Acknowledgements

 -I started looking different tutorial videos regarding object detection, read different articles and blogs. I came accross a brilliant article by Adam Geitgey titled "Machine Learning is Fun! Part 4: Modern Face Recognition with Deep Learning". [Link to the article](https://medium.com/@ageitgey/machine-learning-is-fun-part-4-modern-face-recognition-with-deep-learning-c3cffc121d78)
 
## Description
The Steps Involved:
1. Finding all the faces:
-Histogram of oriented gradients (HOG) method is used to encode the images and extract different facial features then identify the faces in the image.

2. Analyze the facial features:
-Deep Neural Network is trained to find 128 measurements in each faces. We provide some known faces to train the Neural Network withe the unknown faces as well. Then try to find 128 measurements in each faces.

3. Compare against the known faces:
-The measurements extracted from known faces are compared with the given unknown faces. We have to find the person in our database of known people who has the closest measurements to our test image.

4. Making the prediction:
-Finally we can make the prediction by using SVM classifier which gives us the name of predicted person as a result.
However the auther combined all these methods and created a python library call "Face recognization" which is used in this project to recognize different faces.

Project Result:
In this attendance project, i used the face recognization technique to take attendance of my students during their computer science class. I stored their names and their attendance time as record in csv file. The result was mostly accurate.

Face recognization:


## Screenshots

![App Screenshot](https://raw.githubusercontent.com/bibekchapagain1/AttendanceProjectWithFaceRecognization/main/Test%20Results/cover.png)


![App Screenshot](https://raw.githubusercontent.com/bibekchapagain1/AttendanceProjectWithFaceRecognization/main/Test%20Results/s2.png)

## Attendance in Excel

![App Screenshot](https://raw.githubusercontent.com/bibekchapagain1/AttendanceProjectWithFaceRecognization/main/Test%20Results/Attendance.JPG)




