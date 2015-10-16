# OpenCV-detection-models
OpenCV public trained detection models: Haar, HOG and other.

There are public XML-files of trained models to detection of different objects: cars, planes, people, animals, plants and other most popular objects.

**This is branch for OpenCV 3.0**

Available branches:

* [OpenCV 2.4.12](https://github.com/AlexeyAB/OpenCV-detection-models/tree/master)
* [OpenCV 3.0](https://github.com/AlexeyAB/OpenCV-detection-models/tree/3.0)


Used detection methods:

* HaarCascades [cv::CascadeClassifier (C++ class)](http://docs.opencv.org/master/d1/de5/classcv_1_1CascadeClassifier.html#gsc.tab=0)
* HaarCascades CUDA [gpu::CascadeClassifier_GPU (C++ class)](http://docs.opencv.org/master/d9/d80/classcv_1_1cuda_1_1CascadeClassifier.html#gsc.tab=0)
* DPM [cv::DPMDetector (C++ class)](http://docs.opencv.org/master/df/dba/classcv_1_1dpm_1_1DPMDetector.html#gsc.tab=0)
* HOG [cv::HOGDescriptor](http://docs.opencv.org/master/d5/d33/structcv_1_1HOGDescriptor.html#gsc.tab=0)
* HOG CUDA [cv::cuda::HOG (C++ structure)](http://docs.opencv.org/master/de/da6/classcv_1_1cuda_1_1HOG.html#gsc.tab=0)


Sources of models:

* [Itseez/opencv_extra - DPM (LatentSVMdetector)](https://github.com/Itseez/opencv_extra/tree/master/testdata/cv/dpm/VOC2007_Cascade)
* [Itseez/opencv - cascades: Haar, HOG and LBP](https://github.com/Itseez/opencv/tree/master/data)


Soft for training:

* HaarCascades: https://github.com/mrnugget/opencv-haar-classifier-training
* HOG: https://github.com/DaHoC/trainHOG


OpenCV documentation: http://docs.opencv.org/master/#gsc.tab=0