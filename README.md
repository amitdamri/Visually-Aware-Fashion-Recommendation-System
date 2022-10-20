# Visually-Aware-Fashion-Recommendation-System

<p align="center">
<img width=500 height=300 src="https://user-images.githubusercontent.com/49988048/196925513-ee458c40-9015-417d-9e0f-7ab12a4d6275.png">
</p>

This project is an implementation of the DVBPR part of following paper:
Wang-Cheng Kang, Chen Fang, Zhaowen Wang, Julian McAuley. *[Visually-Aware Fashion Recommendation and Design with Generative Image Models.](http://cseweb.ucsd.edu/~jmcauley/pdfs/icdm17.pdf)* In Proceedings of IEEE International Conference on Data Mining (ICDM'17)

We rewrite the code to work with tesorflow 2.5, and suggested an improvement based on ImageNet model and Convolutional AutoEncoder model. 

In the datasets.txt file you can find the three datasets we used. In order to use them, you just need download them to your local drive and change the data_path inside the notebooks.

The notebooks contain three files - one for the original paper model (DVBPR), one for ImageNet-Based model and one for CAE-Based model.
