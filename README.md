# Driver-Drowsiness

Driver drowsiness detection is a technology used to alert drivers if they appear to be tired or inattentive while driving. This can be achieved through various methods such as monitoring eye movements, head position, and driving patterns. Some vehicles have drowsiness detection systems built-in, while others use standalone devices that can be added to a vehicle. The goal of drowsiness detection is to prevent accidents caused by fatigued driving and to promote safe driving practices.

# 68 Landmark Detection

Facial landmark detection refers to the process of detecting and locating key points on a face, such as the eyes, nose, mouth, and jawline, using computer vision techniques. It's often used as a preprocessing step for various face-related tasks, such as face alignment, facial recognition, and expression analysis. The 68-point model is a common landmark detection model that identifies 68 landmarks on a face, providing a comprehensive representation of facial features.

The 68 facial landmark detection algorithm is a computer vision technique for locating specific points on the face, such as the corners of the mouth, the tip of the nose, and the edges of the eyebrows. This is typically done using a machine learning model, such as a deep neural network, that has been trained on a large dataset of face images. During the detection process, an input image of a face is fed into the model, which outputs the x and y coordinates of each landmark point. These coordinates can then be used to create a visual representation of the face, with the landmark points marked on the image. The exact workings of the model depend on the specific architecture used, but in general, it involves several stages of processing, such as feature extraction, convolution, pooling, and non-linear activation, to produce the final output.

# Changes to be made in Code for sucessfull running

install all the necessary libraries for eg: cv2,dlibs and many more
predict = dlib.shape_predictor(" ") here in " " put the location of dat file (shape_predictor_68_face_landmarks.dat)

Link for dat file : https://www.kaggle.com/datasets/sergiovirahonda/shape-predictor-68-face-landmarksdat

