# CV_construction
This repository implements computer vision tasks (object detection and image classification) to construction datasets

## Requirements
Tensorflow 2.10 <br>
protoc 3.14

## Files and folders
The models folders is the Object Detection API folder. One can follow the following tutorial to install the Object Detection API: https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html <br>
The datasets folder contain the datasets used for the project <br>
The training_soda folder contains the fine=tuning of a pre-trained object detection model on a construction dataset (SODA dataset: https://shaunyuan22.github.io/SODA/) <br>
The classification_building folder contains the fine tuning of a pretrained model on the USA OSM and Google StreeView data for a classification of building type task.
 
