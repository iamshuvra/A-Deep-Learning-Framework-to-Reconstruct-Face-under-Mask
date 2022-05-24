# A Deep Learning Framework to Reconstruct Face under Mask
This is the official repository for the research work [A Deep Learning Framework to Reconstruct Face under Mask](https://ieeexplore.ieee.org/document/9736350/)

The pdf version of the full paper: https://arxiv.org/abs/2203.12482



Dataset for this paper: [Google Drive](https://drive.google.com/drive/folders/1RAcxpuBsmj8muouTK3NxlhAdcYvYTPT5) || [Mendeley](https://data.mendeley.com/datasets/zvr4jwvcrc/2)

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

## Trained Models
Inpainting Model:

Mask Segmentation Model:

Gender Classification Model: [Google Drive](https://drive.google.com/file/d/1fF_CAdi_b2I-9p_jjRS9cXzg1UxWkEd9/view?usp=sharing)

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
