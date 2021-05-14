(Go for emotions not for spelling mistakes cuz I am really bad at them) 

# FaceDetect
Face Detection Using OpenCV 
This project requires XML file 'haarcascade_frontalface_default.xml' for detection of the face.  It's the most basic face detection model. Libraries Used are
1. Numpy (Documentation:-https://numpy.org/doc/)
2. OpenCV (Documentation:-https://opencv.org/)
3. sqlite2 (Documentation:-https://docs.python.org/3/library/sqlite3.html)
4. OS (Documentation:-https://docs.python.org/3/library/os.html)
5. Pillow (Documentation:-https://pillow.readthedocs.io/)

The code comprises of 3 function:
1. Data Creator 
2. Trainer
3. Detector

## Data Creator

As the name suggest this function is used to creat data. Using the webcam the face is recorgnised by the xml file mentioned previously. After detecting the face the device takes the snippets of the face creating a database of that fase. We can add additional information like
ID(Type in some ID Number), Name, Age(For Ladies you can hide the info by adding a '#' in the beginning of the line), Gender, Occupation.

## Trainer 

This is the magic code to train the device to recorgnise the face and upgrading the yml file for detection of the face.

## Detector

This function detects the faces using the webcam and using the fata from the database it shows the details of the person.

I have used MySQL browser for the project cuz it's the most effective fot the cause. Databases can be changed, If the recorgnitin is not proper the amount of pictures clicked can also be changed for better result. 

Play with the code to know more about it 

# Enjoyyy.........!!! :)
