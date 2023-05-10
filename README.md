tequ-node-red-triton-pre-process-tf
=====================

Pre-process data for NVIDIA Triton Inference Server.

## Install

Run the following command in your Node-RED user directory - typically `~/.node-red`

        npm install Lapland-UAS-Tequ/tequ-node-red-triton-pre-process-tf

## Information

Pre-processes image for inference.

Supports object detection models trained using:
- Tequ TF2 training pipeline
- Microsoft Custom Vision (Compact S1) 

https://github.com/Lapland-UAS-Tequ/tequ-tf2-ca-training-pipeline

Supports object detection models from Tensorflow 2 Detection Model Zoo
- SSD MobileNet v2 320x320
- SSD MobileNet V2 FPNLite 320x320
- SSD MobileNet V2 FPNLite 640x640

https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md

Dependencies
- https://www.npmjs.com/package/@tensorflow/tfjs-node-gpu
