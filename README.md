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

It will take several hours depends on your processor. (On i7 processor with 16 GB RAM it took me around 4 hours)
after Training , you will find the trained model structure and weights are stored in your project directory.
emotion_model.json
emotion_model.h5

copy these two files create model folder in your project directory and paste it.

### Run emotion detection test file
python TestEmotionDetector.py
