# Emotion-Detection-model
This model uses real-time images/video to predict the emotion of a person in the camera. This model was trained on dataset from Kaggle. There are seven categories of emotions: Angry, Happy, Sad, Surprise, Neutral, Fear and Disgust.
Steps taken:
1. **Feature Extraction**: Converted the image into grayscale and converted its pixel into NumPy array and reshaped it.
2. **Normalization**: Normalize the data.
3. **Label Encoding**: Used LabelEncoder to convert categorical variable (labels of images) into numerical format.
4. **Model**: Created a Sequential Model using Conv2D layers and MaxPooling.
5. **Deployment**: Saved the model as a json file and created a simple interface in VS Code which uses webcam to scan the face and predict the emotion.
