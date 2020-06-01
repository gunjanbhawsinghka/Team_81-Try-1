# Team_81-Try-1
## __TRAFFIC SIGN DETECTION AND CLASSIFICATION__

### 1. DESCRIPTION
- This project is a traffic signs detection and classification system on videos using OpenCV. 

- The detection phase uses Image Processing techniques that create contours on each video frame and find all ellipses or circles among those contours. They are marked as candidates for traffic signs.

- In the next phase - classification phase, a list of images are created by cropping from the original frame based on candidates' coordinate. A pre-trained SVM model will classify these images to find out which type of traffic sign they are.

### 2. SYSTEM STRUCTURE
#### 1. There are 3 python files as 3 modules:
- [main.py](main.py) : The start point of the program
- [classification.py](classification.py) : SVM Model to classify traffic signs 
- [common.py](common.py) : Functions for defining SVM Model

#### 2. Other files: 
- [dataset](dataset) : Contains images for training SVM models.
- [0.png](0.png) : Contains non-traffic-sign cropped images which can be recognized as traffic signs
 
 ![](/images/0.png)
- [all_signs.png](all_signs.png) : Contains all used signs 
 
 ![](/images/all-signs.png)
- [data_svm.dat](data_svm.dat) : Saved SVM model after training.
- [demo.gif](demo.gif) : Demo output of the program

 ![](/images/demo.gif)

 
