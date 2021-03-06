This repository contains the code used for the following paper:

Identification and Classification of Wildlife from Camera-Trap Images using Machine Learning and Computer Vision.

Author: Nawaz Sheikh

If you use this code in an academic article, please cite the following paper:
Sheikh, N., 2020. Identification And Classification Of Wildlife From Camera-Trap Images Using Machine Learning And Computer Vision - NORMA@NCI Library. [online] Trap.ncirl.ie. Available at: <http://trap.ncirl.ie/4283/>.

The link http://trap.ncirl.ie/4283/ contains the project report and the configuration manual. Both the report and configuration manual were written using Latex.


This repository has three independent parts:

1- The code used for Task I: Exploratory Data Analysis (phase 1 folder)

2- The code used for Task II,III, and IV: Applying InceptionV3, VGG-16 and MobileNet topologies to the dataset (phase 2 folder)

3- resize.py is used for resizing the input images for all the other parts.

You need to run six_classes_utils along with Exploratory Data Analysis. six_classes_utils is used in order to resize the images with the expected image format depending on the topology. 

The dataset can be found on the following link:
http://lila.science/datasets/missouricameratraps

1. Requirements

To use this code, you will need to install or use the following:

Python, Google Colab or Jupiter Notebook, Keras, Tensorflow, NumPy, ScikitPlot, Pygal, OpenCV

2. Running
Pre-trained models could be found at the following links:

Inception-V3 architecture:
https://drive.google.com/file/d/1-6Wl-8a0bzbZsK-sAtTkyheb5mRhGGhN/view?usp=sharing

MobileNet architecture:
https://drive.google.com/file/d/1--rczt1D6VELdRx5H5iVbyhsO1cquAkk/view?usp=sharing

VGG-16 architecture:
https://drive.google.com/file/d/1--XoZwQWKZ1swu3qoDsg9zUpkvTMdpuK/view?usp=sharing


3. Questions?
For questions/suggestions, feel free to email at nawaz.sheikh19@gmail.com or create a github issue.
