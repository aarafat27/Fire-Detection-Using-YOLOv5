# Fire-Detection-Using-YOLOv5
This project is aimed at developing a fire detection system using YOLOv5x, a state-of-the-art object detection algorithm. The system can detect the presence of fire in real-time using a live video stream or pre-recorded footage.


![val_batch0_pred](https://user-images.githubusercontent.com/99079792/229861115-aba75455-82b8-4008-bf07-d2ada5deaa16.jpg)


# Language & libraries:
* This code is written in Python 
* PyTorch: A popular open-source machine learning framework used for building and training deep neural networks.
* IPython: A powerful interactive shell and notebook interface for Python.
* roboflow: A Python library for accessing Roboflow API to download and manage datasets.
* glob: A Python module used for finding all the pathnames matching a specified pattern.
* IPython.display: A module used for displaying images in Jupyter notebooks or the IPython shell.

# YOLOv5x
YOLOv5x is a state-of-the-art real-time object detection algorithm that uses deep neural networks to detect and classify objects in images and video streams. It is a successor to the popular YOLOv4 and builds on its success by improving accuracy while maintaining a real-time performance. YOLOv5x is part of the YOLO (You Only Look Once) family of object detection models that use a single neural network to make predictions.

# Key Features of YOLOv5x

 * Real-time object detection: YOLOv5x is capable of detecting and classifying objects in real-time, making it suitable for a wide range of applications such as surveillance systems, self-driving cars, and robotics.

 * Improved accuracy: YOLOv5x has improved accuracy compared to its predecessor, YOLOv4, thanks to several architecture and training improvements.

 * Efficient architecture: YOLOv5x has a streamlined architecture that makes it faster and more memory-efficient than other object detection models.

 * Flexible inputs: YOLOv5x can take inputs of various sizes and aspect ratios, making it suitable for detecting objects in a wide range of images and videos.

 * Easy to use: YOLOv5x is easy to use and comes with pre-trained models that can be fine-tuned on custom datasets.

# Results

![results](https://user-images.githubusercontent.com/99079792/229897873-6a77e59d-560f-4449-8230-f03f96e4fab3.png)


# F1 Curve

![F1_curve](https://user-images.githubusercontent.com/99079792/229897584-53f4b136-4ca0-4717-9931-815a87d709c1.png)


# N.B. 
The Jupyter notebook file named Fire_Detection_Using_YOLOv5.ipynb will not work properly.
The model was built in Google Colab. From the colab the model file was downloaded as ipynb file (There was no other option).
Because of GPU limitation and the path dependencies, this fill will arise in error.
It is suggested to run this file in the Google Colab.
