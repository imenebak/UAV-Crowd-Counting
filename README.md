# VisDrone_CC


This is the Soft CSRNET version repo for ECCV2020(Challenge-CrowdCounting), which delivered an optimization of the parameters of the deep CNN "CSRNET" which made the density estimation in real time.

![ezgif com-video-to-gif](https://user-images.githubusercontent.com/34316110/94086046-b434c100-fe01-11ea-9187-c588803778b7.gif)

## Datasets
CC visdrone Dataset: [web_site](http://aiskyeye.com/)

## Prerequisites
We used Google Colab as a perncipal environment to train and test our models.

## Ground Truth

Please follow the `DensityVisDrone.ipynb ` to generate the ground truth.
You may use `Visdrone2019_dotAnnotation.ipynb` to change the type of the annotation in Visdrone VID 2019 dataset or else.

## Training Process

Please follow the first part of `TrainVal.ipynb` to start training process.

## Validation

Follow the second part `TrainVal.ipynb` to try the validation. You can try to modify the notebook and see the output of each image.

## Test

Follow the `Test_model.ipynb` to test your model on 2020 ECCV CC. You can try to modify the notebook and see the output of each image.

## References

Code 

```
On this repos we based on the keras implementation of CSRNet by : https://github.com/Neerajj9/CSRNet-keras
We're finalyzing also the Pytorch implementation : https://github.com/imenebak/CSRNet-pytorch
```
SOFT-CSRNet paper

```
@INPROCEEDINGS{9378749,
  author={Bakour, Imene and Bouchali, Hadia Nesma and Allali, Sarah and Lacheheb, Hadjer},
  booktitle={2020 2nd International Workshop on Human-Centric Smart Environments for Health and Well-being (IHSH)}, 
  title={Soft-CSRNet: Real-time Dilated Convolutional Neural Networks for Crowd Counting with Drones}, 
  year={2021},
  volume={},
  number={},
  pages={28-33},
  doi={10.1109/IHSH51661.2021.9378749}}
  
  ```
CSRNet paper.

```
@inproceedings{li2018csrnet,
  title={CSRNet: Dilated convolutional neural networks for understanding the highly congested scenes},
  author={Li, Yuhong and Zhang, Xiaofan and Chen, Deming},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  pages={1091--1100},
  year={2018}
}
```
ECCV2020 Challenge DroneCrowd.

```
@article{zhu2018vision,

title={Vision meets drones: A challenge},
author={Zhu, Pengfei and Wen, Longyin and Bian, Xiao and Ling, Haibin and Hu, Qinghua},
journal={arXiv preprint arXiv:1804.07437},
year={2018} }

@article{zhu2020vision,
title={Vision Meets Drones: Past, Present and Future},
author={Zhu, Pengfei and Wen, Longyin and Du, Dawei and Bian, Xiao and Hu, Qinghua and Ling, Haibin},
journal={arXiv preprint arXiv:2001.06303},
year={2020} }
```
