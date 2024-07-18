## Overview :
This project focuses on detecting defects in ball bearings using a combination of YOLOv3 for object detection and Recurrent Neural Networks (RNN) for sequence analysis. The goal is to accurately identify and classify defects in ball bearings to aid in predictive maintenance and quality control.

## Model Training
1)YOLOv3
YOLOv3 is trained on the ball bearing images to detect and locate defects. The configuration and weights files are specified in the training script.

2)RNN
The RNN is trained on sequences generated from YOLOv3 detections to classify the type and severity of the defects. The sequences are stored in sequences.csv.

## Results
The trained models achieve high accuracy in detecting and classifying ball bearing defects. Sample detection results can be found in the results/ directory.
