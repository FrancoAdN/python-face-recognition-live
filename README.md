Python Face Recogntion Algorithm


to run this code you'll need to have installed:
    face-recognition (pip install face-recognition)    
    numpy (pip install numpy)
    opencv (pip install opencv-python)

if you have a GPU I recommend you use a cnn model instead of hog

to tell the program how you are you need to crop some images with your face and place it in a folder with your name. It also works with more than one person

notice that is a live version of a face-recognition so, to run it properly, you'll need to have a webcam otherwise it won't work at all. If you have more than one camera and you can tell the program which one you want to use by changing the parameter to this function "video_capture = cv2.VideoCapture(0)"

Enjoy it!


