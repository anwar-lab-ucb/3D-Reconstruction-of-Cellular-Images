# 3D-Reconstruction-of-Cellular-Images
The goal of the project is to use Machine Learning Models to deblur, enhance and estimate depth from images taken with a microfabricated custom image sensor. [1-3]

To train the models, a synthetic dataset, representative of images taken with the customized image sensor is generated which can be found in the “Dataset” folder.

The dataset consists of a total of 7 .mat files.
Each .mat file includes 2000 samples with the following subparts:
1.	2 (51x51 pixel) images
a.	The images are taken with sensor A on the top and sensor B underneath the target specimen. The sharper regions depicted in the image from sensor A appear blurry in the image taken with sensor B 
2.	Depth map





References:
[1] 	Papageorgiou, E. P., Boser, B. E. & Anwar, M. Chip-Scale Angle-Selective Imager for In Vivo Microscopic Cancer Detection. IEEE Trans Biomed Circuits Syst 14, 91–103 (2020).

[2] 	Najafiaghdam, H. et al. A Molecular Imaging ’Skin A Time-resolving Intraoperative Imager for Microscopic Residual Cancer Detection Using Enhanced Upconverting Nanoparticles∗. Proceedings of the Annual International Conference of the IEEE Engineering in Medicine and Biology Society, EMBS 2018-July, 3005–3008 (2018).

[3]	Rabbani, R. et al. Towards an Implantable Fluorescence Image Sensor for Real-Time Monitoring of Immune Response in Cancer Therapy. in IEEE Int. Conf. in Engineering in Medicine & Biology Society (EMBC) (2021).
