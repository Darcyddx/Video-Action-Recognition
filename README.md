# Video-Action-Recognition

### 🔥🔥🔥[The Journey of Action Recognition]()✈️

> 👋👋👋 A collection of papers and resources related to Large Language Models in video domain🎞️. 
>
> 📌 More details please refer to our [paper](). 
>
> 🛠️ Please let us know if you find out a mistake or have any suggestions by e-mail: Xi.Ding1@anu.edu.au

### 📑 Citation

If you find our work useful for your research, please cite the following paper:

```bibtex
@article{dingjourney,
  title={The Journey of Action Recognition},
  author={Ding, Xi and Wang, Lei}
}
```
---


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

### Dynamic Skeletons-based Methods

<details>
<summary>Click to expand Table 7</summary>

| Model                                         | Venue        | Learning         | Dataset                                                                | Modality                                       | Code |
|-----------------------------------------------|--------------|------------------|------------------------------------------------------------------------|-----------------------------------------------|------|
| [Dynamic Skeletons]()                         | CVPR 2015    | Supervised       | MSRDailyActivity, CAD-60, SYSU 3D HOI                                    | Depth + Joint                                  | [GitHub]() |
| [HBRNN-L]()                                   | CVPR 2015    | Supervised       | MSRAction3D, Berkeley MHAD, HDM05                                       | Joint                                          | [GitHub]() |
| [Part-aware LSTM]()                           | CVPR 2016    | Supervised       | NTU RGB+D                                                               | RGB + Depth + Joint + Infrared                | [GitHub]() |
| [LARP-SO]()                                   | CVPR 2016    | Supervised       | Florence3D-Action, MSRActionPairs3D, G3D-Gaming                         | Joint                                          | [GitHub]() |
| [STA-LSTM]()                                  | AAAI 2017    | Supervised       | NTU RGB+D                                                               | Joint                                          | [GitHub]() |
| [LieNet]()                                    | CVPR 2017    | Supervised       | NTU RGB+D, HDM05, G3D-Gaming                                           | Joint + Bone                                   | [GitHub]() |
| [Two-Stream RNN]()                            | CVPR 2017    | Supervised       | NTU RGB+D                                                               | Joint                                          | [GitHub]() |
| [Ke et al.]()                                 | CVPR 2017    | Supervised       | NTU RGB+D                                                               | Joint                                          | [GitHub]() |
| [VA-LSTM]()                                   | ICCV 2017    | Supervised       | NTU RGB+D, SYSU 3D HOI                                                 | Joint                                          | [GitHub]() |
| [View Invariant]()                            | Pattern Recognit. 2017 | Supervised  | NTU RGB+D, Northwestern-UCLA, UWA3D Multiview Activity II, MSRC-12    | Joint                                          | [GitHub]() |
| [Two-Stream CNN]()                            | ICMEW 2017   | Supervised       | NTU RGB+D, PKU-MMD I                                                  | Joint + Skeleton motion                       | [GitHub]() |
| [LSTM-CNN]()                                  | ICMEW 2017   | Supervised       | NTU RGB+D                                                               | Joint                                          | [GitHub]() |
| [ST-LSTM+Trust Gate]()                        | TPAMI 2018   | Supervised       | NTU RGB+D, MSRAction3D, SYSU 3D HOI, Berkeley MHAD                     | Joint                                          | [GitHub]() |
| [ST-GCN]()                                    | AAAI 2018    | Supervised       | Kinetics-400, NTU RGB+D                                                | Joint                                          | [GitHub]() |
| [Tang et al.]()                               | CVPR 2018    | Reinforcement    | NTU RGB+D, SYSU 3D HOI, UTKinect-Action3D                              | Joint + Bone                                   | [GitHub]() |
| [AS-GCN]()                                    | CVPR 2019    | Supervised       | NTU RGB+D, Kinetics-400                                                | Joint + Bone                                   | [GitHub]() |
| [2s-AGCN]()                                   | CVPR 2019    | Fully-supervised | NTU RGB+D, Kinetics-skeleton                                           | Joint + Bone                                   | [GitHub]() |
| [DGNN]()                                      | CVPR 2019    | Supervised       | NTU RGB+D, Kinetics-skeleton                                           | Joint + Bone                                   | [GitHub]() |
| [EfficientGCN]()                              | ACM MM 2020  | Supervised       | NTU RGB+D, NTU RGB+D 120                                               | Joint + Velocity + Bone                        | [GitHub]() |
| [RA-GCN]()                                    | TCSVT 2020   | Supervised       | NTU RGB+D, NTU RGB+D 120                                               | Joint + Bone                                   | [GitHub]() |
| [Shift-GCN]()                                 | CVPR 2020    | Supervised       | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                            | Joint + Bone                                   | [GitHub]() |
| [MS-G3D]()                                    | CVPR 2020    | Supervised       | NTU RGB+D 60, NTU RGB+D 120, Kinetics-skeleton                         | Joint + Bone                                   | [GitHub]() |
| [DSTA-Net]()                                  | ACCV 2020    | Supervised       | NTU RGB+D, NTU RGB+D 120                                               | Joint + Bone                                   | [GitHub]() |
| [SCK+DCK / SCK$\oplus$+DCK$\oplus$]()          | TPAMI 2020   | Supervised       | UTKinect-Action3D, Florence3D-Action, MSRAction3D, NTU RGB+D 60, Kinetics-400, HMDB51, MPII Cooking | Joint | [GitHub]() |
| [CTR-GCN]()                                   | ICCV 2021    | Supervised       | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                            | Joint + Bone                                   | [GitHub]() |
| [FGCN]()                                      | TIP 2022     | Supervised       | NTU RGB+D, NTU RGB+D120, Northwestern-UCLA                            | Joint + Bone                                   | [GitHub]() |
| [AGE-Ens]()                                   | TNNLS 2022   | Supervised       | NTU RGB+D, NTU RGB+D 120                                               | Joint + Bone                                   | [GitHub]() |
| [PoseConv3D]()                                | CVPR 2022    | Supervised       | Kinetics-400, UCF101, HMDB51                                           | Joint + Bone + RGB                             | [GitHub]() |
| [InfoGCN]()                                   | CVPR 2022    | Supervised       | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                            | Joint + Bone                                   | [GitHub]() |
| [DASTM]()                                     | ECCV 2022    | Few-shot         | NTU RGB+D 120, Kinetics-skeleton                                        | Joint + Bone                                   | [GitHub]() |
| [Uncertainty-DTW]()                           | ECCV 2022    | Supervised/Unsupervised few-shot | NTU RGB+D, NTU RGB+D 120, Kinetics-skeleton                          | Skeleton sequences                             | [GitHub]() |
| [TranSkeleton]()                              | TCSVT 2023   | Supervised       | NTU RGB+D, NTU RGB+D 120                                               | Joint + Bone                                   | [GitHub]() |
| [HiCo]()                                      | AAAI 2023    | Unsupervised + Contrastive | NTU RGB+D, NTU RGB+D 120, PKU-MMD I, PKU MMD II                        | Joint                                          | [GitHub]() |
| [FR-Head]()                                   | CVPR 2023    | Supervised + Contrastive | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                             | Joint + Bone                                    | [GitHub]() |
| [3Mformer]()                                  | CVPR 2023    | Supervised             | NTU RGB+D, NTU RGB+D 120, Kinetics-400, Northwestern-UCLA              | Joint + Hyper-edge                              | [GitHub]() |
| [HYSP]()                                      | ICLR 2023    | Self-supervised         | NTU RGB+D, NTU RGB+D 120, PKU-MMD I                                     | Joint                                          | [GitHub]() |
| [PAINet]()                                    | ICCV 2023    | Few-shot               | NTU RGB+D 120, Kinetics-skeleton                                        | Joint + Bone                                    | [GitHub]() |
| [PCM\textsuperscript{3}]()                    | ACM MM 2023  | Self-supervised         | NTU RGB+D, NTU RGB+D 120, PKU-MMD I                                     | Joint + Bone + Motion                          | [GitHub]() |
| [Stream-GCN]()                                | arXiv 2023   | Supervised             | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                             | Joint + Bone                                    | [GitHub]() |
| [SkeletonGCL]()                               | arXiv 2023   | Self-supervised         | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                             | Joint + Bone                                    | [GitHub]() |
| [DSCNet]()                                    | ESWA 2024    | Supervised + Multimodal | NTU RGB+D, NTU RGB+D 120, PKU-MMD I, UAV-Human, IKEA ASM, Northwestern-UCLA | RGB + Joint + Bone                             | [GitHub]() |
| [Skeleton-OOD]()                              | Neurocomputing 2024 | Supervised         | NTU RGB+D, NTU RGB+D 120, Kinetics-400                                 | Joint                                          | [GitHub]() |
| [ViA]()                                       | IJCV 2024    | Self-supervised         | Posetics, NTU RGB+D, NTU RGB+D 120, Toyota Smarthome, UAV-Human, Penn Action | Joint + Motion                                  | [GitHub]() |
| [DeGCN]()                                     | TIP 2024     | Supervised             | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                             | Joint + Bone                                    | [GitHub]() |
| [Js-SaPR-GCN]()                               | TCSVT 2024   | Supervised             | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                             | Joint + Bone + Motion                          | [GitHub]() |
| [BlockGCN]()                                  | CVPR 2024    | Supervised             | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                             | Joint + Bone + Motion                          | [GitHub]() |
| [JEANIE]()                                    | IJCV 2024    | Supervised/Unsupervised few-shot | NTU RGB+D, NTU RGB+D 120, Kinetics-skeleton, MSRAction3D, UWA3D Multiview Activity | Skeleton sequences                             | [GitHub]() |
| [SA-DVAE]()                                   | arXiv 2024   | Zero-shot              | NTU RGB+D, NTU RGB+D 120, PKU-MMD I                                    | Joint                                          | [GitHub]() |
| [ProtoGCN]()                                  | ArXiv 2024   | Self-supervised + Prototype | NTU RGB+D, NTU RGB+D 120, Kinetics-skeleton, FineGYM                   | Joint                                          | [GitHub]() |
| [HSIC-based]()                                | arXiv 2024   | Supervised             | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA                             | Joint + Bone                                    | [GitHub]() |
| [USDRL]()                                     | AAAI 2025    | Self-supervised         | NTU RGB+D, NTU RGB+D 120, PKU-MMD I, PKU-MMD II                        | Joint + Bone + Motion                          | [GitHub]() |


