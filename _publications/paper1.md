---
title: "Sentinel-1 SAR Backscatter Analysis Ready Data Preparation in Google Earth Engine"
collection: publications
permalink: /publication/paper1
excerpt: ''
date: 2021-05-15
venue: 'Remote Sensing'
paperurl: 'http://adugnag.github.io/files/S1_ARD_remotesensing-13-01954.pdf'
link: 'https://doi.org/10.3390/rs13101954'
citation: 'A. Mullissa, A. Vollrath, C. Odongo-Braun, B. Slagter, J. Balling,Y. Gou, N. Gorelick, J. Reiche, Sentinel-1 sar backscatter analysis ready data preparation in google earth engine, Remote Sensing 13 (10) (2021) 1954, doi:10.3390/rs13101954'
---
[[Paper]](https://doi.org/10.3390/rs13101954) [[Code]](https://github.com/adugnag/gee_s1_ard)

##Abstract

Sentinel-1 satellites provide temporally dense and high spatial resolution synthetic aperture
radar (SAR) imagery. The open data policy and global coverage of Sentinel-1 make it a valuable
data source for a wide range of SAR-based applications. In this regard, the Google Earth Engine
is a key platform for large area analysis with preprocessed Sentinel-1 backscatter images available
within a few days after acquisition. To preserve the information content and user freedom, some
preprocessing steps (e.g., speckle filtering) are not applied on the ingested Sentinel-1 imagery as
they can vary by application. In this technical note, we present a framework for preparing Sentinel-1
SAR backscatter Analysis-Ready-Data in the Google Earth Engine that combines existing and new
Google Earth Engine implementations for additional border noise correction, speckle filtering and
radiometric terrain normalization. The proposed framework can be used to generate Sentinel-1
Analysis-Ready-Data suitable for a wide range of land and inland water applications. The Analysis
Ready Data preparation framework is implemented in the Google Earth Engine JavaScript and
Python APIs.
