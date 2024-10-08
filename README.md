# Accurate_VQA
This repository contains the official code implementation for the paper **Enhanced Multimodal RAG-LLM for Accurate Visual Question Answering**


![](https://github.com/Quan-zzx/Accurate_VQA/blob/main/results/framework.png)



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
![](https://github.com/Quan-zzx/Accurate_VQA/blob/main/results/result1.png) ![](https://github.com/Quan-zzx/Accurate_VQA/blob/main/results/result2.png)  
![](https://github.com/Quan-zzx/Accurate_VQA/blob/main/results/result3.png) ![](https://github.com/Quan-zzx/Accurate_VQA/blob/main/results/result4.png)

