# Helmet_Detection_Using_YOLO

1. Download weights and config file from kaggle:
https://www.kaggle.com/datasets/savanagrawal/helmet-detection-yolov3

2. Generate h5 file using model.py 
<pre>edit the file to add the path to the weights file in WeightReader (line 155)</pre>

3. Use any mp4 video file

4. Edit detect.py file to add the paths to weights file (line 11), config file (line 11), model.h5 file (line 15) and the mp4 video file (line 18)

5. To run the code in google colab, edit detect.py to use cv2_imshow(img) (line 101), else cv2.imshow("Image", img) can be used
<pre>
from google.colab.patches import cv2_imshow
</pre>
