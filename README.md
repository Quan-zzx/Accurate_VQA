# Accurate_VQA
This repository contains the official code implementation for the paper **Enhanced Multimodal RAG-LLM for Accurate Visual Question Answering**



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

## Weight
For the weights of SGG on the AUG dataset, you can download [it](https://pan.baidu.com/s/1DZYS1eozHA-SK-Fv-yCFpQ?pwd=0000) here

## Demo
[demo.ipynb](https://github.com/Quan-zzx/Accurate_VQA/blob/main/demo.ipynb) Provided a demo to run the Accuracy VQA in our paper.  
You may need to modify the **get_respose()** in it, replacing it with the LLM you want to use and your own API key, or using a locally built LLM.

## experience
This folder contains the experiments in our paper.

