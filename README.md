# Deepfake detection using Deep Learning (ResNext and LSTM)

## Give a Star⭐ to repo 
</a>

## Latest Update
#### We have dockerised the [Django Application](https://github.com/abhijitjadhav1998/Deepfake_detection_using_deep_learning/tree/master/Django%20Application) now you can spin up a container within seconds without worring about dependencies


## 1. Introduction
This projects aims in detection of video deepfakes using deep learning techniques like ResNext and LSTM. We have achived deepfake detection by using transfer learning where the pretrained ResNext CNN is used to obtain a feature vector, further the LSTM layer is trained using the features. For more details follow the [documentaion]




## 2. Directory Structure
For ease of understanding the project is structured in below format
```
Deepfake_detection_using_deep_learning
    |
    |--- Django Application
    |--- Model Creation
    |--- Documentaion
```
1. Django Application 
   - This directory consists of the django made application of our work. Where a user can upload the video and submit it to the model for prediction. The trained model performs the prediction and the result is displayed on the screen.
2. Model Creation
   - This directory consists of the step by step process of creating and training a deepfake detection model using our approach.
3. Documentation
   - This directory consists of all the documentation done during the project
   
## 3. System Architecture
<p align="center">
  <img src="https://github.com/abhijitjadhav1998/Deepfake_detection_using_deep_learning/blob/master/github_assets/System%20Architecture.png" />
</p>

## 4. Demo 


<p align="center">
  <img src="https://github.com/abhijitjadhav1998/Deepfake_detection_using_deep_learning/blob/master/github_assets/fakegif.gif" />
</p>

## 5. Our Results

| Model Name | No of videos | No of Frames | Accuracy |
|------------|--------------|--------------|----------|
|model_84_acc_10_frames_final_data.pt |6000 |10 |84.21461|
|model_87_acc_20_frames_final_data.pt | 6000 |20 |87.79160|
|model_89_acc_40_frames_final_data.pt | 6000| 40 |89.34681|
|model_90_acc_60_frames_final_data.pt | 6000| 60 |90.59097 |
|model_91_acc_80_frames_final_data.pt | 6000 | 80 | 91.49818 |
|model_93_acc_100_frames_final_data.pt| 6000 | 100 | 93.58794|




   
## 6. License

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## 8. We welcome Open Source Contribution. 
### Below are the some changes that can be applied to the project. New Ideas will be appreciated.
- [ ] Deploying the applications in free cloud 
- [ ] Creating open source API for detection
- [ ] Batch processing of entire video instead of processing first 'x' frames.
- [ ] Optimizing the code for faster execution.
#### Completed 
- [X] Dockerizing the app
- [X] Enabling working of project on Non Cuda Computers. i.e on normal or AMD GPUs

