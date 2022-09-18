---
permalink: /software/
title: "Software"
gallery:
header:
---

As my research interest is in processing SAR, PolSAR and InSAR signal processing I have developed several scripts to these effect. For my development my preferred programming language is Python and for machine learning, my prefered framework is Tensorflow. Some selected developments are:

## Sentinel-1 SAR backscatter analysis ready data preparation in Google Earth Engine

I am the main developer and maintainer of the [gee_s1_ard](https://github.com/adugnag/gee_s1_ard) of Javascript and Python scripts that are used to process Sentinel-1 SAR ground range detected images to the analysis ready data level. The scripts perform additional border noise correction, mono-temporal and multi-temporal speckle filters and radiometric terrain correction. 

![](/images/software/S1-ARD-framework.png)

## SAR image despeckling

I have developed deep learning based methods to despeckle single channel SAR image despeckling [deSpeckNet](https://github.com/adugnag/deSpeckNet-TF-GEE) in the real number domain 

![](/images/software/deSpeckNet.png)

and PolSAR image despeckling in the complex domain [CV-deSpeckNet](https://github.com/adugnag/CV-deSpeckNet).

![](/images/software/CV-despecknet.png)

## SAR and optical time-series classification

I have also developed methods to fuse SAR and optical time-series data for the detection of forest disturbance [S1-S2-Transformer](https://github.com/adugnag/S1-S2_Transformer). I used a transformer architecture to implicitly learn the seasonality pattern of time-series signals in tropical dry forests.

![](/images/software/S1-S2-Transformer.png)
