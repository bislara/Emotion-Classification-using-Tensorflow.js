# Emotion Classification using Tensorflow.js
 Classify the emotion in real time and play music according to the emotion


### This is a real-time Emotion detection using [TensorFlow.js](https://js.tensorflow.org/) to load a pretrained model into the browser .
[![Packagist](https://img.shields.io/badge/TensorFlow-1.10.1-orange.svg)]()
[![Packagist](https://img.shields.io/badge/Keras-2.2.2-blue.svg)]()
[![Packagist](https://img.shields.io/badge/Python-3.5.0-blue.svg)]()
[![Packagist](https://img.shields.io/badge/TensorFlow.js-0.12.6-orange.svg)]()
## Abstract 
### Detect faces
* We use two methods to detect faces:

  1. [Chrome Shape Detection API](https://www.chromestatus.com/feature/4757990523535360)
  2. [face-api.js](https://github.com/justadudewhohacks/face-api.js/)
  
### Dataset
* We combine two datasets:
  1. Microsoft [FERPlus](https://github.com/Microsoft/FERPlus) as one of the dataset to train the emotion-detect model. 
  2. Real-world Affective Faces Database [(RAF-DB)](http://www.whdeng.cn/RAF/model1.html) as another dataset.

### Convert Model
* Use [TensorFlow.js converter](https://github.com/tensorflow/tfjs-converter) convert Keras model to .json file for loading and running Javascript inference.

## Requirements
* For **MobileNetWebcam.html**:

  [Chrome Shape Detection API](https://www.chromestatus.com/feature/4757990523535360) :
FaceDetector: Chrome on Android, macOS, Windows 10 platfrom.
Go to chrome browser ```chrome://flags/#enable-experimental-web-platform-features``` and enable the feature 
<img src="https://i.imgur.com/7JhkpJn.png" width="500">
