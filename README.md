
# Facial-Expression-Recognition
The objective of this project is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). I have used OpenCV to automatically detect faces in images and draw bounding boxes around them. Once you have trained, saved, and exported the CNN, you will directly serve the trained model to a web interface and perform real-time facial expression recognition on video and image data. 



**The camera.py file consists of a function**
> cv2.VideoCapture("\path") 

**which takes the path of the video as input. If you want to take input from your webcam simply change the function as follows:**
>cv2.VideoCapture(0)

**This is a pre-trained model so you can directly type the following command in your terminal to run the project**
>python3 main.py

**Your web app will be running on http://0.0.0.0:5000/**

## Output:

![ezgif com-optimize](https://user-images.githubusercontent.com/55942093/86212481-c6ea8180-bb95-11ea-8a9b-7e44aa6bc051.gif)




