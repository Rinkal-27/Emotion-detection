# Detection of emotions using CNN

![emotion_detection](https://github.com/datamagic2020/Emotion_detection_with_CNN/blob/main/emoition_detection.png)

### Packages needed to be installed
- pip install numpy
- pip install opencv-python
- pip install keras
- pip3 install --upgrade tensorflow
- pip install pillow

### Download FER2013 dataset for developing model
- from below link and put in data folder under your project directory
- https://www.kaggle.com/msambare/fer2013

### Train Emotion detector to get the model ready
- with all face expression images in the FER2013 Dataset
- command --> python TranEmotionDetector.py

The trained model structure and weights are stored in model directory.
emotion_model.json
emotion_model.h5

### Run emotion detection test file
python TestEmotionDetector.py
