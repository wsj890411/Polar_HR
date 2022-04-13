# Polarization Guided Specular Reflection Separation

![MATLAB R2018b](https://img.shields.io/badge/MATLAB-R2018b-DodgerBlue.svg?style=plastic)
![License CC BY-NC](https://img.shields.io/badge/license-CC_BY--NC-DodgerBlue.svg?style=plastic)

 Our paper is accepted by **IEEE Transactions on Image Processing (TIP)**. 

<div align=center>  <img src="figures/optimization.png" alt="Teaser" width="1200" align="bottom" /> </div>

**Picture:**  *The pipeline of the proposed polarization guided model.*









<div align=center>  <img src="./figures/real_re.png" alt="MPI Results" width="1000" align="center" /> </div>

**Picture:**  *Experiment results in the real scenes.*



This repository contains the official MATLAB implementation of the following paper:

> **Polarization Guided Specular Reflection Separation**<br>
>  Sijia Wen, Yinqiang Zheng, Feng Lu <br> https://ieeexplore.ieee.org/document/9515579
> 
>**Abstract:**  Since specular reflection often exists in the real captured images and causes deviation between the recorded color and intrinsic color, specular reflection separation can bring advantages to multiple applications that require consistent object surface appearance. However, due to the color of an object is significantly influenced by the color of the illumination, the existing researches still suffer from the near-duplicate challenge, that is, the separation becomes unstable when the illumination color is close to the surface color. In this paper, we derive a polarization guided model to incorporate the polarization information into a designed iteration optimization separation strategy to separate the specular reflection. Based on the analysis of polarization, we propose a polarization guided model to generate a polarization chromaticity image, which is able to reveal the geometrical profile of the input image in complex scenarios, \eg, diversity of illumination. The polarization chromaticity image can accurately cluster the pixels with similar diffuse color. We further use the specular separation of all these clusters as an implicit prior to ensure that the diffuse component will not be mistakenly separated as the specular component. With the polarization guided model, we reformulate the specular reflection separation into a unified optimization function which can be solved by the ADMM strategy. The specular reflection will be detected and separated jointly by RGB and polarimetric information. Both qualitative and quantitative experimental results have shown that our method can faithfully separate the specular reflection, especially in some challenging scenarios.

## Resources

Material related to our paper is available via the following links:

- Paper:  https://ieeexplore.ieee.org/document/9515579
- Code: https://github.com/wsj890411/PolarHR_Model

## System requirements

* MATLAB 2018b

## Dataset

Download (BaiduPan): https://pan.baidu.com/s/1cSshmBUJpSDrlmHUqRN3KA  Code: reqn

## Citation

If you find this work or code is helpful in your research, please cite:

```latex
@article{wen2021polarization,
  title={Polarization guided specular reflection separation},
  author={Wen, Sijia and Zheng, Yinqiang and Lu, Feng},
  journal={IEEE Transactions on Image Processing},
  volume={30},
  pages={7280--7291},
  year={2021},
  publisher={IEEE}
}
```

