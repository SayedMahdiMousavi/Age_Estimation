# Age Estimation
In this repository, a pre-trained resnet50 model has been used for age estimation and we have reached an loss of 4.5. In the next update, we will try to train a transformer model and check its results.

## Dataset
The dataset used in this project, which we trained the model with, is the UTKFace dataset.<br>
<a href="https://susanqq.github.io/UTKFace/">description dataset</a><br>
<a href="https://drive.google.com/drive/folders/0BxYys69jI14kU0I1YUQyY1ZDRUE">download dataset</a>


## Block diagram
The following figure is the block diagram of how our proposed model works:

![bd](https://github.com/SayedMahdiMousavi/Age_Estimation/assets/56066734/c0d20246-4431-4840-bc83-94bb6143ee94)

In this project, we have used Pytrorch framework and torchvison library. The names and versions of other libraries are written in the requirements.txt file.

<ul>
<li>python version: 3.10.12</li>
<ul>
