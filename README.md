# NIH_XRay_Faster_RCNN

PyTorch implementation of Faster RCNN with a ResNet-50-FPN backbone on the NIH Chest X-Ray dataset.

The NIH Chest X-Ray dataset, available from [kaggle](https://www.kaggle.com/nih-chest-xrays/data), contains a
total of 12,120 1024 x 1024 chest x-ray images from 30,805 unique patients with varying diseases. Of the 12,120
total images, approximately 1000 images contain ground truth bounding boxes. The 1000 images were used to train the model
for object detection.

Due to limited capacity, the model was only trained for a small number of epochs. If the model is trained for a longer
amount of time, improved results should be available.

Citations:

Xiaosong Wang, Yifan Peng, Le Lu, Zhiyong Lu, MohammadhadiBagheri, Ronald M. Summers.ChestX-ray8: Hospital-scale 
Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases,
IEEE CVPR, pp. 3462-3471,2017

P. Rajpurkar et al. (Dec. 2017). ‘‘CheXNet: Radiologist-level pneumonia detection on chest X-rays with deep learning.’’ [Online]. Available:
https://arxiv.org/abs/1711.05225
