# TTSR_b2
An Improved Texture Transformer Network for Ref-based Image Super-Resolution.

## 1.Introduciton

This is a project to improve the TTSR method. We nonlinearly enhance the attention mechanism. The official PyTorch implementation of the paper [Learning Texture Transformer Network for Image Super-Resolution](https://arxiv.org/abs/2006.04139) is in [here](https://github.com/researchmm/TTSR).

## 2.Method



## 3.Preparation
(1). Download [CUFED train set](https://drive.google.com/drive/folders/1hGHy36XcmSZ1LtARWmGL5OK1IUdWJi3I) and [CUFED test set](https://drive.google.com/file/d/1Fa1mopExA9YGG1RxrCZZn7QFTYXLx6ph/view)
(2). Make dataset structure be:
- CUFED
    - train
        - input
        - ref
    - test
        - CUFED5

## 4.Train & Evaluation

```
python3 main.py
```
Please use numbers in annotation to choose the function you need.


