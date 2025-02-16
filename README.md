# Video-Action-Recognition

### 🔥🔥🔥[The Journey of Action Recognition](https://leiwangr.github.io/files/xi-ar.pdf)✈️

> 👋👋👋 A collection of methods and datasets in the journey of action recognition. 
>
> 📌 More details please refer to our [paper](https://leiwangr.github.io/files/xi-ar.pdf). 
>
> 🛠️ Please let us know if you find out a mistake or have any suggestions by e-mail: Xi.Ding1@anu.edu.au

### 📑 Citation

If you find our work useful for your research, please cite the following paper:

```bibtex
@inproceedings{dingjourney,
title={The Journey of Action Recognition},
author={Ding, Xi and Wang, Lei},
year={2025},
isbn={9798400713316},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url={https://doi.org/10.1145/3701716.3717746},
doi={10.1145/3701716.3717746},
booktitle = {Companion Proceedings of the ACM Web Conference 2025},
keywords = {Action recognition, Data, Model architectures, Learning paradigm},
location = {Sydney, NSW, Australia},
series = {WWW '25 Companion}
}
```
---

## 🚀 News
- \[10/02/2025\] 🎁 The GitHub repository for our paper has been released.
- \[27/01/2025\] 🎈 Our paper has been accepted as an oral presentation at the Companion Proceedings of The Web Conference 2025 (WWW 2025)

## 🔦 Table of Contents

- [Video-Action-Recognition](#video-action-recognition)
  - [🔥🔥🔥 The Journey of Action Recognition](#video-action-recognition)
  - [📑 Citation](#-citation)
  - [🚀 News](#-news)
  - [🧰 Methods Used in The Journey of Action Recognition](#-methods-used-in-the-journey-of-action-recognition)
    - [Handcrafted Methods](#handcrafted-methods)
    - [2D-based Methods](#2d-based-methods)
    - [3D-based Methods](#3d-based-methods)
    - [Two-stream Methods](#two-stream-methods)
    - [(2+1)D-based Methods](#21d-based-methods)
    - [Transformer-based Methods](#transformer-based-methods)
    - [Skeletons-based Methods](#skeletons-based-methods)
    - [Depth-based Methods](#depth-based-methods)
    - [Infrared-based Methods](#infrared-based-methods)
    - [Point Cloud Methods](#point-cloud-methods)
    - [Text/Audio Methods](#textaudio-methods)
  - [💻 Datasets Used in The Journey of Action Recognition](#-datasets-used-in-the-journey-of-action-recognition)
  - [❤️‍🔥❤️‍🔥❤️‍🔥 Contribution](#❤️‍🔥❤️‍🔥❤️‍🔥-contribution)


## 🧰 Methods Used in The Journey of Action Recognition 

### Handcrafted Methods

<details>
<summary>Click to expand Table 1</summary>

| Model          | Venue        | Learning        | Dataset                                                  | Modality                          | Code |
|----------------|--------------|-----------------|----------------------------------------------------------|-----------------------------------|------|
| [HL-STIP](https://link.springer.com/article/10.1007/s11263-005-1838-7) | IJCV 2005    | Supervised      | Outdoor scenes                                            | RGB                               | - |
| [Spatio-temporal Cuboids](https://ieeexplore.ieee.org/document/1570899) | VS-PETS 2005 | Supervised      | Human Action Dataset                                      | RGB                               | - |
| [3D-SURF](https://link.springer.com/chapter/10.1007/11744023_32) | ECCV 2006    | Supervised      | Mikolajczyk                                               | RGB                               | - |
| [3D-SIFT](https://dl.acm.org/doi/10.1145/1291233.1291311) | ACM MM 2007  | Supervised      | Weizmann                                                  | RGB                               | - |
| [NNMF Detector](https://ieeexplore.ieee.org/document/4408923) | ICCV 2007    | Supervised      | KTH                                                       | RGB                               | - |
| [HOG3D](https://inria.hal.science/inria-00514853/) | BMVC 2008    | Supervised      | KTH, Weizmann, Hollywood                                   | RGB                               | - |
| [Laptev et al.](https://ieeexplore.ieee.org/document/4587756) | CVPR 2008    | Supervised      | KTH                                                       | RGB + Optical flow                 | - |
| [Action MACH](https://ieeexplore.ieee.org/document/4587727) | CVPR 2008    | Supervised      | KTH, Weizmann                                             | RGB + Optical flow                 | - |
| [Extended SURF](https://link.springer.com/chapter/10.1007/978-3-540-88688-4_48) | ECCV 2008    | Supervised      | KTH, TRECVID 2006                                          | RGB                               | - |
| [LTP](https://ieeexplore.ieee.org/document/5459201) | ICCV 2009    | Supervised      | KTH, Hollywood, Kissing and slapping dataset, UCF Sports  | RGB                               | - |
| [Messing et al.](https://ieeexplore.ieee.org/document/5459154) | ICCV 2009    | Supervised      | KTH                                                       | RGB                               | - |
| [Bregonzio et al.](https://ieeexplore.ieee.org/abstract/document/5206779) | CVPR 2009    | Supervised      | KTH, Weizmann                                             | RGB                               | - |
| [Tracklet Descriptors](https://link.springer.com/chapter/10.1007/978-3-642-15549-9_42) | ECCV 2010    | Supervised      | KTH, ADL, Hollywood                                       | RGB + Optical flow                 | - |
| [Dense Long-Duration Trajectories](https://ieeexplore.ieee.org/document/5583046) | ICME 2010    | Supervised      | KTH                                                       | RGB + Optical flow                 | - |
| [Dense Trajectories](https://link.springer.com/article/10.1007/s11263-012-0594-8) | IJCV 2013    | Supervised      | KTH, YouTube, Hollywood2, UCF Sports, IXMAS, Olympic Sports, UCF50, UIUC, HMDB51 | RGB + Optical flow                 | - |
| [iDT](https://ieeexplore.ieee.org/document/6751553) | ICCV 2013    | Supervised      | Hollywood2, HMDB51, Olympic Sports, UCF50                | RGB + Optical flow                 | - |
| [Taylor videos](https://arxiv.org/abs/2402.03019) | ICML 2024    | Supervised      | HMDB51, CATER, MPII Cooking, Kinetics-400, -600, Something-Something V2, NTU RGB+D, Kinetics-skeleton | RGB + Skeleton                     | [GitHub](https://github.com/leiwangr/video-ar) |

</details>

### 2D-based Methods

<details>
<summary>Click to expand Table 2</summary>

| Model           | Venue        | Learning         | Dataset                                                            | Modality                                     | Code |
|-----------------|--------------|------------------|--------------------------------------------------------------------|---------------------------------------------|------|
| [Slow fusion](https://ieeexplore.ieee.org/document/6909619)  | CVPR 2014  | Supervised       | Sports-1M, UCF101                                                   | RGB                                         | [GitHub](https://github.com/lRomul/ball-action-spotting) |
| [CNN-LSTM](https://arxiv.org/abs/1503.08909)    | CVPR 2015  | Supervised       | Sports-1M, UCF101                                                   | RGB + Optical flow                          | [GitHub](https://github.com/shobrook/sequitur) |
| [LRCN](https://arxiv.org/abs/1411.4389)        | CVPR 2015  | Supervised       | UCF101                                                              | RGB + Optical flow                          | [GitHub](https://github.com/garythung/torch-lrcn) |
| [Composite LSTM](https://arxiv.org/abs/1502.04681) | ICML 2015  | Unsupervised     | UCF101, HMDB51                                                      | RGB                                         | [GitHub](https://github.com/mansimov/unsupervised-videos) |
| [Rank Pooling](https://arxiv.org/abs/1512.01848) | TPAMI 2016 | Supervised       | HMDB51, Hollywood2, MPII Cooking                                     | RGB + Optical flow                          | - |
| [LENN](https://ieeexplore.ieee.org/document/7780475)        | CVPR 2016  | Supervised       | UCF101                                                              | RGB                                         | - |
| [Bilen et al.](https://arxiv.org/abs/1612.00738) | TPAMI 2017 | Supervised       | UCF101, HMDB51                                                      | RGB                                         | - |
| [TSN](https://arxiv.org/abs/1705.02953)         | TPAMI 2018  | Supervised       | HMDB51, UCF101, Kinetics-400, ActivityNet, THUMOS14                | RGB + RGB differences + Optical flow + Audio | [GitHub](https://github.com/yjxiong/temporal-segment-networks) |
| [Attention-LSTM](https://arxiv.org/abs/1711.09550) | CVPR 2018 | Supervised       | UCF101, HMDB51, Kinetics-400                                         | RGB + Optical flow + Audio                  | [GitHub](https://github.com/longxiang92/Flash-MNIST) |
| [PEAR](https://ieeexplore.ieee.org/document/8784917) | ICME 2019 | Reinforcement    | UCF101, Sports-1M                                                   | RGB + Optical flow                          | - |
| [TSM](https://arxiv.org/abs/1811.08383)         | ICCV 2019  | Supervised       | Something-Something V1, V2, Kinetics-400, UCF101, HMDB51            | RGB                                         | [GitHub](https://github.com/MIT-HAN-LAB/temporal-shift-module) |
| [VINCE](https://arxiv.org/abs/2003.07990)       | arXiv 2020 | Self-supervised  | Kinetics-400                                                         | RGB                                         | [GitHub](https://github.com/danielgordon10/vince) |
| [C²LSTM](https://www.sciencedirect.com/science/article/abs/pii/S0925231219304436) | Neurocomputing 2020 | Supervised | UCF101, HMDB51                                                    | RGB                                         | - |
| [MoCo](https://arxiv.org/abs/2104.14558)        | CVPR 2021  | Self-supervised  | Kinetics-400, UCF101, HMDB51                                         | RGB                                         | [GitHub](https://github.com/facebookresearch/SlowFast) |
| [TCL](https://arxiv.org/abs/2102.02751)         | CVPR 2021  | Semi-supervised + Contrastive | Mini-Something-V2, Kinetics-400, Charades-Ego                     | RGB                                         | [GitHub](https://github.com/CVIR/TCL) |
| [TDN](https://arxiv.org/abs/2012.10071)         | CVPR 2021  | Supervised       | Something-Something V1, V2, Kinetics-400                            | RGB                                         | [GitHub](https://github.com/MCG-NJU/TDN) |
| [DB-LSTM](https://www.sciencedirect.com/science/article/pii/S0925231220317859?casa_token=nrmYvhCmLgYAAAAA:1wy1noAPo1Sn9JdT4F3xKLXCusonFMYP2zE58H8O8zD2BrH48YRauzj_bbZLkZ1abajR2muNdBBl)     | Neurocomputing 2021 | Supervised | UCF101, HMDB51                                                      | RGB + Optical flow                          | - |
| [SeCo](https://arxiv.org/abs/2008.00975)        | AAAI 2021  | Self-supervised  | Kinetics-400, UCF101, HMDB51, ActivityNet                           | RGB                                         | [GitHub](https://github.com/YihengZhang-CV/SeCo-Sequence-Contrastive-Learning) |
| [Xiao et al.](https://arxiv.org/abs/2111.13241)  | CVPR 2022  | Semi-supervised + Contrastive | Kinetics-400, UCF101, HMDB51                                         | RGB                                         | [GitHub](https://github.com/lambert-x/video-semisup) |
| [GCSM](https://dl.acm.org/doi/10.1145/3581783.3612380)        | ACM MM 2023 | Few-shot         | UCF101, HMDB51, Kinetics-400                                         | RGB                                         | - |
| [GgHM](https://arxiv.org/abs/2308.09346)        | ICCV 2023  | Few-shot         | HMDB51, UCF101, Kinetics-400, Something-Something V2                | RGB                                         | [GitHub](https://github.com/jiazheng-xing/gghm) |

</details>

### 3D-based Methods

<details>
<summary>Click to expand Table 3</summary>

| Model               | Venue        | Learning         | Dataset                                                                                                     | Modality                           | Code       |
|---------------------|--------------|------------------|-------------------------------------------------------------------------------------------------------------|------------------------------------|------------|
| [C3D](https://arxiv.org/abs/1412.0767)               | ICCV 2015    | Supervised      | UCF101                                                                                                     | RGB                                | [GitHub](https://github.com/facebookarchive/C3D) |
| [I3D](https://arxiv.org/abs/1705.07750)               | CVPR 2017    | Supervised      | Kinetics-400, UCF101, HMDB51                                                                              | RGB                                | [GitHub](https://github.com/open-mmlab/mmaction2) |
| [P3D](https://arxiv.org/abs/1711.10305)               | ICCV 2017    | Supervised      | Sports-1M, UCF101, ActivityNet                                                                            | RGB                                | [GitHub](https://github.com/ZhaofanQiu/pseudo-3d-residual-networks) |
| [ResNet3D](https://arxiv.org/abs/1711.09577)             | CVPR 2018    | Supervised      | Kinetics-400, UCF101, HMDB51, ActivityNet                                                                 | RGB                                | [GitHub](https://github.com/kenshohara/3D-ResNets-PyTorch) |
| [S3D](https://arxiv.org/abs/1712.04851)            | ECCV 2018    | Supervised      | Kinetics-400, Something-Something V1, UCF101, HMDB51                                                      | RGB + Optical flow                 | [GitHub](https://github.com/kylemin/S3D) |
| [CSN](https://arxiv.org/abs/1904.02811)                | ICCV 2019    | Supervised      | Sports-1M, Kinetics-400, Something-Something V1                                                           | RGB                                | [GitHub](https://github.com/facebookresearch/VMZ) |
| [SlowFast](https://arxiv.org/abs/1812.03982) | ICCV 2019    | Supervised | Kinetics-400, Kinetics-600, Charades, AVA                                                                 | RGB                                | [GitHub](https://github.com/facebookresearch/SlowFast) |
| [STM](https://arxiv.org/abs/1908.02486) | ICCV 2019    | Supervised | Something-Something V1, Something-Something V2, Kinetics-400, UCF101, HMDB51                              | RGB                                | - |
| [DEEP-HAL](https://ieeexplore.ieee.org/document/9008573) | ICCV 2019    | Self-supervised | HMDB51, Charades, MPII Cooking                                                                            | RGB + Optical flow                 | - |
| [Xv et al.](https://ieeexplore.ieee.org/document/8953292) | CVPR 2019    | Self-supervised | UCF101, HMDB51                                                                                           | RGB                                | - |
| [X3D](https://arxiv.org/abs/2004.04730) | CVPR 2020    | Supervised | Kinetics-400, Kinetics-600, Charades, AVA                                                                 | RGB                                | [GitHub](https://github.com/facebookresearch/SlowFast) |
| [TPN](https://arxiv.org/abs/2004.03548) | CVPR 2020    | Supervised | Kinetics-400, Something-Something V1, Something-Something V2, Epic-Kitchens                               | RGB                                | [GitHub](https://github.com/decisionforce/TPN) |
| [SpeedNet](https://arxiv.org/abs/2004.06130) | CVPR 2020    | Self-supervised | Kinetics-400, UCF101, HMDB51, NfS                                                                         | RGB                                | [GitHub](https://github.com/yasar-rehman/fedvssl) |
| [CoCLR](https://arxiv.org/abs/2010.09709) | NeurIPS 2020 | Self-supervised | UCF101, HMDB51, Kinetics-400                                                                             | RGB + Optical flow                 | [GitHub](https://github.com/TengdaHan/CoCLR) |
| [VTHCL](https://arxiv.org/abs/2006.15489) | arXiv 2020  | Self-supervised | Kinetics-400, UCF101, HMDB51                                                                             | RGB                                | [GitHub](https://github.com/decisionforce/VTHCL) |
| [MvPL](https://arxiv.org/abs/2104.00682) | ICCV 2021    | Semi-supervised | Kinetics-400, UCF101, HMDB51                                                                             | RGB + Optical flow                 | - |
| [CVRL](https://ieeexplore.ieee.org/document/4587756) | CVPR 2021    | Self-supervised | Kinetics-400, Kinetics-600, UCF101, HMDB51                                                               | RGB                                | [GitHub](https://github.com/tensorflow/models/tree/master/official/projects/video_ssl) |
| [Yang et al.](https://arxiv.org/abs/2104.01198) | CVPR 2021    | Supervised | Kinetics-400, Kinetics-700, Charades, Something-Something V1, AVA                                        | RGB                                | - |
| [3DResNet+ATFR](https://arxiv.org/abs/2011.08652) | CVPR 2021    | Supervised | Kinetics-400, Kinetics-600, UCF101, HMDB51, Something-Something V2                                       | RGB                                | - |
| [MoViNet](https://arxiv.org/abs/2103.11511) | CVPR 2021    | Supervised | Kinetics-400, Kinetics-600, Kinetics-700, Something-Something V2, Epic-Kitchens-100, MiT, Charades        | RGB                                | [GitHub](https://github.com/tensorflow/models) |
| [ODF+SDF](https://arxiv.org/abs/2001.04627) | ACM MM 2021 | Self-supervised | HMDB51, Charades, MPII Cooking, EPIC-Kitchen                                                             | RGB + Optical flow + object/saliency detectors | - |
| [CLASTER](https://arxiv.org/abs/2101.07042) | ECCV 2022    | Reinforcement+Zero-shot | UCF101, HMDB51, Olympic Sports                                                                         | RGB + Optical flow + Semantic embeddings | - |
| [TFCNet](https://arxiv.org/abs/2203.05928) | arXiv 2022  | Supervised | Diving48, CATER                                                                                         | RGB                                | - |
| [Multi-Transforms](https://arxiv.org/abs/2102.10378) | ICMEW 2024  | Self-supervised | UCF101, HMDB51                                                                                           | RGB                                | - |
| [HoT](https://arxiv.org/abs/2110.05216) | ICASSP 2024   | Supervised | HMDB51, MPII Cooking                                                                                    | RGB + Optical flow                 | - |
| [Flow corr.](https://arxiv.org/abs/2310.10059) | ICASSP 2024   | Supervised | HMDB51, Charades, MPII Cooking                                                                          | RGB + Optical flow                 | - |

</details>

### Two-stream Methods

<details>
<summary>Click to expand Table 4</summary>

| Model                                         | Venue        | Learning         | Dataset                                                                | Modality                                       | Code |
|-----------------------------------------------|--------------|------------------|------------------------------------------------------------------------|-----------------------------------------------|------|
| [Two-Stream ConvNet](https://arxiv.org/abs/1406.2199)                        | NeurIPS 2014  | Supervised       | UCF101, HMDB51                                                         | RGB + Optical flow                            | [GitHub](https://github.com/feichtenhofer/twostreamfusion) |
| [P-CNN](https://ieeexplore.ieee.org/document/7410725)                                     | ICCV 2015    | Supervised       | JHMDB, MPII Cooking                                                    | RGB + Optical Flow + Joint                    | - |
| [TDD](https://arxiv.org/abs/1505.04868)                                       | CVPR 2015    | Supervised       | HMDB51, UCF101                                                         | RGB + Optical flow                            | [GitHub](https://github.com/damien911224/theWorldInSafety) |
| [Two-Stream Fusion](https://arxiv.org/abs/1604.06573)                         | CVPR 2016    | Supervised       | UCF101, HMDB51                                                         | RGB + Optical flow                            | [GitHub](https://github.com/feichtenhofer/twostreamfusion) |
| [TSN-Two-Stream](https://arxiv.org/abs/1608.00859)                            | ECCV 2016    | Supervised       | HMDB51, UCF101                                                         | RGB + RGB differences + Optical flow + Warped optical flow | [GitHub](https://github.com/yjxiong/temporal-segment-networks) |
| [DOVF](https://arxiv.org/abs/1701.07368)                                      | CVPR 2017    | Supervised       | UCF101, HMDB51                                                         | RGB + Optical flow                            | [GitHub](https://github.com/alibaba-mmai-research/TAdaConv) |
| [TLE](https://arxiv.org/abs/1611.06678)                                       | CVPR 2017    | Supervised       | UCF101, HMDB51                                                         | RGB + Optical flow                            | [GitHub](https://github.com/bryanyzhu/two-stream-pytorch) |
| [ActionVLAD](https://arxiv.org/abs/1704.02895)                                | CVPR 2017    | Supervised       | HMDB51, UCF101, Charades                                                | RGB + Optical flow                            | - |
| [TRN-Two-Stream](https://arxiv.org/abs/1711.08496)                            | ECCV 2018    | Supervised       | Something-Something V1, Something-Something V2, Charades                | RGB                                           | [GitHub](https://paperswithcode.com/paper/temporal-relational-reasoning-in-videos#code) |
| [TSM-Two-Stream](https://arxiv.org/abs/1811.08383)                            | ICCV 2019    | Supervised       | Something-Something V1, Something-Something V2, Kinetics-400, UCF101, HMDB51 | RGB + Optical flow                            | [GitHub](https://github.com/MIT-HAN-LAB/temporal-shift-module) |
| [KTSN](https://arxiv.org/abs/2002.03312)                                      | arXiv 2020   | Supervised       | FSD-10                                                                 | RGB + Optical flow + Skeleton                  | - |
| [MSM-ResNets](https://www.sciencedirect.com/science/article/abs/pii/S0262885621000135)                               | IVC 2021     | Supervised       | UCF101, HMDB51                                                         | RGB + Optical Flow + Motion Saliency          | - |
| [MAT-EffNet](https://link.springer.com/article/10.1007/s00530-022-00961-3)                                | MMSys 2023    | Supervised       | UCF101, HMDB51, Kinetics-400                                            | RGB + Optical flow                            | - |
| [TTFA](https://ieeexplore.ieee.org/document/10669816)                                      | SPL 2024     | Few-shot         | Something-Something V2, Kinetics-400                                    | RGB + Optical flow                            | - |

</details>

### (2+1)D-based Methods

<details>
<summary>Click to expand Table 5</summary>

| Model                                         | Venue        | Learning         | Dataset                                                                | Modality                                       | Code |
|-----------------------------------------------|--------------|------------------|------------------------------------------------------------------------|-----------------------------------------------|------|
| [R(2+1)D](https://arxiv.org/abs/1711.11248)                                   | CVPR 2018    | Supervised       | Kinetics-400, Sports-1M, UCF101, HMDB51                                | RGB + Optical flow                            | [GitHub](https://github.com/facebookresearch/VMZ) |
| [R(2+1)D+BERT](https://arxiv.org/abs/2008.01232)                              | ECCVW 2020   | Supervised       | HMDB51, UCF101                                                         | RGB                                           | [GitHub](https://github.com/artest08/LateTemporalModeling3DCNN) |
| [XDC](https://arxiv.org/abs/1911.12667)                                       | NeurIPS 2020 | Self-supervised  | HMDB51, UCF101                                                         | RGB + Audio                                    | [GitHub](https://github.com/HumamAlwassel/XDC) |
| [ELo](https://arxiv.org/abs/2002.12177)                                       | CVPR 2020    | Self-supervised  | Kinetics-400, UCF101, HMDB51                                           | RGB + Optical flow + Audio                    | - |
| [Jin et al.](https://ieeexplore.ieee.org/document/9611970)    | ICICSP 2021  | Supervised       | UCF101                                                                  | RGB                                           | - |
| [GDT](https://www.semanticscholar.org/paper/Multi-modal-Self-Supervision-from-Generalized-Data-Patrick-Asano/ab120fa17c22dba7d50dd45e039c8a2e86c96348)                                       | arXiv 2021   | Self-supervised  | Kinetics-400, UCF101, HMDB51                                           | RGB + Audio                                    | - |
| [AVID](https://arxiv.org/abs/2004.12943)                                      | CVPR 2021    | Self-supervised  | Kinetics-400, UCF101, HMDB51                                           | RGB + Audio                                    | [GitHub](https://github.com/facebookresearch/AVID-CMA) |

</details>

### Transformer-based Methods

<details>
<summary>Click to expand Table 6</summary>

| Model                                         | Venue        | Learning         | Dataset                                                                | Modality                                       | Code |
|-----------------------------------------------|--------------|------------------|------------------------------------------------------------------------|-----------------------------------------------|------|
| [VTN](https://arxiv.org/abs/2102.00719)                                       | ICCV 2021    | Supervised       | Kinetics-400, MiT                                                      | RGB                                           | [GitHub](https://github.com/bomri/SlowFast/blob/master/projects/vtn/README.md) |
| [TimeSformer](https://arxiv.org/abs/2102.05095)                               | ICML 2021    | Supervised       | Kinetics-400, Kinetics-600                                              | RGB                                           | [GitHub](https://github.com/facebookresearch/TimeSformer) |
| [STAM](https://arxiv.org/abs/2103.13915)                                       | arXiv 2021   | Supervised       | Kinetics-400, UCF101, Charades                                          | RGB                                           | [GitHub](https://github.com/Alibaba-MIIL/STAM) |
| [ViViT](https://arxiv.org/abs/2103.15691)                                      | ICCV 2021    | Supervised       | Kinetics-400, Kinetics-600, Epic-Kitchens-100, MiT, Something-Something V2 | RGB                                           | [GitHub](https://github.com/google-research/scenic) |
| [MViT](https://arxiv.org/abs/2104.11227)                                       | ICCV 2021    | Supervised       | Kinetics-400, Kinetics-600, Something-Something V2, Charades, AVA        | RGB                                           | [GitHub](https://github.com/facebookresearch/SlowFast) |
| [Motionformer](https://arxiv.org/abs/2106.05392)                               | NeurIPS 2021 | Supervised       | Kinetics-400, Kinetics-600, Something-Something V2, Epic-Kitchens-100    | RGB                                           | [GitHub](https://github.com/facebookresearch/Motionformer) |
| [X-ViT](https://arxiv.org/abs/2106.05968)                                      | NeurIPS 2021 | Supervised       | Kinetics-400, Kinetics-600, Something-Something V2, Epic-Kitchens-100    | RGB                                           | [GitHub](https://github.com/1adrianb/video-transformers) |
| [TallFormer](https://arxiv.org/abs/2204.01680)                                 | ECCV 2022   | Supervised       | THUMOS14, ActivityNet                                                  | RGB                                           | [GitHub](https://github.com/klauscc/tallformer) |
| [VideoSwin](https://arxiv.org/abs/2106.13230)                                  | CVPR 2022   | Supervised       | Kinetics-400, Kinetics-600, Something-Something V2                      | RGB                                           | [GitHub](https://github.com/SwinTransformer/Video-Swin-Transformer) |
| [ORViT](https://arxiv.org/abs/2110.06915)                                      | CVPR 2022   | Supervised       | Something-Something V2, SomethingElse, Diving48, AVA, Epic-Kitchens-100 | RGB                                           | [GitHub](https://github.com/eladb3/orvit) |
| [BEVT](https://arxiv.org/abs/2112.01529)                                       | CVPR 2022   | Self-supervised  | Kinetics-400, Something-Something V2, Diving-48                          | RGB                                           | [GitHub](https://github.com/xyzforever/bevt) |
| [MaskFeat](https://arxiv.org/abs/2112.09133)                                   | CVPR 2022   | Self-supervised  | Kinetics-400, Kinetics-600, Kinetics-700                                 | RGB                                           | [GitHub](https://github.com/facebookresearch/SlowFast) |
| [UniFormer](https://arxiv.org/abs/2201.04676)                                  | arXiv 2022  | Supervised       | Kinetics-400, Kinetics-600, Something-Something V1, V2                   | RGB                                           | [GitHub](https://github.com/sense-x/uniformer) |
| [VideoMAE](https://arxiv.org/abs/2203.12602)                                   | NeurIPS 2022 | Self-supervised  | Kinetics-400, Something-Something V2, UCF101, HMDB51, AVA               | RGB                                           | [GitHub](https://github.com/MCG-NJU/VideoMAE) |
| [MTV](https://arxiv.org/abs/2201.04288)                                        | CVPR 2022   | Supervised       | Kinetics-400, Kinetics-600, Kinetics-700, Something-Something V2, Epic-Kitchens-100, MiT | RGB | [GitHub](https://github.com/google-research/scenic) |
| [MAE-ST](https://arxiv.org/abs/2205.09113)                                     | arXiv 2022  | Self-supervised  | Kinetics-400, Something-Something V2, AVA                                | RGB                                           | [GitHub](https://github.com/facebookresearch/mae_st) |
| [CAST](https://arxiv.org/abs/2311.18825)                                       | NeurIPS 2023 | Supervised       | Kinetics-400, Something-Something V2, Epic-Kitchens-100                  | RGB                                           | [GitHub](https://github.com/khu-vll/cast) |
| [UniFormerV2](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_UniFormerV2_Unlocking_the_Potential_of_Image_ViTs_for_Video_Understanding_ICCV_2023_paper.pdf)                                | ICCV 2023   | Supervised+Contrastive | Kinetics-400, Kinetics-600, Kinetics-700, MiT, Something-Something V1, V2, ActivityNet, HACS | RGB | - |
| [OmniMAE](https://arxiv.org/abs/2206.08356)                                    | CVPR 2023   | Self-supervised  | Something-Something V2, Epic-Kitchens-100, Kinetics-400                 | RGB                                           | [GitHub](https://github.com/facebookresearch/omnivore) |
| [MVD](https://arxiv.org/abs/2212.04500)                                        | CVPR 2023   | Self-supervised  | Kinetics-400, Something-Something V2, UCF101, HMDB51                    | RGB                                           | [GitHub](https://github.com/ruiwang2021/mvd) |
| [Hiera](https://arxiv.org/abs/2306.00989)                                      | ICML 2023   | Self-supervised  | Kinetics-400, Kinetics-600, Kinetics-700, Something-Something V2, AVA    | RGB                                           | [GitHub](https://github.com/facebookresearch/hiera) |
| [VideoMAE V2](https://arxiv.org/abs/2303.16727)                                | CVPR 2023   | Self-supervised  | Kinetics-400, Something-Something V2, UCF101, HMDB51                    | RGB                                           | [GitHub](https://github.com/OpenGVLab/VideoMAEv2) |
| [SOAP](https://arxiv.org/abs/2407.16344)                                       | ACM MM 2024 | Few-shot         | Something-Something V2, Kinetics-400, UCF101, HMDB51                    | RGB                                           | [GitHub](https://paperswithcode.com/paper/soap-enhancing-spatio-temporal-relation-and#code) |
| [C2C](https://arxiv.org/abs/2407.06113)                                        | ECCV 2024   | Zero-shot        | Sth-com                                                                | RGB                                           | [GitHub](https://github.com/rongchangli/zscar_c2c) |
| [VMPs](https://arxiv.org/abs/2407.03179)                                       | ACML 2024   | Supervised       | HMDB51, MPII Cooking 2, FineGym                                         | RGB + Motion prompts                         | [GitHub](https://github.com/q1xiangchen/vmps) |
| [TIME Layer](https://arxiv.org/abs/2411.15284)                                 | arXiv 2024   | Self-supervised  | UCF101, HMDB51, UWA3D Multiview Activity II, NTU RGB+D, NTU RGB+D 120   | RGB + Depth                                   | - |

</details>

### Skeletons-based Methods

<details>
<summary>Click to expand Table 7</summary>

| Model                                         | Venue        | Learning         | Dataset                                                                | Modality                                       | Code |
|-----------------------------------------------|--------------|------------------|------------------------------------------------------------------------|-----------------------------------------------|------|
| [Dynamic Skeletons](https://ieeexplore.ieee.org/document/7299172)                         | CVPR 2015    | Supervised       | MSRDailyActivity, CAD-60, SYSU 3D HOI                                    | Depth + Joint                                  | - |
| [HBRNN-L](https://ieeexplore.ieee.org/document/7298714)                                   | CVPR 2015    | Supervised       | MSRAction3D, Berkeley MHAD, HDM05                                       | Joint                                          | - |
| [Part-aware LSTM](https://arxiv.org/abs/1604.02808)                           | CVPR 2016    | Supervised       | NTU RGB+D                                                               | RGB + Depth + Joint + Infrared                | [GitHub](https://github.com/shahroudy/NTURGB-D) |
| [LARP-SO](https://ieeexplore.ieee.org/document/7780853)                                   | CVPR 2016    | Supervised       | Florence3D-Action, MSRActionPairs3D, G3D-Gaming                         | Joint                                          | - |
| [STA-LSTM](https://arxiv.org/abs/1611.06067)                                  | AAAI 2017    | Supervised       | NTU RGB+D                                                               | Joint                                          | - |
| [LieNet](https://arxiv.org/abs/1612.05877)                                    | CVPR 2017    | Supervised       | NTU RGB+D, HDM05, G3D-Gaming                                           | Joint + Bone                                   | - |
| [Two-Stream RNN](https://arxiv.org/abs/1704.02581)                            | CVPR 2017    | Supervised       | NTU RGB+D                                                               | Joint                                          | - |
| [Ke et al.](https://arxiv.org/abs/1703.03492)                                 | CVPR 2017    | Supervised       | NTU RGB+D                                                               | Joint                                          | - |
| [VA-LSTM](https://arxiv.org/abs/1703.08274)                                   | ICCV 2017    | Supervised       | NTU RGB+D, SYSU 3D HOI                                                 | Joint                                          | [GitHub](https://github.com/microsoft/View-Adaptive-Neural-Networks-for-Skeleton-based-Human-Action-Recognition) |
| [View Invariant](https://www.sciencedirect.com/science/article/pii/S0031320317300936)                            | Pattern Recognit. 2017 | Supervised  | NTU RGB+D, Northwestern-UCLA, UWA3D Multiview Activity II, MSRC-12    | Joint                                          | - |
| [Two-Stream CNN](https://arxiv.org/abs/1704.07595)                            | ICMEW 2017   | Supervised       | NTU RGB+D, PKU-MMD I                                                  | Joint + Skeleton motion                       | [GitHub](https://github.com/hikvision-research/skelact) |
| [LSTM-CNN](https://ieeexplore.ieee.org/document/8026287)                                  | ICMEW 2017   | Supervised       | NTU RGB+D                                                               | Joint                                          | - |
| [ST-LSTM+Trust Gate](https://arxiv.org/abs/1706.08276)                        | TPAMI 2018   | Supervised       | NTU RGB+D, MSRAction3D, SYSU 3D HOI, Berkeley MHAD                     | Joint                                          | - |
| [ST-GCN](https://arxiv.org/abs/1801.07455)                                    | AAAI 2018    | Supervised       | Kinetics-400, NTU RGB+D                                                | Joint                                          | [GitHub](https://github.com/yysijie/st-gcn) |
| [Tang et al.](https://ieeexplore.ieee.org/document/8578656)                               | CVPR 2018    | Reinforcement    | NTU RGB+D, SYSU 3D HOI, UTKinect-Action3D                              | Joint + Bone                                   | - |
| [AS-GCN](https://arxiv.org/abs/1904.12659)                                    | CVPR 2019    | Supervised       | NTU RGB+D, Kinetics-400                                                | Joint + Bone                                   | [GitHub](https://github.com/limaosen0/AS-GCN) |
| [2s-AGCN](https://arxiv.org/abs/1805.07694)                                   | CVPR 2019    | Fully-supervised | NTU RGB+D, Kinetics-skeleton                                           | Joint + Bone                                   | [GitHub](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) |
| [DGNN](https://ieeexplore.ieee.org/document/8954160)                                      | CVPR 2019    | Supervised       | NTU RGB+D, Kinetics-skeleton                                           | Joint + Bone                                   | [GitHub](https://github.com/kenziyuliu/DGNN-PyTorch) |
| [EfficientGCN](https://arxiv.org/abs/2010.09978)                              | ACM MM 2020  | Supervised       | NTU RGB+D, NTU RGB+D 120                                               | Joint + Velocity + Bone                        | - |
| [RA-GCN](https://arxiv.org/abs/2008.03791)                                    | TCSVT 2020   | Supervised       | NTU RGB+D, NTU RGB+D 120                                               | Joint + Bone                                   | [gitee](https://gitee.com/yfsong0709/RA-GCNv2) |
| [Shift-GCN](https://ieeexplore.ieee.org/document/9157077)                                 | CVPR 2020    | Supervised       | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                            | Joint + Bone                                   | [GitHub](https://github.com/kchengiva/Shift-GCN) |
| [MS-G3D](https://arxiv.org/abs/2003.14111)                                    | CVPR 2020    | Supervised       | NTU RGB+D 60, NTU RGB+D 120, Kinetics-skeleton                         | Joint + Bone                                   | [GitHub](https://github.com/kenziyuliu/ms-g3d) |
| [DSTA-Net](https://arxiv.org/abs/2007.03263)                                  | ACCV 2020    | Supervised       | NTU RGB+D, NTU RGB+D 120                                               | Joint + Bone                                   | - |
| [SCK+DCK / SCK$\oplus$+DCK$\oplus$](https://arxiv.org/abs/2012.14371)          | TPAMI 2020   | Supervised       | UTKinect-Action3D, Florence3D-Action, MSRAction3D, NTU RGB+D 60, Kinetics-400, HMDB51, MPII Cooking | Joint | - |
| [CTR-GCN](https://arxiv.org/abs/2107.12213)                                   | ICCV 2021    | Supervised       | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                            | Joint + Bone                                   | - |
| [FGCN](https://arxiv.org/abs/2003.07564)                                      | TIP 2022     | Supervised       | NTU RGB+D, NTU RGB+D120, Northwestern-UCLA                            | Joint + Bone                                   | - |
| [AGE-Ens](https://arxiv.org/abs/2105.01563)                                   | TNNLS 2022   | Supervised       | NTU RGB+D, NTU RGB+D 120                                               | Joint + Bone                                   | [GitHub](https://github.com/kfzyqin/Angular-Skeleton-Encoding) |
| [PoseConv3D](https://arxiv.org/abs/2104.13586)                                | CVPR 2022    | Supervised       | Kinetics-400, UCF101, HMDB51                                           | Joint + Bone + RGB                             | [GitHub](https://github.com/open-mmlab/mmaction2) |
| [InfoGCN](https://ieeexplore.ieee.org/document/9879266)                                   | CVPR 2022    | Supervised       | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                            | Joint + Bone                                   | [GitHub](https://github.com/stnoah1/infogcn) |
| [DASTM](https://link.springer.com/chapter/10.1007/978-3-031-19772-7_11)                                     | ECCV 2022    | Few-shot         | NTU RGB+D 120, Kinetics-skeleton                                        | Joint + Bone                                   | - |
| [Uncertainty-DTW](https://arxiv.org/abs/2211.00005)                           | ECCV 2022    | Supervised/Unsupervised few-shot | NTU RGB+D, NTU RGB+D 120, Kinetics-skeleton                          | Skeleton sequences                             | [GitHub](https://github.com/leiwangr/udtw) |
| [TranSkeleton](https://ieeexplore.ieee.org/document/10029908)                              | TCSVT 2023   | Supervised       | NTU RGB+D, NTU RGB+D 120                                               | Joint + Bone                                   | - |
| [HiCo](https://arxiv.org/abs/2212.02082)                                      | AAAI 2023    | Unsupervised + Contrastive | NTU RGB+D, NTU RGB+D 120, PKU-MMD I, PKU MMD II                        | Joint                                          | [GitHub](https://paperswithcode.com/paper/hierarchical-contrast-for-unsupervised#code) |
| [FR-Head](https://arxiv.org/abs/2303.03729)                                   | CVPR 2023    | Supervised + Contrastive | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                             | Joint + Bone                                    | [GitHub](https://github.com/zhysora/fr-head) |
| [3Mformer](https://arxiv.org/abs/2303.14474)                                  | CVPR 2023    | Supervised             | NTU RGB+D, NTU RGB+D 120, Kinetics-400, Northwestern-UCLA              | Joint + Hyper-edge                              | - |
| [HYSP](https://arxiv.org/abs/2303.06242)                                      | ICLR 2023    | Self-supervised         | NTU RGB+D, NTU RGB+D 120, PKU-MMD I                                     | Joint                                          | [GitHub](https://github.com/paolomandica/hysp) |
| [PAINet](https://ieeexplore.ieee.org/document/10377291)                                    | ICCV 2023    | Few-shot               | NTU RGB+D 120, Kinetics-skeleton                                        | Joint + Bone                                    | - |
| [PCM<sup>3</sup>](https://arxiv.org/abs/2308.03975)                    | ACM MM 2023  | Self-supervised         | NTU RGB+D, NTU RGB+D 120, PKU-MMD I                                     | Joint + Bone + Motion                          | [GitHub](https://github.com/JHang2020/Shap-Mix) |
| [Stream-GCN](https://arxiv.org/abs/2306.07576)                                | IJCAI 2023   | Supervised             | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                             | Joint + Bone                                    | - |
| [SkeletonGCL](https://arxiv.org/abs/2301.10900)                               | arXiv 2023   | Self-supervised         | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                             | Joint + Bone                                    | [GitHub](https://github.com/oliverhxh/skeletongcl) |
| [DSCNet](https://www.sciencedirect.com/science/article/pii/S0957417423035637)                                    | ESWA 2024    | Supervised + Multimodal | NTU RGB+D, NTU RGB+D 120, PKU-MMD I, UAV-Human, IKEA ASM, Northwestern-UCLA | RGB + Joint + Bone                             | - |
| [Skeleton-OOD](https://arxiv.org/abs/2405.20633)                              | Neurocomputing 2024 | Supervised         | NTU RGB+D, NTU RGB+D 120, Kinetics-400                                 | Joint                                          | [GitHub](https://github.com/YilliaJing/Skeleton-OOD) |
| [ViA](https://arxiv.org/abs/2209.00065)                                       | IJCV 2024    | Self-supervised         | Posetics, NTU RGB+D, NTU RGB+D 120, Toyota Smarthome, UAV-Human, Penn Action | Joint + Motion                                  | [GitHub](https://github.com/YangDi666/UNIK) |
| [DeGCN](https://ieeexplore.ieee.org/document/10478824)                                     | TIP 2024     | Supervised             | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                             | Joint + Bone                                    | [GitHub](https://github.com/WoominM/DeGCN_pytorch) |
| [Js-SaPR-GCN](https://ieeexplore.ieee.org/document/10323358)                               | TCSVT 2024   | Supervised             | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                             | Joint + Bone + Motion                          | - |
| [BlockGCN](https://ieeexplore.ieee.org/document/10658569)                                  | CVPR 2024    | Supervised             | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                             | Joint + Bone + Motion                          | [GitHub](https://github.com/zhouyuxuanyx/blockgcn) |
| [JEANIE](https://arxiv.org/abs/2402.04599)                                    | IJCV 2024    | Supervised/Unsupervised few-shot | NTU RGB+D, NTU RGB+D 120, Kinetics-skeleton, MSRAction3D, UWA3D Multiview Activity | Skeleton sequences                             | - |
| [SA-DVAE](https://arxiv.org/abs/2407.13460)                                   | arXiv 2024   | Zero-shot              | NTU RGB+D, NTU RGB+D 120, PKU-MMD I                                    | Joint                                          | [GitHub](https://github.com/pha123661/SA-DVAE) |
| [ProtoGCN](https://arxiv.org/abs/2411.18941)                                  | arXiv 2024   | Self-supervised + Prototype | NTU RGB+D, NTU RGB+D 120, Kinetics-skeleton, FineGYM                   | Joint                                          | [GitHub](https://github.com/firework8/ProtoGCN) |
| [HSIC-based](https://arxiv.org/abs/2412.18780)                                | arXiv 2024   | Supervised             | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                             | Joint + Bone                                    | - |
| [USDRL](https://arxiv.org/abs/2412.09220)                                     | AAAI 2025    | Self-supervised         | NTU RGB+D, NTU RGB+D 120, PKU-MMD I, PKU-MMD II                        | Joint + Bone + Motion                          | [GitHub](https://github.com/wengwanjiang/USDRL) |


</details>

### Depth-based Methods

<details>
<summary>Click to expand Table 8</summary>

| Model                                          | Venue                       | Learning       | Dataset                                                                | Modality                                       | Code |
|------------------------------------------------|-----------------------------|----------------|------------------------------------------------------------------------|-----------------------------------------------|------|
| [HON4D](https://ieeexplore.ieee.org/document/6618942)                                      | CVPR 2013                   | Supervised     | MSRAction3D, MSRDailyActivity3D, MSRActionPairs3D                       | Depth                                         | - |
| [HOPC](https://arxiv.org/abs/1408.3809)                                       | ECCV 2014                   | Supervised     | MSRAction3D, MSRActionPairs3D, UWA3D Multiview Activity                 | Depth + Point cloud                           | - |
| [Wang et al.](https://ieeexplore.ieee.org/abstract/document/7358110)                                | Trans. Human-Mach. Syst. 2016| Supervised     | MSRAction3D, MSRDailyActivity3D, UTKinect-Action3D                      | Depth                                         | - |
| [Rahmani et al.](https://ieeexplore.ieee.org/abstract/document/7780536)                             | CVPR 2016                   | Supervised     | Northwestern-UCLA, UWA3D Multiview Activity II                          | Depth                                         | - |
| [S<sup>2</sup>DDI](https://ieeexplore.ieee.org/document/8265332)                    | ICCVW 2017                  | Supervised     | MSRAction3D, G3D-Gaming, MSRDailyActivity3D, SYSU 3D HOI, UTD-MHAD      | Depth                                         | - |
| [Wang et al.](https://arxiv.org/abs/1804.01194)                                | TMM 2018                    | Supervised     | NTU RGB+D                                                               | Depth                                         | - |
| [MVDI](https://arxiv.org/abs/1806.11269)                                       | Inf. Sci. 2018              | Supervised     | NTU RGB+D, Northwestern-UCLA, UWA3D Multiview Activity II              | Depth                                         | [GitHub](https://github.com/3huo/MVDI) |
| [3DFCNN](https://arxiv.org/abs/2006.07743)                                     | Multimed. Tools Appl. 2020  | Supervised     | NTU RGB+D, Northwestern-UCLA, UWA3D Multiview Activity II              | Depth                                         | - |
| [Liu et al.](https://ieeexplore.ieee.org/document/7952393)                                 | ICASSP 2017                 | Supervised     | MSRAction3D, DHA                                                        | Depth                                         | - |
| [Dhiman et al.](https://arxiv.org/abs/1912.03632)                              | TIP 2020                    | Supervised     | NTU RGB-D, UWA3D Multiview Activity II, Northwestern-UCLA               | RGB + Depth                                   | - |
| [Stateful ConvLSTM](https://arxiv.org/abs/2006.07744)                          | arXiv 2020                  | Supervised     | NTU RGB+D                                                               | Depth                                         | - |
| [DEAR](https://arxiv.org/abs/2408.15679)                                       | arXiv 2024                  | Supervised     | Something-Something V2                                                  | RGB + Depth                                   | [GitHub](https://github.com/sadeghrahmanib/dear) |

</details>

### Infrared-based Methods

<details>
<summary>Click to expand Table 9</summary>

| Model                                          | Venue                        | Learning       | Dataset                                                               | Modality                                          | Code |
|------------------------------------------------|------------------------------|----------------|-----------------------------------------------------------------------|--------------------------------------------------|------|
| [Gao et al.](https://www.sciencedirect.com/science/article/pii/S0925231216307044)                                  | Neurocomputing 2016          | Supervised     | InfAR                                                                 | Infrared + Optical flow                          | - |
| [Jiang et al.](https://arxiv.org/abs/1705.06709)                               | CVPRW 2017                   | Supervised     | InfAR                                                                 | Infrared + Optical flow                          | - |
| [Kawashima et al.](https://ieeexplore.ieee.org/document/8078497)                           | AVSS 2017                    | Supervised     | Custom Dataset                                                        | Infrared                                         | - |
| [Shah et al.](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10751/1075111/A-spatio-temporal-deep-learning-approach-for-human-action-recognition/10.1117/12.2502993.full)                                | SPIE 2018                    | Supervised     | Custom IR Dataset                                                     | Infrared                                         | - |
| [TSTDDs](https://ieeexplore.ieee.org/document/8332532)                                     | SPL 2018                     | Supervised     | InfAR, NTU RGB+D                                                      | Infrared + Optical flow                          | - |
| [Akula et al.](https://www.sciencedirect.com/science/article/pii/S1389041717302206)                               | CSR 2018                     | Supervised     | Custom IR Dataset                                                     | Infrared                                         | - |
| [Imran et al.](https://www.sciencedirect.com/science/article/pii/S1350449519302762)                               | Infrared Phys. Technol. 2019 | Supervised     | InfAR, IITR-IAR                                                       | Infrared + Optical flow                          | - |
| [Meglouli et al.](https://www.semanticscholar.org/paper/A-new-technique-based-on-3D-convolutional-neural-in-Khebli-Meglouli/9157ffcf1c33eebc547651e80fca6952aeefc313)                            | CEAI 2019                     | Supervised     | InfAR                                                                 | Infrared + Optical flow                          | - |
| [Mehta et al.](https://ieeexplore.ieee.org/document/9412632)                               | ICPR 2020                     | Adversarial    | TSF                                                                   | Infrared + Optical flow                          | [GitHub](https://github.com/ivineetm007/Fall-detection) |

</details>

### Point Cloud Methods

<details>
<summary>Click to expand Table 10</summary>

| Model                                          | Venue                       | Learning       | Dataset                                                                | Modality                                       | Code |
|------------------------------------------------|-----------------------------|----------------|------------------------------------------------------------------------|-----------------------------------------------|------|
| [MeteorNet](https://arxiv.org/abs/1910.09165)                                   | ICCV 2019                   | Supervised     | MSRAction3D                                                            | Point cloud                                    | [GitHub](https://github.com/xingyul/meteornet) |
| [PointLSTM](https://ieeexplore.ieee.org/document/9157795)                                  | CVPR 2020                   | Supervised     | MSRAction3D                                                            | Point cloud                                    | [GitHub](https://github.com/VIPL-SLP/pointlstm-gesture-recognition-pytorch) |
| [3DV-PointNet++](https://ieeexplore.ieee.org/document/9157595)                              | CVPR 2020                   | Supervised     | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA, UWA3D Multiview Activity II | Depth                                          | [GitHub](https://github.com/3huo/3DV-Action) |
| [ASTA3DConv](https://ieeexplore.ieee.org/abstract/document/9522122)                                 | Trans. Instrum. Meas. 2020   | Supervised     | MSRAction3D                                                            | Point cloud                                    | - |
| [Wang et al.](https://ieeexplore.ieee.org/document/9423387)  | WACV 2021                   | Self-supervised| NTU RGB+D, NTU-PCL, MSRAction3D                                         | Point cloud                                    | - |
| [P4Transformer](https://ieeexplore.ieee.org/document/9578674)                               | CVPR 2021                   | Supervised     | MSRAction3D, NTU RGB+D, NTU RGB+D 120                                  | Point cloud                                    | [GitHub](https://github.com/hehefan/P4Transformer) |
| [PSTNet](https://arxiv.org/abs/2205.13713)                                      | ICLR 2021                   | Supervised     | MSRAction3D, NTU RGB+D, NTU RGB+D 120                                  | Point cloud                                    | [GitHub](https://github.com/hehefan/Point-Spatio-Temporal-Convolution) |
| [PST<sup>2</sup>](https://arxiv.org/abs/2110.09783)                      | WACV 2022                   | Supervised     | MSRAction3D                                                            | Point cloud                                    | - |
| [MaST-Pre](https://arxiv.org/abs/2308.09245)                                    | ICCV 2023                   | Self-supervised| MSRAction3D, NTU RGB+D                                                 | Point cloud                                    | [GitHub](https://github.com/johnsonsign/mast-pre) |
| [PointCPSC](https://arxiv.org/abs/2308.09247)                                   | ICCV 2023                   | Self-supervised| MSRAction3D, NTU RGB+D                                                 | Point cloud                                    | - |
| [3DInAction](https://arxiv.org/abs/2303.06346)                                  | CVPR 2024                   | Supervised     | MSRAction3D                                                            | Point cloud                                    | [GitHub](https://github.com/sitzikbs/3dincaction) |
| [KAN-HyperpointNet](https://www.arxiv.org/abs/2409.09444)                           | arXiv 2024                   | Supervised     | NTU RGB+D, MSRAction3D                                                 | Point cloud                                    | - |

</details>


### Text/Audio Methods

<details>
<summary>Click to expand Table 11</summary>

| Model                                          | Venue                       | Learning       | Dataset                                                                | Modality                                       | Code |
|------------------------------------------------|-----------------------------|----------------|------------------------------------------------------------------------|-----------------------------------------------|------|
| [CPD](https://arxiv.org/abs/2001.05691)                                        | arXiv 2020                  | Self-supervised| Kinetics-400, HMDB51, UCF101                                           | RGB + Text                                    | [GitHub](https://github.com/MCG-NJU/CPD-Video) |
| [G-Blend](https://arxiv.org/abs/1905.12681)                                    | CVPR 2020                   | Multi-task     | Kinetics-400, Mini-Sports, EPIC-Kitchen                                | RGB + Optical flow + Audio                    | - |
| [MIL-NCE](https://arxiv.org/abs/1912.06430)                                    | CVPR 2020                   | Self-supervised| HowTo100M, HMDB51, UCF101                                             | RGB + Text                                    | [GitHub](https://github.com/antoine77340/MIL-NCE_HowTo100M) |
| [MMV](https://arxiv.org/abs/2006.16228)                                        | NeurIPS 2020                | Self-supervised| UCF101, HMDB51, Kinetics-600                                           | RGB + Audio + Text                            | [GitHub](https://github.com/google-deepmind/deepmind-research/tree/master/mmv) |
| [VIMPAC](https://arxiv.org/abs/2106.11250)                                     | arXiv 2021                  | Self-supervised| Something-Something V2, Diving48, UCF101, HMDB51                       | RGB + Text                                    | [GitHub](https://github.com/airsplay/vimpac) |
| [InternVideo](https://arxiv.org/abs/2212.03191)                                | CVPR 2023                   | Self-supervised| Kinetics-400, Kinetics-600, Kinetics-700, Something-Something V1, V2, ActivityNet, HACS, HMDB51 | RGB + Text                                    | [GitHub](https://github.com/OpenGVLab/InternVideo/tree/main/InternVideo1) |
| [Side4Video](https://arxiv.org/abs/2311.15769)                                 | arXiv 2023                  | Self-supervised| Something-Something V1, Something-Something V2, Kinetics-400           | RGB + Text                                    | [GitHub](https://github.com/HJYao00/Side4Video) |
| [EZ-CLIP](https://arxiv.org/abs/2312.08010)                                    | arXiv 2024                  | Zero-shot      | Kinetics-400, HMDB51, UCF101, Something-Something V2                    | RGB + Text                                    | [GitHub](https://github.com/shahzadnit/ez-clip) |
| [SATA](https://arxiv.org/abs/2403.01560)                                       | arXiv 2024                  | Zero-shot      | UCF101, HMDB51                                                       | RGB + Text                                    | [GitHub](https://github.com/kunyulin/xov-action) |
| [TC-CLIP](https://arxiv.org/abs/1703.03492)                                    | ECCV 2024                   | Zero-shot/Few-shot/Fully-supervised | HMDB51, UCF101, Kinetics-400, Something-Something V2                  | RGB + Text                                    | - |
| [InternVideo2](https://arxiv.org/abs/2403.15377)                               | arXiv 2024                  | Self-supervised + Multimodal | Kinetics-400, Kinetics-600, Kinetics-700, MiT, Something-Something V2, ActivityNet, HACS, Charades, HMDB51 | RGB + Audio + Text                            | [GitHub](https://github.com/OpenGVLab/InternVideo/tree/main/InternVideo2) |
| [OmniViD](https://arxiv.org/abs/2403.17935)                                    | CVPR 2024                   | Supervised     | Kinetics-400, Something-Something V2, UCF101, HMDB51                    | RGB + Text                                    | [GitHub](https://github.com/wdrink/OmniVid) |
| [LoCATe-GAT](https://ieeexplore.ieee.org/document/10769605)                                 | TETCI 2024                  | Zero-shot      | UCF101, HMDB51, ActivityNet, Kinetics-400                              | RGB + Text                                    | [GitHub](https://github.com/sandipan211/LoCATe-GAT) |
| [STDD](https://arxiv.org/abs/2412.09895)                                       | arXiv 2024                  | Zero-shot      | Kinetics-600, UCF101, HMDB51                                           | RGB + Text                                    | [GitHub](https://github.com/mia-yatingyu/stdd) |

</details>

## 💻 Datasets Used in The Journey of Action Recognition 

<details>
<summary>Click to expand Table 12</summary>

| Datasets | Year | # Classes | # Subjects | # Views | # Video clips | Sensor | Modalities | Dataset type |
|----------|------|-----------|------------|---------|--------------|--------|------------|--------------|
| [KTH](https://www.csc.kth.se/cvap/actions/) | 2004 | 6 | 25 | 1 | 2391 | Static camera | RGB | Human actions (e.g., walking, jogging) |
| [Weizmann](https://ieeexplore.ieee.org/document/1544882) | 2005 | 10 | 9 | 1 | 90 | - | RGB | Human actions (e.g., jumping, running) |
| [IXMAS](https://www.epfl.ch/labs/cvlab/data/data-ixmas10/) | 2006 | 11 | 10 | 5 | 330 | - | RGB | Movie Scenes (e.g., kissing, running) |
| [Hollywood](https://www.kaggle.com/datasets/mohdmuttalib/hollywood-movies-dataset) | 2008 | 8 | - | - | 1422 | - | RGB | Movie Scenes (e.g., eating, driving) |
| [Hollywood2](https://www.di.ens.fr/~laptev/actions/hollywood2/) | 2009 | 12 | - | - | 1709 | - | RGB | Movie Scenes (e.g., running, kissing) |
| [ADL](https://github.com/UIUC-ChenLab/YouHome-Dataset) | 2009 | 10 | 5 | - | 150 | Static camera | RGB | Daily Activities (e.g., brushing teeth, reading) |
| [Olympic Sports](http://vision.stanford.edu/Datasets/OlympicSports/) | 2010 | 16 | - | - | 783 | - | RGB | Sports (e.g., high jumping, diving) |
| [MSRAction3D](https://sites.google.com/view/wanqingli/data-sets/msr-action3d) | 2010 | 20 | 10 | 1 | 567 | Kinect v1 | Depth+3DJoints | Daily Activities (e.g., drinking, walking) |
| [CAD-60](https://cove.thecvf.com/datasets/37) | 2011 | 14 | 4 | - | 68 | Kinect v1 | RGB+Depth+3DJoints | Human performing activities (e.g., cleaning objects) |
| [HMDB51](https://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/) | 2011 | 51 | - | - | 6,766 | - | RGB | Human actions (e.g., jumping, running) |
| [MSRDailyActivity3D](https://sites.google.com/view/wanqingli/data-sets/msr-dailyactivity3d) | 2012 | 16 | 10 | 1 | 320 | Kinect v1 | RGB+Depth+3DJoints | Daily Activities (e.g., calling, playing game) |
| [UCF101](https://www.crcv.ucf.edu/data/UCF101.php) | 2012 | 101 | - | - | 13,320 | - | RGB | Body motion, Human-object interactions, sports etc. |
| [UTKinect-Action3D](https://cvrc.ece.utexas.edu/KinectDatasets/HOJ3D.html) | 2012 | 10 | 10 | 1 | 199 | Kinect v1 | RGB+Depth+3DJoints | Human actions (e.g., waving hands, pushing) |
| [MPII Cooking](https://ieeexplore.ieee.org/document/6247801) | 2012 | 64 | 12 | 1 | 3,748 | - | RGB | Cooking |
| [G3D-Gaming](http://velastin.dynu.com/G3D/G3D.html) | 2012 | 20 | 10 | 1 | - | Kinect v1 | RGB+Depth+3DJoints | Gaming scenario (e.g., defending, climbing) |
| [Berkeley MHAD](https://www.kaggle.com/datasets/dasmehdixtr/berkeley-multimodal-human-action-database) | 2013 | 11 | 12 | 4 | 660 | Multi-baseline stereo cameras | RGB+Depth+3DJoints+Accelerometer+Audio | Human actions (e.g., throwing, clapping hands) |
| [CAD-120](https://cove.thecvf.com/datasets/36) | 2013 | 10 | 4 | - | 120 | Kinect v1 | RGB+Depth+3DJoints | Human performing activities (e.g., picking objects) |
| [UCF50](https://www.crcv.ucf.edu/data/UCF50.php) | 2013 | 50 | - | - | 6676 | - | RGB | Body motion, Human-object interactions, sports etc. |
| [Florence3D-Action](https://www.micc.unifi.it/resources/datasets/florence-3d-actions-dataset/) | 2013 | 9 | 10 | 1 | 215 | Kinect v1 | RGB+Depth+3DJoints | Human actions (e.g., bowing, drinking) |
| [MSRActionPairs3D](https://ieeexplore.ieee.org/document/6618942) | 2013 | 12 | 10 | 1 | 360 | Kinect v1 | RGB+Depth+3DJoints | Human actions (e.g., picking up, putting down) |
| [Sports-1M](https://cs.stanford.edu/people/karpathy/deepvideo/) | 2014 | 487 | - | - | 1,000,000 | - | RGB | Sports (e.g., swimming, skiing) |
| [THUMOS14](https://www.crcv.ucf.edu/THUMOS14/home.html) | 2014 | 101 | - | - | 5,613 | - | RGB | Human Actions (e.g., making up, archery) |
| [Northwestern-UCLA](https://wangjiangb.github.io/my_data.html) | 2014 | 10 | 10 | 3 | 1494 | Kinect v1 | RGB+Depth+3DJoints | Human actions (e.g., dropping trash) |
| [UWA3D Multiview Activity](https://ieee-dataport.org/documents/uwa-3d-multiview-activity-ii-dataset) | 2014 | 30 | 10 | 1 | 701 | Kinect v1 | RGB+Depth+3DJoints | Daily Activities (e.g., holding head, walking) |
| [ActivityNet](http://activity-net.org/) | 2015 | 203 | - | - | 27,801 | - | RGB | Human actions (e.g., drawing, washing) |
| [MPII Cooking 2](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/human-activity-recognition/mpii-cooking-2-dataset/) | 2015 | 67 | 30 | 1 | 273 | Static camera | RGB | Cooking |
| [UWA3D Multiview Activity II](https://ieee-dataport.org/documents/uwa-3d-multiview-activity-ii-dataset) | 2015 | 30 | 9 | 4 | 1,070 | Kinect v1 | RGB+Depth+3DJoints | Daily Activities (e.g., waving head, jumping) |
| [SYSU 3D HOI](https://www.isee-ai.cn/~hujianfang/ProjectJOULE.html) | 2015 | 12 | 40 | - | 480 | Kinect v1 | RGB+Depth+3DJoints | Human-Object Interactions (e.g., sweeping the floor) |
| [NTU RGB+D](https://github.com/shahroudy/NTURGB-D) | 2016 | 60 | 40 | 80 | 56,880 | Kinect v2 | RGB+Depth+3DJoints | Daily actions, health-related actions etc. |
| [InfAR](https://www.sciencedirect.com/science/article/pii/S0925231216307044) | 2016 | 12 | 40 | - | 600 | Infrared camera | Infrared | Human actions (e.g., jogging) |
| [TSF](https://huggingface.co/datasets/Monash-University/monash_tsf) | 2016 | 2 | - | 1 | 44 | FLIR ONE | Infrared | Falls and normal activities |
| [Charades](https://prior.allenai.org/projects/charades) | 2016 | 157 | - | - | 66,500 | - | RGB+Flow | Indoor activities (e.g., cleaning) |
| [PKU-MMD I](https://www.icst.pku.edu.cn/struct/Projects/PKUMMD.html) | 2017 | 51 | 66 | 3 | 1,076 | Kinect v2 | RGB+Depth+Infrared+3DJoints | Human actions (e.g., walking) |
| [NfS](https://ci2cv.net/nfs/index.html) | 2017 | - | - | - | 100 | 240 FPS camera | RGB | Visual object tracking |
| [Kinetics-400](https://github.com/cvdfoundation/kinetics-dataset) | 2017 | 400 | - | - | 306,245 | - | RGB | Human-centered actions (e.g., playing instruments) |
| [Something-Something V1](https://github.com/open-mmlab/mmaction2/blob/main/tools/data/sthv1/README.md) | 2017 | 174 | - | - | 108,499 | - | RGB | Human performing actions with everyday objects |
| [Kinetics-skeleton](https://github.com/open-mmlab/mmskeleton/blob/master/doc/SKELETON_DATA.md) | 2017 | 400 | - | - | 260,232 | - | 2DJoints | Human-centered actions |
| [HACS](https://hacs.csail.mit.edu/) | 2017 | 200 | - | - | 1,500,000 | - | RGB+Flow | Human actions (e.g., dancing) |
| [Charades-Ego](https://prior.allenai.org/projects/charades-ego) | 2018 | 157 | 112 | 2 | 68,536 | Head-mounted+standard camera | RGB | Egocentric indoor activities |
| [AVA](https://research.google.com/ava/) | 2018 | 80 | - | - | 211,000 | - | RGB+Flow | Human actions (e.g., talking, sitting) |
| [Diving48](http://www.svcl.ucsd.edu/projects/resound/dataset.html) | 2018 | 48 | - | - | 18,404 | - | RGB+Flow | Diving actions |
| [Epic-Kitchens](https://epic-kitchens.github.io/2025) | 2018 | 149 | 32 | - | 39,594 | - | RGB+Flow | Cooking |
| [Something-Something V2](https://www.qualcomm.com/developer/software/something-something-v-2-dataset) | 2018 | 174 | - | - | 220,847 | - | RGB | Human performing actions with everyday objects |
| [MiT](http://moments.csail.mit.edu/) | 2018 | 339 | - | - | 1,000,000+ | - | RGB+Audio+Flow | Dynamic actions (e.g., human, animals) |
| [Kinetics-600](https://github.com/cvdfoundation/kinetics-dataset) | 2018 | 600 | - | - | 495,547 | - | RGB | Human-centered actions (e.g., playing instruments) |
| [NTU RGB+D 120](https://github.com/shahroudy/NTURGB-D) | 2019 | 120 | 106 | 155 | 114,480 | Kinect v2 | RGB+Depth+3DJoints+Infrared | Daily actions, health-related actions etc. |
| [IITR-IAR](https://www.sciencedirect.com/science/article/pii/S1350449519302762) | 2019 | 21 | 35 | - | 1,470 | FLIR T1020 | Infrared | Human actions (hugging, fighting) |
| [Kinetics-700](https://github.com/cvdfoundation/kinetics-dataset) | 2019 | 700 | - | - | 650,317 | - | RGB | Human-centered actions (e.g., playing instruments) |
| [HowTo100M](https://www.di.ens.fr/willow/research/howto100m/) | 2019 | 23,611 | - | - | 136,000,000 | - | RGB | Instructional videos (e.g., cooking) |
| [CATER](https://rohitgirdhar.github.io/CATER/) | 2019 | 301 | - | - | 5,500 | - | RGB | Compositional actions and temporal reasoning |
| [FineGym](https://sdolivia.github.io/FineGym/) | 2020 | 530 | - | - | 32,697 | - | RGB | Gymnasium videos (e.g., balance beam) |
| [PKU-MMD II](https://www.icst.pku.edu.cn/struct/Projects/PKUMMD.html) | 2020 | 41 | 13 | 3 | 1,009 | Kinect v2 | RGB+Depth+Infrared+3DJoints | Human actions (e.g., standing) |
| [EPIC-KITCHENS-100](https://epic-kitchens.github.io/2025) | 2020 | 4,053 | 37 | - | 89,977 | GoPro Hero7 Black | RGB+Flow | Cooking |
| [UAV-Human](https://github.com/SUTDCV/UAV-Human) | 2021 | 155 | 119 | - | 22,476 | UAV Camera | RGB+3DJoints | Human Actions (e.g., walking, jogging) |


</details>


## ❤️‍🔥❤️‍🔥❤️‍🔥 Contribution
We warmly invite everyone to contribute to this repository and help enhance its quality and scope. Feel free to submit pull requests to add new methods, datasets or other useful resources, as well as to correct any errors you discover. To ensure consistency, please format your pull requests using our tables' structures. We greatly appreciate your valuable contributions and support!
