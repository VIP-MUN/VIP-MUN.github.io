---
title: "CORONA-Net"
permalink: /CORONA_NET/
author_profile: true
#header:
#  image: "/images/arch.jpg"
author: 
---
# COnvolutional Re-initialization Optimization Network for Detecting  COVID-19 from CT and X-ray images



The COVID-19 pandemic has been deemed a global health emergency. The early detection  of COVID-19 is  key to combating its outbreak and could help  bring this pandemic to an end. One of the most challenging factors in applying deep learning to medical images is the lack of large benchmarks due to the privacy and  expensive annotation.  Carefully designing a deep network to leverage the available limited data can, in most scenarios, perform well. In this paper, we propose CORONA-Net, a carefully-designed-network to leverage the available limited COVID-19 dataset of chest X-rays images and CT scans. CORONA-Net is divided into two phases: 1) The re-initialization phase and 2) The classification phase. In the re-initialization phase, the network has a backbone/encoder network and a decoder network. The objective of this phase is to initialize the backbone/encoder network  by a  distribution that comes out of  medical images  instead of the pre-training that was done on natural images. In the classification phase, the decoder network is removed from CORONA-Net, and the backbone network is used in the classification/inference. Extensive experiments are performed on the publicly available dataset, COVIDx, and the results show that CORONA-Net significantly outperforms the current state-of-the-art networks.

[Source code](https://github.com/Abdelpakey/CORONA-Net)

[Pretraine network](https://drive.google.com/file/d/1m95g1Lg2vi6Q5mMuPh9GX_U2Odc3H0NE/view?usp=sharing)

## CORONA-Net Architecture
In  this section we show the architecture of DP-Siam. Data dimensions are shown in Table I.

  <img src="./images/coronanet.jpg">


## Results

The figure below shows the results of CORONA-Net on COVIDx dataset.

![Confusion matrix](./images/confusionlabel.png)

The table below shows the Positive Predictive  Value (PPV) for CORONA-Net compared to other methods.



![](./images/ppv.jpg)



If you interested in our work, please cite:





<script type="text/javascript" id="clstr_globe" src="//cdn.clustrmaps.com/globe.js?d=DK6NivqyBCLgdq4_G_cU28fGcqhaBSty4GAmbzVWqf4"></script>