
<h1 align="center">Face Mask Detection</h1>

<div align= "center"><img src="[https://i.imgur.com/MfKjyLG.png](https://www.shutterstock.com/image-vector/man-woman-medical-face-protection-600w-1667507122.jpg)"/>
  
<p>Face Mask Detection Model built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.</p>
</div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)
<img src = "https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white"/>
<img src ="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white"/>

![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/techyhoney/Facemask_Detection/issues)
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/techyhoney/Facemask_Detection/blob/master/LICENSE)



## Motivation
In the present scenario due to Covid-19, there rose a need for consistent face mask detection applications which are now in high demand for transportation means, densely populated areas, residential districts, large-scale manufacturers and other enterprises to ensure safety. Also, the absence of large datasets of __‘with_mask’__ images has made this task more cumbersome and challenging. 



## Libraries/ used

- [OpenCV](https://opencv.org/)
- [Keras](https://keras.io/)
- [TensorFlow](https://www.tensorflow.org/)
- [CNN](https://en.wikipedia.org/wiki/Convolutional_neural_network)
- [Caffe-based face detector](https://caffe.berkeleyvision.org/)
- [Streamlit](https://docs.streamlit.io/en/stable/api.html)

## Usecase
The face mask detector is made purely using real non-morphed images. 
This model has 3 applications:
  1. Loading an image from a database and detecting face masks.
  2. Loading an image from a live videocam and detecting face masks.
  3. Loading the direct video stream from a videocam and detecting face masks every 'n' seconds.

The 3rd application makes the model particularly useful in queues at airports, banks, malls and other public places.
Since in a we need to detect every 5-10 seconds, we can use the 3rd mode with great efficiency.

## Dataset
The dataset used can be downloaded here - [Click to Download](https://github.com/techyhoney/Facemask_Detection/tree/master/dataset)

This dataset consists of __4000 images__ belonging to two classes:
*	__with_mask: 2000 images__
*	__without_mask: 2000 images__

The images used were real images of faces wearing masks. The images were collected from the following sources:

* [__Kaggle datasets__](https://www.kaggle.com/search?q=facemask+detection+in%3Adatasets)
* [__RMFD dataset__](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset)
* [__Google Dataset Search__](https://datasetsearch.research.google.com/)

## Prerequisites

All the dependencies and required libraries are included in the file <code>requirements.txt</code>


## Execution
1. Clone the repo
```
$ git clone https://github.com/techyhoney/Facemask_Detection.git
```

2. Change your directory to the cloned repo 
```
$ cd Face-Mask-Detection
```

3. Create a Python virtual environment named 'test' and activate it
```
$ virtualenv test
```
```
$ source test/bin/activate
```

4. Now, run the following command in your Terminal/Command Prompt to install the libraries required
```
$ pip3 install -r requirements.txt
```

## Results

#### Our model gave around 99% accuracy for Face Mask Detection after training.
####          
![](https://i.imgur.com/3vo1w8f.png)

####          

#### We got the following accuracy/loss training curve plots
![](https://i.imgur.com/cLNo6nK.png)
####          
![](https://i.imgur.com/RYiOlCP.png)


## License
[MIT](https://github.com/techyhoney/Facemask_Detection/blob/master/LICENSE)
