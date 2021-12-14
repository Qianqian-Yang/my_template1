---
title: "Mapping PM2.5 concentration at a sub-km level resolution: A dual-scale retrieval approach"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Qiangqiang Yuan
- Linwei Yue
- Tongwen Li
- Huanfeng Shen
- Liangpei Zhang
 
# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
#- "Equal contribution"

date: "2020-07-20T00:00:00Z"
doi: "https://doi.org/10.1016/j.isprsjprs.2020.05.018"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *ISPRS Journal of Photogrammetry and Remote Sensing*
publication_short: In *ISPRS Journal of Photogrammetry and Remote Sensing*

abstract: Satellite-based retrieval has become a popular PM2.5 monitoring method currently. To improve the retrieval performance, multiple variables are usually introduced as auxiliary variable in addition to aerosol optical depth (AOD). Different kinds of variables are usually at different resolutions varying from sub-kilometers to dozens of kilometers. Generally, when doing the retrieval, variables at different resolutions are resampled to the same resolution as the AOD product to keep the scale consistency. A deficiency of doing this is that the information contained in the scale difference is discarded. To fully utilize the information contained at different scales, a dual-scale retrieval method is proposed in this study. At the first stage, variables which influence PM2.5 concentration at large scale were used for PM2.5 retrieval at coarse resolution. Then at the second stage, variables which affect PM2.5 distribution in finer scale, were used for the further PM2.5 retrieval at high resolution (sub-km level resolution) with the retrieved PM2.5 at the first stage at coarser resolution also as input. In this study, four different retrieval models including multiple linear regression (MLR), geographically weighted regression (GWR), random forest (RF) and generalized regression neural network (GRNN) are adopted to test the performance of the dual-scale retrieval method. Compared with the traditional retrieval method, the proposed dual-scale retrieval method can achieve PM2.5 mapping at finer resolution and with higher accuracy. Dual-scale retrieval can fully utilize the information contained at different scales, thus achieving a higher resolution and accuracy. It can be used for the generation of quantitative remote sensing products in various fields, and promote the improvement of the quality of quantitative remote sensing products.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Article Link
  url: https://www.sciencedirect.com/science/article/pii/S0924271620301441

url_pdf: 'https://reader.elsevier.com/reader/sd/pii/S0924271620301441?token=07E4AEF493EEF723A4287ADDAC8D9E6D9BFED683BFFB741B953CDE76054D952521060C057C9CB99425DC1B55B2F978A0&originRegion=us-east-1&originCreation=20211214084044'
#url_code: ''
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
