# Face-And-Eyes-Detection
I built small project for face and eyes detection. My project can detect one and more faces in image.
You can download and run the full project with Jupeter or othe application. For face detection I took picture from google (Ronaldo picture :))
See below how to use XML data:

## XML for Face detection
face_cascade = cv2.CascadeClassifier('haarcascade_frontalface_default.xml')

## XML for Eyes detection
eye_cascade = cv2.CascadeClassifier('haarcascade_eye.xml')

## XML for Smile detection
smile_cascade = cv2.CascadeClassifier('haarcascade_smile.xml')
