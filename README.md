# sign-language-alphabet-prediction
This project focuses on predicting alphabetic characters from sign language gestures using machine learning techniques. The workflow includes collecting a dataset of hand gesture images, preprocessing the images to extract hand landmarks, training a machine learning model on the preprocessed data, and performing real-time prediction.

Dataset Collection:
The dataset collection process involves capturing images of sign language gestures using a webcam. Each gesture is associated with a specific alphabetic character, and the images are saved in a directory structure suitable for training the model.

Dataset Preprocessing:
Once the dataset is collected, the images are preprocessed to extract hand landmarks using the MediaPipe Hands library. These hand landmarks serve as features for training the machine learning model.

Model Training:
The model training phase involves using the preprocessed dataset to train a Random Forest classifier. This classifier learns to map hand landmarks to the corresponding alphabetic characters, enabling it to predict the sign language alphabet from new gesture images.

Real-Time Prediction:
Following the training, the trained model is deployed for real-time prediction using a webcam. The webcam captures video input, and the model predicts the corresponding alphabetic characters in real-time.

Results:
Screenshots of the real-time prediction results can be found in the "results" directory.  

![Screenshot (224)](https://github.com/Purusothaman12/sign-language-alphabet-prediction/assets/136260916/0913e107-6874-4f25-9847-ed382cc201a7)
![Screenshot (225)](https://github.com/Purusothaman12/sign-language-alphabet-prediction/assets/136260916/ba6b3161-6709-42f5-88b9-77e9c46bca67)
![Screenshot (226)](https://github.com/Purusothaman12/sign-language-alphabet-prediction/assets/136260916/3b22c837-e591-4a52-8f8e-ef376bf39bef)

                Thank You
