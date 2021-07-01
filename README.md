##### Face detection and face recognition using Haar-Cascade Classifier, OpenCV, Python and an Ip Camera  ####

## Requirement
- Python 3.9
- OpenCV 4.5.2.52  
        installation syntax: 
        pip install opencv-python
- Numpy 
        installation syntax:
        pip install numpy
- Ip Camera
    This is an android app if you are in same router you can access the video recording
    through the Ip Camera using a specific ip address.


## Outline
This project consist of 3 parts, which are:
1. Creating datasets (face_datasets.py)
2. Train the model (training.py)
3. Face Recognition (face_recognition.py)

## setting up Ip config app
download Ip Camera from playstore and after opening there will be some start server option, slicking start server we will see an ip adress below the screen, opening this ip adress in brower and clicking javascript menu we can acess the camera of mobile phone to ip adress and copying the url of live video we can use them in our application.

## How to run??

1. Folders called 'dataset' and 'trainer' should be in the same directory
2. Run in the command line the face_datasets.py for taking your face image as datasets. Don't forget to set each person's face to unique ID (You need to edit the code everytime, or maybe just change the id variable to raw_input[OPTIONAL])
3. If you have more face to be include, change the ID and run the program again
4. Train your datasets by running training.py
5. Lastly, run face_recognition.py





