# BSL-recognition-model
Final project for MSc Data Science @ University of Birmingham

## Project title 
Sign language recognition model for restaurant-related word-level British sign language

## Project aim
This project aims to build a real-time British sign language (BSL) detector for restaurant settings using Tensorflow and Python. The final product is a trained model that can process real-time input from a webcam and identify the correct meaning. The input consists of restaurant-related word-level signs of the BSL.

## Project objectives
* Train a deep learning model that can recognise different word-level signs of the BSL: since this can be considered to be a supervised learning problem, the accuracy score will be used to measure whether this objective is achieved or not.
* Use the trained model to process real-time video input of the BSL: a video demo of the real-time sign language recognition model will be used to measure the successful delivery of this objective.

## Methodology
A real-time model for sign language recognition would require the use of an action detection technique. First, the video input would be processed to extract keypoints from a skeleton modality point of view. Then, the extracted features would be labelled and used to train an LSTM model, which would learn to classify different sequences of hand gestures and facial movements to match with the correct vocabulary. Lastly, the trained model would be tested against real-time input to evaluate its ability to predict unseen data.

## Data
The dataset required to complete this project would be self-generated by me. It would consist of at least 30 keypoints sequences for each of the word-level BSL signs for the following restaurant-related vocabulary: rice, noodles, soup, chicken, beef, and pork. The input data would be captured by my laptop webcam.
