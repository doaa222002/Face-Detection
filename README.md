# Face Detection
# OverView:
This is a simple face detection application built using Streamlit and OpenCV. It allows users to upload an image, and the app will detect and highlight faces using a pre-trained Haar Cascade classifier.

# Features:
Upload an image in jpg, jpeg, or png format.

The application will automatically detect any faces present in the image.

Detected faces are highlighted with a rectangular box.

The processed image with face detection is displayed directly in the app.

# How it Works
Image Upload: The user uploads an image file through the Streamlit interface.

Face Detection: The app uses OpenCV's CascadeClassifier with the haarcascade_frontalface_default.xml model to detect faces in the image.

Face Highlighting: If faces are detected, a rectangle is drawn around each face.

Display Results: The original image and the face-detected image are displayed within the app.

# Dependencies
Streamlit: For creating the user interface.

OpenCV: For image processing and face detection.

NumPy: For efficient handling of image data.
