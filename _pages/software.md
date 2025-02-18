---
permalink: /software/
title: "Software"
gallery:
header:
---

My research interest is in SAR, PolSAR and InSAR image and signal processing for environmental monitoring. Therefore, I have developed several methods, workflows and architectures to perform extract, load, transform tasks in this domain. Here are some selected developments in the mentioned areas.

### Sentinel-1 SAR backscatter analysis ready data preparation in Google Earth Engine

I am the main developer and maintainer of the [gee_s1_ard](https://github.com/adugnag/gee_s1_ard) framework developed in GEE Javascript and Python API  used to process Sentinel-1 SAR ground range detected images to the analysis ready data level. The scripts perform additional border noise correction, mono-temporal and multi-temporal speckle filters and radiometric terrain flattening. 

![](/images/software/S1-ARD-framework.png)

### SAR image despeckling

I have developed deep learning based methods to despeckle single channel SAR image despeckling [deSpeckNet](https://github.com/adugnag/deSpeckNet-TF-GEE) in the real number domain 

![](/images/software/deSpeckNet.png)

and PolSAR image despeckling in the complex domain [CV-deSpeckNet](https://github.com/adugnag/CV-deSpeckNet).

![](/images/software/CV-despecknet.png)

### SAR and optical time-series classification

 I have also developed methods to fuse SAR and optical time-series data for the detection of forest disturbance. I used recurrent neural networks such as LSTM to implicitly learn the seasonality pattern of time-series signals in tropical dry forests.


### SAR images semantic segmentation

I have also developed methods to perform semantic segmentation for SAR image time-series data [SAR-FCN-DK3](https://github.com/adugnag/SAR-FCN-DK3). I used a fully convolutional network with dilated kernels for landcover classification.

![](/images/software/PolSARNet.png)
