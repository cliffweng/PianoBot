# YOLO Object Detection

This is part of the series of Automation with Python projects using the likes of OpenCV, MSS, Pyautogui.

This code is mostly from [YOLO Object Detection with OpenCV](https://gilberttanner.com/blog/yolo-object-detection-with-opencv) by [Tanner Gilbert](https://github.com/TannerGilbert?tab=repositories)

## Steps to run the code

- Install the requirements.txt
Copy the following pre-trained file into /model, it is too big for github.
- https://pjreddie.com/media/files/yolov3.weights

These 2 files were pre-downloaded so you don't have to do anything: 
- https://raw.githubusercontent.com/pjreddie/darknet/master/cfg/yolov3.cfg
- https://raw.githubusercontent.com/pjreddie/darknet/master/data/coco.names

YOLO Object Detection on images

```
python yolo.py # use the front-camera
python yolo.py -r # use the on-screen video
```
or
```
python camera_yolo.py
python screen_yolo.py
```
## References
https://gilberttanner.com/blog/yolo-object-detection-introduction
https://github.com/AlexeyAB/darknet
https://python-mss.readthedocs.io/index.html

https://stackoverflow.com/questions/50310613/how-to-capture-screen-using-python-with-better-frame-rate

Object Tracking https://www.pyimagesearch.com/2018/07/30/opencv-object-tracking/

https://github.com/TannerGilbert/Tensorflow-Object-Detection-with-Tensorflow-2.0
