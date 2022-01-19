# 3D-Reconstruction-of-Cellular-Images
The goal of the project is to use Machine Learning Models to deblur, enhance and estimate depth from images taken with a microfabricated custom image sensor. [1-3]

To train the models, a synthetic dataset, representative of images taken with the customized image sensor is generated which can be found in the “Dataset” folder.

The dataset consists of a total of 7 .mat files.
Each .mat file includes 2000 samples with the following subparts:
1.	2 (51x51 pixel) images
a.	The images are taken with sensor A on the top and sensor B underneath the target specimen. The sharper regions depicted in the image from sensor A appear blurry in the image taken with sensor B 
2.	Depth map
