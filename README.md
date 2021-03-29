# Line Graph Neural Networks for Link Prediction



## Introduction

Pytorch implementation of [Line Graph Neural Networks for Link Prediction](https://arxiv.org/pdf/2010.10046.pdf).

![model](./LGLP/Python/pipeline.png)

If using this code , please cite our paper.

```
@article{cai2020line,
  title={Line graph neural networks for link prediction},
  author={Cai, Lei and Li, Jundong and Wang, Jie and Ji, Shuiwang},
  journal={arXiv preprint arXiv:2010.10046},
  year={2020}
}
```

## System requirement

#### Programming language
Python 3.5 +

#### Python Packages
Pytorch , Numpy , Networkx, PyTorch Geometric

#### Datasets

Raw datasets are obtained from https://noesis.ikor.org/datasets/link-prediction. Datasets are processed and saved into mat file.

## Training 

#### Train the network

```
cd LGLP/Python
python Main.py --data-name=BUP --test-ratio=0.5
```


## Acknowlegdements

Part of code borrow from https://github.com/muhanzhang/SEAL and https://github.com/muhanzhang/DGCNN. Thanks for their excellent work!
