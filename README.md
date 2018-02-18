# Vehicle-Detection-Net
## This project is aimed at implementing a vehicle detection platform for aerial images.
A Faster R-CNN is employed for the detection mechanism. Detailed description of F-RCNN can be found [here](https://arxiv.org/pdf/1506.01497.pdf). Detection of vehicles in aerial image has real life implications like military surveillance, trafiic management, parking lot monitoring etc.
The current model can be used for detecting other objects in images like people, cars,bus etc. This is enabled by pretrained weights, that are trained on huge image dataset. Along with detection our model enables both instantaneous count per frame and sequential count of objects in videos. Input to the model can be either video or images while testing. Training is done using annotated images. Annotation and dataset creation for training on your own data is discussed below.
## Data annotation and Training

