<div align="center">
<h1><a href="https://ieeexplore.ieee.org/document/9934924">LEVIR-CC Dataset & LEVIR-MCI Dataset</a></h1>
</div>
Dataset for Remote Sensing Image Change Captioning and Change Detection

## Paper Source
- **LEVIR-CC: A Large Dataset for Remote Sensing Image Change Captioning.** [[Paper](https://ieeexplore.ieee.org/document/9934924)] [[code](https://github.com/Chen-Yang-Liu/RSICC)]
- **LEVIR-MCI: A Large Dataset for exploring multi-task learning for change detection and change captioning.** [[Paper](https://arxiv.org/abs/2403.19646)] [[code](https://github.com/Chen-Yang-Liu/Change-Agents)]


## LEVIR-CC Dataset 
Download Source:
- [[🤗 Huggingface](https://huggingface.co/datasets/lcybuaa/LEVIR-CC/tree/main)]
- [[Google Drive](https://drive.google.com/drive/folders/1cEv-BXISfWjw1RTzL39uBojH7atjLdCG?usp=sharing)]
- [[Baidu Pan](https://pan.baidu.com/s/1YrWcz090kdqOZ0lrbqXJJA) (code:nq9y)]

The path list in the downloaded folder is as follows:
```python
path to LEVIR_CC_dataset:
                ├─LevirCCcaptions.json
                ├─images
                  ├─train
                  │  ├─A
                  │  ├─B
                  ├─val
                  │  ├─A
                  │  ├─B
                  ├─test
                  │  ├─A
                  │  ├─B
```
where A contains images of pre-phase, B contains images of post-phase.
- **Dataset mean and variance:**
  
| Folder | R_mean  | G_mean| B_mean | R_var |   G_var   |   B_var  |
| :--: | :------------: | :--------: | :---------: | :------: | :------: | :------: |
| A | 0.44152 | 0.43863 | 0.37418 | 0.17623 | 0.16578 | 0.15337 |
| B | 0.33992 | 0.33383 | 0.28561 | 0.13035 | 0.12678 | 0.11959 |
| ALL | 0.39073 | 0.38623 | 0.32989 | 0.15329 | 0.14628 | 0.13648 |


- The LEVIR-CC dataset contains **10,077** pairs of bi-temporal remote sensing images and **50,385** sentences describing the differences between images:

  ![dataset_example](https://github.com/Chen-Yang-Liu/RSICC/blob/main/Example/num.png)

  ![image](https://github.com/user-attachments/assets/996d4838-4ab9-4d3d-ac09-7e82f0fe6b73)

- Some examples of our dataset are as follows:
![dataset_example](https://github.com/Chen-Yang-Liu/RSICC/blob/main/Example/dataset_example.png)



## LEVIR- MCI Dataset
- The dataset contains bi-temporal images as well as diverse change detection masks and descriptive sentences. It provides a crucial data foundation for exploring multi-task learning for change detection and change captioning.
- Download link (https://github.com/Chen-Yang-Liu/Change-Agent)

  ![image](https://github.com/user-attachments/assets/e515a860-2d00-4819-9a87-c666ac0584f9)

- Some examples of our dataset are as follows:
  ![dataset_example](https://github.com/Chen-Yang-Liu/Change-Agent/blob/main/resource/dataset.png)
