
# Garbage detection from cctv using deep learning (tensorflow)

# ABSTRACT OF OUR PROJECT :

Cities today are beginning their
transformation into ”smart cities”. Beside
smart traffic, lighting, and energy
management, smart waste is an integral part
of any smart city. Particular attention should
be given to the abandoned garbage both in
public city areas or in places outside of town,
such as countryside or suburban roads.
Beyond causing the degradation of the area,
abandoned garbage can cause pollution and
have a negative impact on the quality of life of
residents in these areas. Our work focuses on
developing a software that is able to detect
and report the presence of abandoned waste
through the analysis of video streams in realtime. An improved YOLOv3 network model is
adopted to perform garbage detection and
recognition. The network has been fine-tuned
on dataset collected for this purpose. The
results show that the proposed approach may
represent a major contribution for a more
efficient waste management in smart cities. 

 # DATA 
 The collection of the images of the dataset
has been made using Google Images
Download which is a command-line Python
software that allows you to search for
keywords and phrases on Google Images and
automatically download them. In our project
it was used to search and download many
images on garbage and also images that
depicted scenes without the presence of
garbage.
[Link of our dataset](https://drive.google.com/drive/folders/1LpAsJUTNUM8-fgqd4CVZbsJHdkZhgHxn)


#  TRAINING THE NETWORK
YOLOv3 is a Convolutional Neural Network,
composed of 106 layers. The first 53 layers
refer to the Darknet-53 network used as
Feature Extractor and it is pre-trained on
Imagenet, allowing Deep-Transfer Learning.
The successive 53 layers allow Object
Detection on three scales of size (small,
medium and large objects). Moreover, a
further important feature of YOLOv3 is the
use of the anchors box, predetermined
through the use of the k-means clustering
algorithm on the training set. This
improvement allows to obtain a faster and
more stable network training. In our
experiment, we train the last 53 layers of
YOLOv3 on our dataset. We called the neural
network proposed in this work YOLO
TrashNet 
[Link for downloading weights](https://drive.google.com/drive/folders/1LpAsJUTNUM8-fgqd4CVZbsJHdkZhgHxn)


# IMAGES  OF OUR PROJECT:
![2022-12-14 (2)](https://user-images.githubusercontent.com/86285670/208422366-bcfc42a5-8d9f-4333-a593-d121c6de4c59.png)

![2022-12-14](https://user-images.githubusercontent.com/86285670/208422423-a32587bb-722f-461d-994c-081a644d2bec.png)

![2022-12-14 (1)](https://user-images.githubusercontent.com/86285670/208422480-675bb101-105c-4469-b6cd-6cb629d1b78f.png)

[Our Research Paper](https://drive.google.com/file/d/18Ah6Kp6j9kJ6bdPnjQrLQcYU-rkXJy8e/view?usp=sharing)
 
