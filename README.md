# Title
## Face Recognition System using AI and Machine Learning
This project implements a face recognition system using machine learning algorithms to identify and verify faces. The model is trained with both known and unknown images, allowing it to recognize individuals.

## Key Features:
- Face Detection & Recognition: Detects faces in images and identifies individuals based on pre-trained data.
- Real-time Recognition: Uses OpenCV and the face_recognition library to process video input for live face recognition.
- Trained on Known and Unknown Images: The system distinguishes between known faces (labeled) and unknown faces (unlabeled).
- Easy to Integrate: Can be used for applications like security systems, attendance tracking, and user authentication.

  ## Technologies Used:
- face_recognition: A Python library for face recognition that simplifies the process of detecting and recognizing faces.
- OpenCV: A powerful library for real-time computer vision, used here for video stream handling and image display.

  ## Usage:
 - Load Known and Unknown Images: You should prepare a dataset of known images (people you want the system to recognize). These images will be used for training the recognition model.

### Run the Script:

- The model will attempt to recognize faces in images by comparing the detected faces to the known faces database.
- If a match is found, it will display the name or label of the recognized face.
