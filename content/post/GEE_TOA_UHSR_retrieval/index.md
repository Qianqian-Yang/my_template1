---
title: Intra-urban PM2.5 estimation from top-of-atmosphere reflectance with machine learning: theories, methods, and applications
subtitle: 

# Summary for listings and search engines
summary: 

# Link this post with a project
projects: []

# Date published
date: "2021-12-14T00:00:00Z"

# Date updated
lastmod: "2021-12-14T00:00:00Z"

# Is this an unpublished draft?
draft: true

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://postimg.cc/Lhjn4pM0)'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin
- Qiangqiang Yuan
- Tongwen Li

#tags:
#- Academic
#- 开源

#categories:
#- Demo
#- 教程
---

## Highlights:

1. 90m PM2.5 concentration are retrieved for China using L8/S2 TOAR based on GEE
2. Theoretical problems (scale effect, band selection, cloud impact) are investigated
3. Semivariogram- and PFD-based mapping quality evaluation method was proposed
4. Four types retrieval models are compared with pros and cons of each type summarized
5. Mapping results of DNN (CV R2=0.93) were used for intra-urban pollution analysis

## Abstracts: 

Intra-urban pollution monitoring requires fine particulate (PM2.5) concentration mapping at ultrahigh-resolution (dozens to hundreds of meters). However, current PM2.5 concentration estimation, which is mainly based on aerosol optical depth (AOD) and meteorological data, usually had a low spatial resolution (kilometers) and severe spatial missing problem, cannot be applied to intra-urban pollution monitoring. To solve these problems, top-of-atmosphere reflectance (TOAR), which contains both the information about land and atmosphere and has high resolution and large spatial coverage, may be efficiently used for PM2.5 estimation. This study aims to systematically evaluate the feasibility of retrieving ultrahigh-resolution PM2.5 concentration at a large scale (national level) from TOAR. Firstly, we make a detailed discussion about several important but unsolved theoretic problems on TOAR-based PM2.5 retrieval, including the band selection, scale effect, cloud impact, and mapping quality evaluation. Secondly, four types and eight retrieval models are compared in terms of quantitative accuracy, mapping quality, model generalization, and model efficiency, with the pros and cons of each type summarized. Thirdly, based on the above conclusions, we built a TOAR-based PM2.5 retrieval model using a deep neural network (DNN) model which has a high cross-validation R2 of 0.93. Through combining Landsat 8 and Sentinel 2 images, a 90m and ~4-day resolution PM2.5 product was generated. The retrieved maps were used for analyzing the fine-scale interannual pollution change inner the city, the pollution variations during novel coronavirus disease 2019 (COVID-19), and the effect of environmental protection actions. Results showed that the ultrahigh resolution can bring new findings of intra-urban pollution change, which cannot be observed at previous coarse resolution. Lastly, some suggestions for future ultrahigh-resolution PM2.5 mapping research were given.

## Learn more about this work

- 💬 [Contact the **authors**](https://happy-poitras-e5a301.netlify.app/#contact) 

## 😀 Thanks for your reading! Have a nice day! 😀 
