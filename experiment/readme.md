This folder contains experimental code。  

Firstly, you need to prepare the AUG dataset and VG150 dataset. Secondly, regarding the large model GPT-4o used in them, Gemini-flash,Qwen-vl-max， You need to prepare your own API key and fill in your key in the program. To prepare specifically, please refer to the corresponding documentation  

test_genimi.ipynb test_gpt.ipynb test_qwen.ipynb test_our.ipynb    
Includes experiments on the AUG dataset test set on Gemini, GPT, Qwen,our  

VG_test_genimi.ipynb VG_test_gpt.ipynb VG_test_qwen.ipynb VG_test_our.ipynb     
Includes experiments on the VG150 dataset test set on Gemini, GPT,Qwen,our

get_ground_truth.ipynb   
Generate ground_truth for AUG dataset

VG_get_ground_truth.ipynb   
Generate ground_truth for VG150 dataset


compute_metric.ipynb  
Calculate evaluation indicators
