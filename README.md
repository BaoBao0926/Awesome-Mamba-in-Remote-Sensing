# Vision Mamba in Remote Sensing: A Comprehensive Survey of Techniques, Applications and Outlook


### News:
- 2025.04.05: The repository was created



## Contents
- [Mamba](#mamba)
- [Related Survey](#related-survey)
- [Vision Mamba Backbone](#vision-mamba-backbone)
- [Vision Mamba in Remote Sensing](#vision-mamba-in-remote-sensing)
  - [Classification](#classification)
  - [Segmentation](#segmentation)
    - [Vanilla Segmentation](#semantic-segmentation)
    - [Interactive Segmentation](#interactive-segmentation)
    - [Boundary Segmentation](#boundary-segmentation)
  - [Detection](detection)
    - [Object Detection](#object-detection)
    - [Target Detection](#target-detection)
    - [Object Tracking](#object-tracking)
    - [Object Counting](#object-counting)
  - [Change Detection](#change-detection)
    - [Change Detection](#change-detection)
    - [Change Detection Captioning](change-detection-captioning)
  - [Super-Resolution](#super-resolution)
    - [Super-Resolution](#super-resolution)
    - [Pan-Sharpening](#pan-sharpening)
    - [Down-Scaling](#down-scaling)
  - [Image Restoration](#image-restoration)
    - [Cloud Removal](#cloud-removal)
    - [Shadow Removal](#shadow-removal)
    - [Dehazing](#dehazing)
    - [Denoising](#denoising)
    - [Rain Removal](#rain-removal)
    - [HSI Reconstruction](#hsi-reconstruction)
  - [Spectral Translation](#spectral-translation)

## Mamba


## Related Survey

## Vision Mamba Backbone

# Vision Mamba in Remote Sensing
We document these papers according to different downstream tasks. All dates are the received date.


## Classification
| Venue(received, accepted)| Paper | Figure    | Link | Code         |
| :--------  | :---- | :-------- | :--- | :----------- |
|LGRS(24.03.28, 24.05.27)|RSMamba:Remote Sensing Image Classification With State Space Model |<img width="1600" alt="image" src="Assets/9.png">|[Link](https://ieeexplore.ieee.org/abstract/document/10542538)|[Code](https://github.com/KyanChen/RSMamba)|
|arXiv(24.04.12, -)|HSIMamba:Hyperpsectral Imaging Efficient Feature Learning with Bidirectional State Space for Classification |<img width="1600" alt="image" src="Assets/93.jpg">|[Link](https://arxiv.org/abs/2404.00272)|[Code](https://github.com/Judyxyang/HSImamba)|
|arXiv(24.04.12, -)|SpectralMamba:Efficient Mamba for Hyperspectral Image Classification |<img width="684" alt="image" src="Assets/33.jpg">|[Link](https://arxiv.org/abs/2404.08489)||
|TGRS(24.04.24, 24.07.10)|MambaHSI:Spatial–Spectral Mamba for Hyperspectral Image Classification |<img width="684" alt="image" src="Assets/101.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10604894)|[Code](https://github.com/li-yapeng/MambaHSI)|
|TGRS(24.04.28, 25.01.17)|S2Mamba:A Spatial-spectral State Space Model for Hyperspectral Image Classification |<img width="684" alt="image" src="Assets/64.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10844849)|[Code](https://github.com/PURE-melo/S2Mamba)|
|arXiv(24.04.29, -)|Spectral-Spatial Mamba for Hyperspectral Image Classification |<img width="684" alt="image" src="Assets/49.jpg">|[Link](https://arxiv.org/abs/2404.18401)|[Code](https://github.com/mengduanjinghua/Spectral-spatial-Mamba-for-HSIC)|
|TGRS(24.05.11, 24.10.23)|GraphMamba:An Efficient Graph Structure Learning Vision Mamba for Hyperspectral Image Classification |<img width="684" alt="image" src="Assets/63.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10746459)|[Code](https://github.com/ahappyyang/GraphMamba)|
|TGRS(24.05.14, 24.10.14)|HyperMamba:A Spectral–Spatial Adaptive Mamba for Hyperspectral Image Classification |<img width="684" alt="image" src="Assets/31.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10720896)|[Code](https://github.com/chiangliu/HyperMamba)|
|JSTARS(24.05.17, 24.09.30)|Rethinking Scanning Strategies with Vision Mamba in Semantic Segmentation of Remote Sensing Imagery:An Experimental Study |<img width="684" alt="image" src="Assets/10.png">|[Link](https://ieeexplore.ieee.org/abstract/document/10703181)||
|Signal Processing(24.05.18, 24.08.18)|State space models meet transformers for hyperspectral image classification |<img width="684" alt="image" src="Assets/76.jpg">|[Link](https://www.sciencedirect.com/science/article/pii/S0165168424002895?casa_token=VVB7b0RZUQcAAAAA:wtKXPTCkwUdcMeRFnzeUBqbnjjxSftmUmYEFdWRqjFYoEn7wESjqT6m0tOrAkSf3j4cfGwO_wZc)|[Code](https://github.com/PPPPPsanG/MamTrans)|
|()||<img width="684" alt="image" src="Assets/">|[Link]()|[Code]()|
|()||<img width="684" alt="image" src="Assets/">|[Link]()|[Code]()|
|()||<img width="684" alt="image" src="Assets/">|[Link]()|[Code]()|
|()||<img width="684" alt="image" src="Assets/">|[Link]()|[Code]()|



## Segmentation

### Semantic Segmentation

### Interactive Segmentation

### Boundary Segmentation





## Detection

### Object Detection

### Target Detection

### Object Tracking

### Object Counting



## Change Detection

### Change Detection 
| Venue(received, accepted)| Paper | Figure    | Link | Code         |
| :--------  | :---- | :-------- | :--- | :----------- |
|TGRS(24.04.10, 24.07.05)  |RS-Mamba for Large Remote Sensing Image Dense Prediction|<img width="684" alt="image" src="Assets/1.png">|[Link](https://ieeexplore.ieee.org/abstract/document/10589665)|[Code](https://github.com/walking-shadow/Official_Remote_Sensing_Mamba)|
|TGRS(24.04.15, 24.06.17)  |ChangeMamba:Remote Sensing Change Detection with Spatio-Temporal State Space Model |<img width="684" alt="image" src="Assets/14.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10565926)|[Code](https://github.com/ChenHongruixuan/MambaCD)|
|TGRS(24.04.25, 24.10.15)  |ConMamba:CNN and SSM High-Performance Hybrid Network for Remote Sensing Change Detection |<img width="684" alt="image" src="Assets/65.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10750064)||
|arXiv(24.06.06, -)        |CDMamba:Remote Sensing Image Change Detection with Mamba |<img width="684" alt="image" src="Assets/6.png">|[Link](https://arxiv.org/abs/2406.04207)|[Code](https://github.com/zmoka-zht/CDMamba)|
|RS(24.08.15, 24.09.27)    |Iterative Mamba Diffusion Change-Detection Model for Remote Sensing|<img width="684" alt="image" src="Assets/8.jpg">|[Link](https://www.mdpi.com/2072-4292/16/19/3651)|[Code](https://github.com/LiuFxxx/IMDCD)|
|RS(24.09.12, 24.11.08)    |DC-Mamba:A Novel Network for Enhanced Remote Sensing Change Detection in Difficult Cases |<img width="684" alt="image" src="Assets/16.jpg">|[Link](https://www.mdpi.com/2072-4292/16/22/4186)||
|RS(24.10.19, 24.10.30)    |TTMGNet:Tree Topology Mamba-Guided Network Collaborative Hierarchical Incremental Aggregation for Change Detection |<img width="684" alt="image" src="Assets/68.jpg">|[Link](https://www.mdpi.com/2072-4292/16/21/4068)|[Code](https://github.com/COMPHZ/TTMGNet)|
|TGRS(24.10.21, 24.11.12)  |A Novel Remote Sensing Image Change Detection Approach Based on Multilevel State Space Model |<img width="684" alt="image" src="Assets/41.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10756674)|[Code](https://github.com/121zzy/MF-Mamba.git)|
|RS(24.10.27, 24.12.09)    |An Unsupervised Remote Sensing Image Change Detection Method Based on RVMamba and Posterior Probability Space Change Vector |<img width="684" alt="image" src="Assets/72.jpg">|[Link](https://www.mdpi.com/2072-4292/16/24/4656)||
|JSTARS(24.11.26, 25.01.14)|LCCDMamba:Visual State Space Model for Land Cover Change Detection of VHR Remote Sensing Images |<img width="684" alt="image" src="Assets/102.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10845192)|[Code](https://github.com/juncyan/lccdmamba)|
|arXiv(25.01.26, -)        |CD-Lamba:Boosting Remote Sensing Change Detection via a Cross-Temporal Locally Adaptive State Space Model |<img width="684" alt="image" src="Assets/110.jpg">|[Link](https://arxiv.org/abs/2501.15455)|[Code](https://github.com/xwmaxwma/rschange)|


### Change Detection Captioning
| Venue(received, accepted)| Paper | Figure    | Link | Code         |
| :--------  | :---- | :-------- | :--- | :----------- |
|LGRS(24.05.02, 24.05.20)|RSCaMa:Remote Sensing Image Change Captioning With State Space Model |<img width="684" alt="image" src="Assets/48.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10537177)|[Code](https://github.com/Chen-Yang-Liu/RSCaMa)|



## Super-Resolution

### Super-Resolution
| Venue(received, accepted)| Paper | Figure    | Link | Code         |
| :--------  | :---- | :-------- | :--- | :----------- |
|TMM(24.05.01, 24.08.28)|Frequency-Assisted Mamba for Remote Sensing Image Super-Resolution|<img width="684" alt="image" src="Assets/4.png">|[Link](https://ieeexplore.ieee.org/abstract/document/10817590)|[Code](https://github.com/XY-boy/FreMamba)|
|JSTARS(24.06.11, 24.09.23)|Spatial–Spectral Interaction Super-Resolution CNN–Mamba Network for Fusion of Satellite Hyperspectral and Multispectral Image |<img width="684" alt="image" src="Assets/52.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10695805)||
|RS(24.07.22, 24.08.27)|ConvMambaSR:Leveraging State-Space Models and CNNs in a Dual-Branch Architecture for Remote Sensing Imagery Super-Resolution |<img width="684" alt="image" src="Assets/53.jpg">|[Link](https://www.mdpi.com/2072-4292/16/17/3254)||
|LGRS(24.08.07, 24.08.28)|MambaFormerSR:A Lightweight Model for Remote-Sensing Image Super-Resolution |<img width="684" alt="image" src="Assets/34.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10663411)||
|IJRS(24.08.16, 24.12.06)|UVMSR:a novel approach to hyperspectral image super-resolution by fusing U-Net and Mamba |<img width="684" alt="image" src="Assets/44.jpg">|[Link](https://www.tandfonline.com/doi/full/10.1080/01431161.2024.2443619?casa_token=JHK8qMLi11UAAAAA%3AODHxgFVYckTIQCOTqg6wRfL3_ixHH1ocGOrRU_9Y0Pv7YyBGJRW2KfMwyIsEbXSllfZ7zploxoAc69o)|[Code](https://github.com/TeresaTing/UVMSR)|
|CVPR(24.12.28, 25.03.22)|MaIR:A Locality-and Continuity-Preserving Mamba for Image Restoration |<img width="684" alt="image" src="Assets/90.jpg">|[Link](https://arxiv.org/abs/2412.20066)|[Code](https://github.com/XLearning-SCU/2025-CVPR-MaIR)|
|PRAI(25.01.14, 25.01.14)|Mamba-Based Residual Network for Remote Sensing Image Super-Resolution |<img width="684" alt="image" src="Assets/30.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10826984)||
|arXiv(25.01.30, -)|HSRMamba:Contextual Spatial-Spectral State Space Model for Single Hyperspectral Super-Resolution |<img width="684" alt="image" src="Assets/111.jpg">|[Link](https://arxiv.org/abs/2501.18500)||

### Pan-Sharpening
| Venue(received, accepted)| Paper | Figure    | Link | Code         |
| :--------  | :---- | :-------- | :--- | :----------- |
|Information Fusion(24.07.13, 24.10.29)|Pan-Mamba:Effective pan-sharpening with state space model |<img width="684" alt="image" src="Assets/57.jpg">|[Link](https://www.sciencedirect.com/science/article/pii/S1566253524005578?casa_token=T-IXNVum8_IAAAAA:ElLzx-L4UQj-3JX6TD9GybybHNRGe15wgXvhQlG-9ejAfg5YNLYmj-s7z9h6F-MpGm9wj-CtEUE)|[Code](https://github.com/alexhe101/Pan-Mamba)|
|TGRS(24.07.25, 24.10.30)|FusionMamba:Efficient Remote Sensing Image Fusion With State Space Model |<img width="684" alt="image" src="Assets/28.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10750233)|[Code](https://github.com/PSRben/FusionMamba)|
|TGRS(24.08.17, 24.11.18)|Supervised Detail-guided Multi-scale State Space Model for Pan-sharpening |<img width="684" alt="image" src="Assets/91.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10812822)|[Code](https://github.com/zhaomengjiao123/SDMSPan)|
|symmetry(24.11.13, 24.12.13)|Conditional Skipping Mamba Network for Pan-Sharpening |<img width="684" alt="image" src="Assets/78.jpg">|[Link](https://www.mdpi.com/2073-8994/16/12/1681)||

### Down-Scaling
| Venue(received, accepted)| Paper | Figure    | Link | Code         |
| :--------  | :---- | :-------- | :--- | :----------- |
|TGRS(24.08.25, 24.11.07)|MambaDS:Near-Surface Meteorological Field Downscaling With Topography Constrained Selective State-Space Modeling |<img width="684" alt="image" src="Assets/92.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10752514)||


## Image Restoration

### Cloud Removal
| Venue(received, accepted)| Paper | Figure    | Link | Code         |
| :--------  | :---- | :-------- | :--- | :----------- |
|arXiv(24.05.16, -)|RSDehamba:Lightweight Vision Mamba for Remote Sensing Satellite Image Dehazing |<img width="684" alt="image" src="Assets/7.png">|[Link](https://arxiv.org/abs/2405.10030)||
|TGRS(24.08.07, 25.01.02)|FMambaIR:A Hybrid State Space Model and Frequency Domain for Image Restoration |<img width="684" alt="image" src="Assets/80.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10834441)|[Code](https://github.com/mickoluan/FMambaIR)|
|SIVP(24.09.19, 24.12.07)|Lightweight vision Mamba for weather-degraded remote sensing image restoration |<img width="684" alt="image" src="Assets/24.jpg">|[Link](https://link.springer.com/article/10.1007/s11760-024-03767-0)||
|TGRS(24.09.22, 24.12.13)|Mamba-CR:A State-Space Model for Remote Sensing Image Cloud Removal |<img width="684" alt="image" src="Assets/19.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10806801)||
|RS(25.01.06, 25.01.27)|Weamba:Weather-Degraded Remote Sensing Image Restoration with Multi-Router State Space Model |<img width="684" alt="image" src="Assets/106.jpg">|[Link](https://www.mdpi.com/2072-4292/17/3/458)||

### Shadow Removal
| Venue(received, accepted)| Paper | Figure    | Link | Code         |
| :--------  | :---- | :-------- | :--- | :----------- |
|TGRS(24.08.15, 25.01.05)|RSMamba: Biologically Plausible Retinex-Based Mamba for Remote Sensing Shadow Removal|<img width="684" alt="image" src="Assets/17.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10833852)||

### Dehazing
| Venue(received, accepted)| Paper | Figure    | Link | Code         |
| :--------  | :---- | :-------- | :--- | :----------- |
|arxiv(24.06.09, -)|HDMba:Hyperspectral Remote Sensing Imagery Dehazing with State Space Model |<img width="684" alt="image" src="Assets/82.jpg">|[Link](https://arxiv.org/abs/2406.05700)|[Code](https://github.com/RsAI-lab/HDMba)|
|Mathematical Problems of Computer Science(-, 24,12,01)|Mamba-based Thermal Image Dehazing |<img width="684" alt="image" src="Assets/83.jpg">|[Link](http://93.187.165.2/index.php/mpcs/article/view/866)||
|RS(25.01.06, 25.01.27)|Weamba:Weather-Degraded Remote Sensing Image Restoration with Multi-Router State Space Model |<img width="684" alt="image" src="Assets/106.jpg">|[Link](https://www.mdpi.com/2072-4292/17/3/458)||

### Denoising
| Venue(received, accepted)| Paper | Figure    | Link | Code         |
| :--------  | :---- | :-------- | :--- | :----------- |
|arXiv(24.04.15, -)|HSIDMamba:Exploring Bidirectional State-Space Models for Hyperspectral Denoising |<img width="684" alt="image" src="Assets/58.jpg">|[Link](https://arxiv.org/abs/2404.09697)||
|TGRS(24.06.09, 24.08.15)|SSUMamba:Spatial–Spectral Selective State Space Model for Hyperspectral Image Denoising |<img width="684" alt="image" src="Assets/79.jpg">|[Link](https://ieeexplore.ieee.org/abstract/document/10643108)|[Code](https://github.com/lronkitty/SSUMamba)|

### Rain Removal
| Venue(received, accepted)| Paper | Figure    | Link | Code         |
| :--------  | :---- | :-------- | :--- | :----------- |
|arXiv(24.08.31, -)|A Hybrid Transformer-Mamba Network for Single Image Deraining |<img width="684" alt="image" src="Assets/70.jpg">|[Link](https://arxiv.org/abs/2409.00410)|[Code](https://github.com/sunshangquan/TransMamba)|
|RS(25.01.06, 25.01.27)|Weamba:Weather-Degraded Remote Sensing Image Restoration with Multi-Router State Space Model |<img width="684" alt="image" src="Assets/106.jpg">|[Link](https://dl.acm.org/doi/abs/10.1145/3664647.3680648?casa_token=6gjQ10LnqlIAAAAA:qJYQwQcP8heuc3I_iqWs0wFMYtUos-PFmCxqgrsPT5wB5EX-9HNlKoa5SgtIYXhsEDvGNxm0uN50)||


### HSI Reconstruction
| Venue(received, accepted)| Paper | Figure    | Link | Code         |
| :--------  | :---- | :-------- | :--- | :----------- |
|arXiv(24.08.31, -)|Dual Hyperspectral Mamba for Efficient Spectral Compressive Imaging |<img width="684" alt="image" src="Assets/66.jpg">|[Link](https://arxiv.org/abs/2406.00449)|[Code](https://github.com/JiahuaDong/DHM)|
|International Multimedia Conference(-, 24.10.28)|VmambaSCI:Dynamic Deep Unfolding Network with Mamba for Compressive Spectral Imaging |<img width="684" alt="image" src="Assets/88.jpg">|[Link](https://dl.acm.org/doi/abs/10.1145/3664647.3680648?casa_token=6gjQ10LnqlIAAAAA:qJYQwQcP8heuc3I_iqWs0wFMYtUos-PFmCxqgrsPT5wB5EX-9HNlKoa5SgtIYXhsEDvGNxm0uN50)||


## Spectral Translation
| Venue(received, accepted)| Paper | Figure    | Link | Code         |
| :--------  | :---- | :-------- | :--- | :----------- |
|arXiv(24.08.15, -)|ColorMamba:Towards High-quality NIR-to-RGB Spectral Translation with Mamba |<img width="684" alt="image" src="Assets/81.jpg">|[Link](https://arxiv.org/abs/2408.08087)|[Code](https://github.com/AlexYangxx/ColorMamba)|











