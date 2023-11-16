<div align="center">
<h1><a href="https://ieeexplore.ieee.org/document/9934924">LEVIR-CC Dataset</a></h1>
</div>
A Large Dataset for Remote Sensing Image Change Captioning

## Paper Source
[[paper](https://ieeexplore.ieee.org/document/9934924)] and [[code page](https://github.com/Chen-Yang-Liu/RSICC)]


## LEVIR-CC Dataset 
Download Source:
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

The LEVIR-CC dataset contains **10,077** pairs of bi-temporal remote sensing images and **50,385** sentences describing the differences between images.
![dataset_example](https://github.com/Chen-Yang-Liu/RSICC/blob/main/Example/num.png)
Some examples of our dataset are as follows:
![dataset_example](https://github.com/Chen-Yang-Liu/RSICC/blob/main/Example/dataset_example.png)
