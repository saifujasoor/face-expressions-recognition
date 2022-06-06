# face-expressions-recognition

### Built With
![python-shield] ![open-cv]

###  face-expressions-recognition

Train a facial expression classification model with the fast.ai library, read facial expressions from your webcam or a video file, and finally, add in facial landmarking to track your eyes to determine awareness!

### What is Fast.ai ?
fastai is a deep learning library which provides practitioners with high-level components that can quickly and easily provide state-of-the-art results in standard deep learning domains, and provides researchers with low-level components that can be mixed and matched to build new approaches.

<br> 

### What is ResNet 34?
ResNet 34 is image classification model pre-trained on ImageNet dataset. This is PyTorch* implementation based on architecture described in paper “Deep Residual Learning for Image Recognition” in TorchVision package (see here) https://docs.openvino.ai/latest/omz_models_model_resnet_34_pytorch.html#:~:text=ResNet%2034%20is%20image%20classification,224%2C%20224%20in%20RGB%20order.

The model input is a blob that consists of a single image of 1, 3, 224, 224 in RGB order.
<br>

## Getting Started

- Download the Facial landmark points detection through Dlib's 68 Model by below link and place it in working directory.

https://www.kaggle.com/datasets/sergiovirahonda/shape-predictor-68-face-landmarksdat?resource=download

### Prerequisites
Make sure you have installed Fast.ai library,Dlib,Numpy, Scipy, IMutils, OpenCV, Pandas, Argparse and Python.

### Execution guide
1. Download the contents of the repository
2. Make sure the necessary prerequisites are installed on your system
3. Type the following commands to install the necessary libraries and modules:
```
pip3 install -r requirements.txt
```

5. To run the project type the following command inside the directory on your terminal

* For Real time detection:-
  ```
  python3 liveVideoFrameRead.py
  ```
  
  * For Detecting on Video:-
  ```
  python3 videoFrameRead.py --video-file "your video file name"
  ```
 
  
4. Click http://127.0.0.1:5000/ (Press CTRL+C to quit)

### Ref: 
* https://towardsdatascience.com/ 
* https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/






## Author

<table>
<tr>
<td>
     <img src="https://avatars.githubusercontent.com/u/76810003?s=400&u=3de867a69316245acd6e93279367fc2a37a6dd14&v=4" width="180"/>
     
     Saifullah Rahimi

<p align="center">
<a href = "https://github.com/saifujasoor"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/saifullahrahimi/"><img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/></a>
</p>
</td>
</tr> 
  </table>



<!-- Links -->

[python-shield]: https://img.shields.io/badge/-Python-blue?logo=python&logoColor=white&style=for-the-badge
[open-cv]: https://img.shields.io/badge/-OpenCV-red?logo=opencv&logoColor=white&style=for-the-badge
[flask]: https://img.shields.io/badge/-Flask-black?logo=flask&logoColor=white&style=for-the-badge
[html-shield]: https://img.shields.io/badge/-HTML-orange?logo=html5&logoColor=white&style=for-the-badge
[css-shield]: https://img.shields.io/badge/-CSS-2862E9?logo=css3&logoColor=white&style=for-the-badge
[linkedin-shield]: https://img.shields.io/badge/-linkedin-0078B6?logo=linkedin&logoColor=white&style=for-the-badge
[linkedin]:https://www.linkedin.com/in/saifullahrahimi/