</details>

### Depth-based Methods

<details>
<summary>Click to expand Table 8</summary>

| Model                                          | Venue                       | Learning       | Dataset                                                                | Modality                                       | Code |
|------------------------------------------------|-----------------------------|----------------|------------------------------------------------------------------------|-----------------------------------------------|------|
| [HON4D]()                                      | CVPR 2013                   | Supervised     | MSRAction3D, MSRDailyActivity3D, MSRActionPairs3D                       | Depth                                         | [GitHub]() |
| [HOPC]()                                       | ECCV 2014                   | Supervised     | MSRAction3D, MSRActionPairs3D, UWA3D Multiview Activity                 | Depth + Point cloud                           | [GitHub]() |
| [Wang et al.]()                                | Trans. Human-Mach. Syst. 2016| Supervised     | MSRAction3D, MSRDailyActivity3D, UTKinect-Action3D                      | Depth                                         | [GitHub]() |
| [Rahmani et al.]()                             | CVPR 2016                   | Supervised     | Northwestern-UCLA, UWA3D Multiview Activity II                          | Depth                                         | [GitHub]() |
| [S\textsuperscript{2}DDI]()                    | ICCVW 2017                  | Supervised     | MSRAction3D, G3D-Gaming, MSRDailyActivity3D, SYSU 3D HOI, UTD-MHAD      | Depth                                         | [GitHub]() |
| [Wang et al.]()                                | TMM 2018                    | Supervised     | NTU RGB+D                                                               | Depth                                         | [GitHub]() |
| [MVDI]()                                       | Inf. Sci. 2018              | Supervised     | NTU RGB+D, Northwestern-UCLA, UWA3D Multiview Activity II              | Depth                                         | [GitHub]() |
| [3DFCNN]()                                     | Multimed. Tools Appl. 2020  | Supervised     | NTU RGB+D, Northwestern-UCLA, UWA3D Multiview Activity II              | Depth                                         | [GitHub]() |
| [Liu et al.]()                                 | ICASSP 2017                 | Supervised     | MSRAction3D, DHA                                                        | Depth                                         | [GitHub]() |
| [Dhiman et al.]()                              | TIP 2020                    | Supervised     | NTU RGB-D, UWA3D Multiview Activity II, Northwestern-UCLA               | RGB + Depth                                   | [GitHub]() |
| [Stateful ConvLSTM]()                          | arXiv 2020                  | Supervised     | NTU RGB+D                                                               | Depth                                         | [GitHub]() |
| [DEAR]()                                       | arXiv 2024                  | Supervised     | Something-Something V2                                                  | RGB + Depth                                   | [GitHub]() |

