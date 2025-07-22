# Accurate_VQA
This repository contains the official code implementation for the paper **Structured Scene Graph Augmentation for Large Language Model in
Complex Visual Reasoning**

<img width="1803" height="814" alt="image" src="https://github.com/user-attachments/assets/153bcc81-597e-4d99-9389-24b42a9e5846" />




## Install
### Requirements
Our work SGG reference this [code](https://github.com/Maelic/SGG-Benchmark/tree/main),so most of the requirements of this projects are similar to it.You also conference it.

python>=3.8  
pytorch==2.2.1(CUDA 12.1)  
torchvision >= 0.4  
transforms 

## Dataset
For the VG150 dataset, you can refer to the link to the SGG code repository above to download it
For the AUG dataset,you can refer to the [link](https://gitee.com/xiaoyibang/lpg-sgg) download it

Due to the need to convert Raw data into the format required by the [above framework](https://github.com/Maelic/SGG-Benchmark/tree/main) for scene graph generation, [this folder](https://github.com/Quan-zzx/Accurate_VQA/tree/main/AUG_deal_data) provides the processed files of the AUG dataset

## Weight
For the weights of SGG on the AUG dataset, you can download [it here by BaiduNetDisk](https://pan.baidu.com/s/1DZYS1eozHA-SK-Fv-yCFpQ?pwd=0000) or [Google NetDist](https://drive.google.com/file/d/1JDxMu9LPM0VIAHYxRjVGCFvh2W71xcn9/view?usp=sharing)


## experience
This folder contains the experiments in our paper.You can view [the introduction of each file here](https://github.com/Quan-zzx/Accurate_VQA/blob/main/experiment/readme.md)  
The following are the experimental results comparing our method with different multimodal large models  
<img width="601" height="480" alt="image" src="https://github.com/user-attachments/assets/f3d3a453-c30b-4d33-9d08-59c25a053f26" />

<img width="600" height="472" alt="image" src="https://github.com/user-attachments/assets/f48405f8-ee7d-4cb3-843e-4bb0c2a7675b" />

