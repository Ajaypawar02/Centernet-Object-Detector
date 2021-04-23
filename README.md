# Centernet-Object-Detector

Object Detection is the computer vision which deals with identifying and locating object of certain classes in the image. We did the object detection using CenterNet. CenterNet considers the center of a box as an object as well as a key point and then uses this predicted center to find the coordinates/offsets of the bounding box.

For this Object Detection we used WIDER FACE DATASET and VGG19 Architecture .WIDER FACE dataset is a face detection benchmark dataset, of which images are selected from the publicly available WIDER dataset. There are total of 32,203 images out of which we used 8000 images for training. VGG19 architecture consists of total 19 layers out of which 16 are of  convolution layers, 3 Fully connected layer, 5 MaxPool layers and 1 Softmax layer. It has total of 143,667,240 parameters.
