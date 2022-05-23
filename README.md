# A Deep Learning Framework to Reconstruct Face under Mask
This github repo has just one module(Gender Classification)'s code of our research paper. We will update soon with the other modules code.


The link of the paper: https://arxiv.org/abs/2203.12482



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


Citation
------------------------------------------
If you use our work in your research, please cite our paper. 

```
@INPROCEEDINGS{9736350,  author={Modak, Gourango and Das, Shuvra Smaran and Islam Miraj, Md. Ajharul and Morol, Md. Kishor},  
booktitle={2022 7th International Conference on Data Science and Machine Learning Applications (CDMA)},   
title={A Deep Learning Framework to Reconstruct Face under Mask},   
year={2022},  volume={},  number={},  pages={200-205},  
doi={10.1109/CDMA54072.2022.00038}}
```
