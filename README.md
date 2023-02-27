# Helmet_Detection_Using_YOLO

1. download weights and config file from kaggle:
https://www.kaggle.com/datasets/savanagrawal/helmet-detection-yolov3

2. generate h5 file using model.py (edit the file to add the path to the weights file in WeightReader)

3. use any mp4 video file

4. edit detect.py file to add the paths to weights file, config file, model.h5 file and the mp4 video file

5. To run the code in google colab, edit detect.py to use cv2_imshow(img), else cv2.imshow("Image", img) can be used
from google.colab.patches import cv2_imshow
