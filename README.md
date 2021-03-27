# Python-Face-Recognizer
Built Face Recognizer which gets frames from camera with OpenCV and passes frames through face-recognizer library (internally uses dlib's deep learning face recognition).

Followed tutorial here: [https://towardsdatascience.com/building-a-face-recognizer-in-python-7fd6630c6340](https://towardsdatascience.com/building-a-face-recognizer-in-python-7fd6630c6340)

### STEPS
- import images from folder
- file names are listed and assigned to "names"
- train faces (pass each example image to face_recognition library)
- test faces (use webcam to find face locations & face encodings then compare with known face distances)