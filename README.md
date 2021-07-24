# Face_Mask_Detection

Implemented MobileNetV2 using tensorflow, Keras and OpenCV.
It detect face-masks from real-time video streams.

# Dataset
Dataset taken from few open sources image libraries and google images.

Number of images with mask=1,915 images

Number of images without mask=1,918 images

Used ImageData generator for data augmentation

# Network Architecture Used

Used MobileNetV2 for creating its base model

Used Fully connected layer for head of the model that will be placed on top of the  base model

Checkout my repository for base model --> BaseModel_Summary.txt

# Training Loss and Accuracy

![alt text](https://github.com/maurya0456/Face_Mask_Detection/blob/master/plot.png)

# Model Accuracy

Training Accuracy: 0.9937

Validation Accuracy: 0.9909