</details>

### Infrared-based Methods

<details>
<summary>Click to expand Table 9</summary>

| Model                                          | Venue                        | Learning       | Dataset                                                               | Modality                                          | Code |
|------------------------------------------------|------------------------------|----------------|-----------------------------------------------------------------------|--------------------------------------------------|------|
| [Gao et al.]()                                  | Neurocomputing 2016          | Supervised     | InfAR                                                                 | Infrared + Optical flow                          | [GitHub]() |
| [Jiang et al.]()                               | CVPRW 2017                   | Supervised     | InfAR                                                                 | Infrared + Optical flow                          | [GitHub]() |
| [Kawashima et al.]()                           | AVSS 2017                    | Supervised     | Custom Dataset                                                        | Infrared                                         | [GitHub]() |
| [Shah et al.]()                                | SPIE 2018                    | Supervised     | Custom IR Dataset                                                     | Infrared                                         | [GitHub]() |
| [TSTDDs]()                                     | SPL 2018                     | Supervised     | InfAR, NTU RGB+D                                                      | Infrared + Optical flow                          | [GitHub]() |
| [Akula et al.]()                               | CSR 2018                     | Supervised     | Custom IR Dataset                                                     | Infrared                                         | [GitHub]() |
| [Imran et al.]()                               | Infrared Phys. Technol. 2019 | Supervised     | InfAR, IITR-IAR                                                       | Infrared + Optical flow                          | [GitHub]() |
| [Meglouli et al.]()                            | CEAI 2019                     | Supervised     | InfAR                                                                 | Infrared + Optical flow                          | [GitHub]() |
| [Mehta et al.]()                               | ICPR 2020                     | Adversarial    | TSF                                                                   | Infrared + Optical flow                          | [GitHub]() |

