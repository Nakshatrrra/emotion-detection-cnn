# Emotion_detection_with_CNN

### Create Virtual environment

-  python -m venv venv
- .\venv\Scripts\activate
- deactivate

### Packages need to be installed
- pip install numpy
- pip install opencv-python
- pip install keras
- pip3 install --upgrade tensorflow
- pip install pillow

  or just
- pip install -r requirements.txt

### download FER2013 dataset
- from below link and put in data folder under your project directory
- https://www.kaggle.com/msambare/fer2013

### Train Emotion detector
- with all face expression images in the FER2013 Dataset
- command --> python TranEmotionDetector.py

It will take several hours, you will find the trained model structure and weights are stored in your project directory.
emotion_model.json
emotion_model.h5

copy these two files create model folder in your project directory and paste it.

### run your emotion detection test file
python TestEmotionDetector.py

![image](https://github.com/Nakshatrrra/emotion-detection-cnn/assets/95171021/a44dd01f-c42d-4697-a571-a042b6c4ce47)

