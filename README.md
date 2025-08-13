FER2013 is used as dataset for this model.
First I extract landmarks from dataset with mediapipe and use them as features in the model. The code is in file "features-extracting.ipynb".
I trained model with only important landmarks such as eyes, eyebrows, nose and lips. (more efficient)
Model is trained with LSTM. The code is in file "lstm-with-face-landmarks.ipynb"