</details>

### Point Cloud Methods

<details>
<summary>Click to expand Table 10</summary>

| Model                                          | Venue                       | Learning       | Dataset                                                                | Modality                                       | Code |
|------------------------------------------------|-----------------------------|----------------|------------------------------------------------------------------------|-----------------------------------------------|------|
| [MeteorNet]()                                   | ICCV 2019                   | Supervised     | MSRAction3D                                                            | Point cloud                                    | [GitHub]() |
| [PointLSTM]()                                  | CVPR 2020                   | Supervised     | MSRAction3D                                                            | Point cloud                                    | [GitHub]() |
| [3DV-PointNet++]()                              | CVPR 2020                   | Supervised     | NTU RGB+D, NTU RGB+D 120, Northwestern-UCLA, UWA3D Multiview Activity II | Depth                                          | [GitHub]() |
| [ASTA3DConv]()                                 | Trans. Instrum. Meas. 2020   | Supervised     | MSRAction3D                                                            | Point cloud                                    | [GitHub]() |
| [Wang et al.](https://arxiv.org/abs/2007.10442)  | WACV 2021                   | Self-supervised| NTU RGB+D, NTU-PCL, MSRAction3D                                         | Point cloud                                    | [GitHub]() |
| [P4Transformer]()                               | CVPR 2021                   | Supervised     | MSRAction3D, NTU RGB+D, NTU RGB+D 120                                  | Point cloud                                    | [GitHub]() |
| [PSTNet]()                                      | arXiv 2021                   | Supervised     | MSRAction3D, NTU RGB+D, NTU RGB+D 120                                  | Point cloud                                    | [GitHub]() |
| [PST\textsuperscript{2}]()                      | WACV 2022                   | Supervised     | MSRAction3D                                                            | Point cloud                                    | [GitHub]() |
| [MaST-Pre]()                                    | ICCV 2023                   | Self-supervised| MSRAction3D, NTU RGB+D                                                 | Point cloud                                    | [GitHub]() |
| [PointCPSC]()                                   | ICCV 2023                   | Self-supervised| MSRAction3D, NTU RGB+D                                                 | Point cloud                                    | [GitHub]() |
| [3DInAction]()                                  | CVPR 2024                   | Supervised     | MSRAction3D                                                            | Point cloud                                    | [GitHub]() |
| [KAN-HyperpointNet]()                           | arXiv 2024                   | Supervised     | NTU RGB+D, MSRAction3D                                                 | Point cloud                                    | [GitHub]() |

</details>


### Text/Audio Methods

<details>
<summary>Click to expand Table 11</summary>

| Model                                          | Venue                       | Learning       | Dataset                                                                | Modality                                       | Code |
|------------------------------------------------|-----------------------------|----------------|------------------------------------------------------------------------|-----------------------------------------------|------|
| [CPD]()                                        | arXiv 2020                  | Self-supervised| Kinetics-400, HMDB51, UCF101                                           | RGB + Text                                    | [GitHub]() |
| [G-Blend]()                                    | CVPR 2020                   | Multi-task     | Kinetics-400, Mini-Sports, EPIC-Kitchen                                | RGB + Optical flow + Audio                    | [GitHub]() |
| [MIL-NCE]()                                    | CVPR 2020                   | Self-supervised| HowTo100M, HMDB51, UCF101                                             | RGB + Text                                    | [GitHub]() |
| [MMV]()                                        | NeurIPS 2020                | Self-supervised| UCF101, HMDB51, Kinetics-600                                           | RGB + Audio + Text                            | [GitHub]() |
| [VIMPAC]()                                     | arXiv 2021                  | Self-supervised| Something-Something V2, Diving48, UCF101, HMDB51                       | RGB + Text                                    | [GitHub]() |
| [InternVideo]()                                | CVPR 2023                   | Self-supervised| Kinetics-400, Kinetics-600, Kinetics-700, Something-Something V1, V2, ActivityNet, HACS, HMDB51 | RGB + Text                                    | [GitHub]() |
| [Side4Video]()                                 | arXiv 2023                  | Self-supervised| Something-Something V1, Something-Something V2, Kinetics-400           | RGB + Text                                    | [GitHub]() |
| [EZ-CLIP]()                                    | arXiv 2024                  | Zero-shot      | Kinetics-400, HMDB51, UCF101, Something-Something V2                    | RGB + Text                                    | [GitHub]() |
| [SATA]()                                       | arXiv 2024                  | Zero-shot      | UCF101, HMDB51                                                       | RGB + Text                                    | [GitHub]() |
| [TC-CLIP]()                                    | ECCV 2024                   | Zero-shot/Few-shot/Fully-supervised | HMDB51, UCF101, Kinetics-400, Something-Something V2                  | RGB + Text                                    | [GitHub]() |
| [InternVideo2]()                               | arXiv 2024                  | Self-supervised + Multimodal | Kinetics-400, Kinetics-600, Kinetics-700, MiT, Something-Something V2, ActivityNet, HACS, Charades, HMDB51 | RGB + Audio + Text                            | [GitHub]() |
| [OmniViD]()                                    | CVPR 2024                   | Supervised     | Kinetics-400, Something-Something V2, UCF101, HMDB51                    | RGB + Text                                    | [GitHub]() |
| [LoCATe-GAT]()                                 | TETCI 2024                  | Zero-shot      | UCF101, HMDB51, ActivityNet, Kinetics-400                              | RGB + Text                                    | [GitHub]() |
| [STDD]()                                       | arXiv 2024                  | Zero-shot      | Kinetics-600, UCF101, HMDB51                                           | RGB + Text                                    | [GitHub]() |

</details>

