## Introduction
This repository aims to perform the captioning task for 1 image using `Transformer` architecture and `VGG16` pretrained model to conduct this task.

---
## Getting started
In this source code, i use self-attention mechanism to build my own `Transformer` and use `VGG16` to extract some informations of images before giving them to encoder component of `Transformer`
<p align="center">
    <img src="https://github.com/thanhhung0112/Image-captioning/assets/79474374/be9bffec-b4c4-4041-a5df-5059e2e1266c">
</p>

* Crawling dataset
<p align="center">
    <img src="https://github.com/thanhhung0112/Image-captioning/assets/79474374/e6b30140-f211-46c7-b413-95b1ddb22937">
</p>

I use the above website and `Selenium` library of `Python` to crawl images and titles of them [![Crawling dataset](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12djfcRyG6UxrpH6Bgt-JG5I_ZHhFKJsv)

Training model and performing inference here [![Training model](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12esN53sHOK5PXzvHCooNSwcfLQR-cS0T)

## Results
<p align="center">
  <img src="https://github.com/thanhhung0112/Image-captioning/assets/79474374/870e955c-1777-4d5b-b47e-45e148978942">
</p>
<p align="center">
  <img src="https://github.com/thanhhung0112/Image-captioning/assets/79474374/66733145-a51f-4011-9b73-ad3857189f83">
</p>
The achieved loss and accuracy in validation dataset are not good. However, in this case, the achieved caption is not bad.
