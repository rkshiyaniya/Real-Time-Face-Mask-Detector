# Real Time Mask Detector using Deep Learning ( Keras )

Real Time Mask Detector with Keras, OpenCV. By detecting Face then Classify whether person wearing Mask or Not.

# Requirements

* Python 3.5 +
* Numpy
* Opencv
* Keras ( Tensorflow as backend )
* imutils
* Matplotlib
* sklearn

# Note

* The dataset used can be downloaded here - [Click to Download](https://drive.google.com/drive/folders/1XDte2DL2Mf_hw4NsmGst7QtYoU7sMBVG?usp=sharing)
* Caffe-based Face Detector because it's more accurate and fast

# About Project

* First Load Data and Pre-process it

* Trained model on base of mobilenet_v2 model with pre-trained weights of 'imagenet'

* Save model as 'model_detector.model' ( save_format = h5 )

* Using OpenCV and serialized faceNet (res10_caffe_model) extract Person's Live Face and it's location

* Then our trained serialized 'mask_detector.model' detect whether person wearing mask or not

* Then show it as label to make real-time by OpenCV

# Screenshots

* With Mask ...

![WithMask](ss/with_mask.jpg?raw=true)

* Without Mask ...

![WithoutMask](ss/without_mask.jpg?raw=true)

