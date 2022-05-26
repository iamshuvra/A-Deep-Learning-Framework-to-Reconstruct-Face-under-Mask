# A Deep Learning Framework to Reconstruct Face under Mask
This is the official repository for the research work [A Deep Learning Framework to Reconstruct Face under Mask](https://ieeexplore.ieee.org/document/9736350/). We are updating the available resources in this repo. Stay tuned with us. Thank you.




The pdf version of the full paper: https://arxiv.org/abs/2203.12482


# Datasets

Dataset of Mask Segementation and Inpainting: [Google Drive](https://drive.google.com/drive/folders/1RAcxpuBsmj8muouTK3NxlhAdcYvYTPT5) || [Mendeley](https://data.mendeley.com/datasets/zvr4jwvcrc/2)

Dataset for Gender Classification: [Gender Classified Dataset with Masked Face](https://www.kaggle.com/datasets/itsshuvra/gender-classified-dataset-with-masked-face)

# Experiments
We have used the Labelme software to create our dataset. You will find the mask segmentation dataset in the above link. Here is one example:

![Labelme](https://github.com/itsshuvra/A-Deep-Learning-Framework-to-Reconstruct-Face-under-Mask/blob/main/Results/Mask1.PNG)

We have perfectly detect the mask as an object. Here is the result you can see: 


![Object Detection](https://github.com/itsshuvra/A-Deep-Learning-Framework-to-Reconstruct-Face-under-Mask/blob/main/Results/mask4.png)
![Object Detection](https://github.com/itsshuvra/A-Deep-Learning-Framework-to-Reconstruct-Face-under-Mask/blob/main/Results/mask5.png)

There is no edges on the face because we have detect the region of the mask properly.


![No Edges](https://github.com/itsshuvra/A-Deep-Learning-Framework-to-Reconstruct-Face-under-Mask/blob/main/Results/Mask3.PNG)


Now, comparison with the ground truth of an image we know.

![Target Image](https://github.com/itsshuvra/A-Deep-Learning-Framework-to-Reconstruct-Face-under-Mask/blob/main/Results/Target1.PNG)

We have used [Adaptive WingLoss](https://github.com/protossw512/AdaptiveWingLoss) for Facial Landmark Calculation.

# Trained Models
## Inpainting Model
### FFHQ

For Male: [Generator](https://drive.google.com/file/d/1-6Qul73nxR68DgyM_7hjLqUXYyQ1pPQb/view?usp=sharing) || [Descriminator](https://drive.google.com/file/d/1-8hT8Xl8rnw8c9gjygxD32CaScnU1n5y/view?usp=sharing)

For Female: [Generator](https://drive.google.com/file/d/18FUMW5QP0_hz8H3EUuK2UoEV_eYIKUu0/view?usp=sharing) || [Descriminator](https://drive.google.com/file/d/18FWZqnB7tXCxfjlUFPXmKI2QN5NHaTng/view?usp=sharing)

### CelebA
For Male: [Generator](https://drive.google.com/file/d/10QSBLUmATJqvnH6_2tqH2NQx80KqiOVU/view?usp=sharing) || [Descriminator](https://drive.google.com/file/d/10cidzbeoXH0R7YknKqiDrTND5LZMR23Q/view?usp=sharing)

For Female: [Generator](https://drive.google.com/file/d/1-U5eWNpo7HXT_swSpZjzDdCRtGDh7Z4k/view?usp=sharing) || [Descriminator](https://drive.google.com/file/d/1-V7e-UHnaOs3MMoAVxkwCVYL6z7Xuivr/view?usp=sharing)

## Mask Segmentation Model:
We have used [Mask RCNN](https://github.com/matterport/Mask_RCNN) to train our dataset. Saved Model Link: [Google Drive](https://drive.google.com/file/d/1-5GGKKmwG96W5PzqwMwT5hTvipERn0M3/view?usp=sharing)

## Gender Classification Model: 
We have used [Inception V3](https://github.com/fchollet/deep-learning-models/blob/master/inception_v3.py) pretrained model and used keras tuner to tune the model for our problem. We trained with the dataset of 89k images separately male and female. 
Saved Model Link: [Google Drive](https://drive.google.com/file/d/1fF_CAdi_b2I-9p_jjRS9cXzg1UxWkEd9/view?usp=sharing)

Citation
------------------------------------------
If you find our work helpful for your research, please cite our paper. 

```
@INPROCEEDINGS{9736350,  author={Modak, Gourango and Das, Shuvra Smaran and Islam Miraj, Md. Ajharul and Morol, Md. Kishor},  
booktitle={2022 7th International Conference on Data Science and Machine Learning Applications (CDMA)},   
title={A Deep Learning Framework to Reconstruct Face under Mask},   
year={2022},  volume={},  number={},  pages={200-205},  
doi={10.1109/CDMA54072.2022.00038}}
```
