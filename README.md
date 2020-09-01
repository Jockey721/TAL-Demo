# Temporal Action Localization Demo

<div align=center>| Detecting the PoleVault action segments on the timeline of video |
<div align=center><img src="Thumos14Demo\PoleVault-Demo.gif" style="zoom:200%;" width="480" /> 
<div align=center>| Detecting the GolfSwing action segments on the timeline of video |
<div align=center><img src="Thumos14Demo\GolfSwing-Demo.gif" style="zoom:200%;" width="480"/> 


<div align=left><br/>

# Dataset

  
|      Dataset      | Video Number | train | validation | test | instances |class |
| :---------------: | :----------: | :---: | :--------: | :--: | :--------:|:---: |
|      THUMOS14     |    413       |   -   |    200     | 213  |   6,363   | 20   |
| ActivityNet-v1.3  |     19994    | 10,024|    4,926   | 5,044|   30791   | 200  |


# Experimental Results
### THUMOS14
|                     Method                      |  Conference   |   IoU@0.1   |   IoU@0.2   |   IoU@0.3   |   IoU@0.4   |   IoU@0.5   |   IoU@0.6   |   IoU@0.7   |
| :---------------------------------------------: | :-----------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: |
| <span id = "1192">[DBS](#2192)</span>           |   AAAI-2019   |    56.7     |    54.7     |    50.6     |    43.1     |    34.3     |    24.4     |    14.7     |
| <span id = "1184">[BSN](#2184)</span>           |   ECCV-2018   |      -      |      -      |    53.5     |    45.0     |    36.9     |    28.4     |    20.0     |
| <span id = "1201">[AGCN](#2201)</span>          |   AAAI-2020   |    59.3     |    59.6     |    57.1     |    51.6     |    38.6     |    28.9     |     17.0    |
| <span id = "1193">[GTAN](#2193)</span>          |   CVPR-2019   |    69.1     |    63.7     |    57.8     |    47.2     |    38.8     |      -      |      -      |
| <span id = "1194">[BMN](#2194)</span>           |   ICCV-2019   |      -      |      -      |    56.0     |    47.4     |    38.8     |    29.7     |    20.5     |
| <span id = "1204">[DBG](#2204)</span>           |   AAAI-2020   |      -      |      -      |    57.8     |    49.4     |    39.8     |    30.2     |    21.7     |
| <span id = "1185">[TAL-Net](#2185)</span>       |   CVPR-2018   |    59.8     |    57.1     |    53.2     |    48.5     |    42.8     |    33.8     |    20.8     |
| <span id = "1196">[PGCN](#2196)</span>          |   ICCV-2019   |    69.5     |    67.8     |    63.6     |    57.8     |    49.1     |      -      |      -      |
| <span id = "1202">[PBRNet](#2202)</span>        |   AAAI-2020   |      -      |      -      |    58.5     |    54.6     |    51.3     |    41.8     |     29.5    |
| <span id = "1203">[G-TAD](#2203)</span>         |   CVPR-2020   |      -      |      -      |    66.4     |    60.4     |    51.6     |    37.6     |     22.9    |
| our method                                      |   -           |     74.5    |     72.3    |    68.6     |    62.8     |    54.4  
|    41.4     |     27.8    |
### ActivityNet-v1.3
|         Method         |  Conference   |   IoU@0.5   |   IoU@0.75   |   IoU@0.95   |   IoU@Avg   |
| :--------------------: | :-----------: | :---------: | :----------: | :----------: | :---------: |
| [AGCN](#2201)          |   AAAI-2020   |    30.4     |      -       |      -       |      -      |
| [TAL-Net](#2185)       |   CVPR-2018   |    38.23    |    18.30     |     1.30     |    20.22    |
| [DBS](#2192)           |   CVPR-2019   |    43.2     |    25.8      |     6.1      |    26.1     |
| [PGCN](#2196)          |   ICCV-2019   |    42.90    |    28.14     |     2.47     |    26.99    |
| [BSN](#2184)           |   ECCV-2018   |    46.45    |    29.96     |     8.02     |    30.03    |
| [BMN](#2194)           |   ICCV-2019   |    50.07    |    34.78     |     8.29     |    33.85    |
| [G-TAD](#2203)         |   CVPR-2020   |    50.36    |    34.60     |     9.02     |    34.09    |
| [GTAN](#2193)          |   CVPR-2019   |    52.61    |    34.14     |     8.91     |    34.31    |
| [PBRNet](#2202)        |   AAAI-2020   |    53.96    |    34.97     |     8.98     |    35.01    |

# Related Papers
### <span id = "tal-2020"> 2020 </span>

- <span id = "2204">[[DBG]](#1204)</span> [**Fast Learning of Temporal Action Proposal via Dense Boundary Generator**](https://arxiv.org/pdf/1911.04127) - Chunming Lin et al, `AAAI 2020`. [[code]](<https://github.com/Tencent/ActionDetection-DBG>)
- <span id = "2203">[[G-TAD]](#1203)</span> [**G-TAD: Sub-Graph Localization for Temporal Action Detection**](https://arxiv.org/abs/1911.11462) - Mengmeng Xu et al, `CVPR 2020`. [[code]](<https://github.com/frostinassiky/gtad>)
- <span id = "2202">[[PBRNet]](#1202)</span> [**Progressive Boundary Refinement Network for Temporal Action Detection**](https://aaai.org/Papers/AAAI/2020GB/AAAI-LiuQ.4870.pdf) - Qinying Liu et al, `AAAI 2020`.
- <span id = "2201">[[AGCN]](#1201)</span> [**Graph Attention based Proposal 3D ConvNets for Action Detection**](https://www.aaai.org/Papers/AAAI/2020GB/AAAI-LiJ.1424.pdf) - Jun Li et al, `AAAI 2020`.


### <span id = "tal-2019"> 2019 </span>

- <span id = "2196">[[PGCN]](#1196)</span> [**Graph Convolutional Networks for Temporal Action Localization**](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zeng_Graph_Convolutional_Networks_for_Temporal_Action_Localization_ICCV_2019_paper.pdf) - Runhao Zeng et al, `ICCV 2019`. [[code]](<https://github.com/Alvin-Zeng/PGCN>)
- <span id = "2195">[[RAM]](#1195)</span> [**Relation Attention for Temporal Action Localization**](https://ieeexplore.ieee.org/document/8933113) - Peihao Chen et al, `TMM 2019`. 
- <span id = "2194">[[BMN]](#1194)</span> [**BMN: Boundary-Matching Network for Temporal Action Proposal Generation**](http://openaccess.thecvf.com/content_ICCV_2019/papers/Lin_BMN_Boundary-Matching_Network_for_Temporal_Action_Proposal_Generation_ICCV_2019_paper.pdf) - Tianwei Lin et al, `ICCV 2019`.
- <span id = "2193">[[GTAN]](#1193)</span> [**Gaussian Temporal Awareness Networks for Action Localization**](https://arxiv.org/abs/1909.03877) - Fuchen Long et al, `CVPR 2019`.
- <span id = "2192">[[DBS]](#1192)</span> [**Video Imprint Segmentation for Temporal Action Detection in Untrimmed Videos**](https://www.aaai.org/ojs/index.php/AAAI/article/view/4846) - Zhanning Gao et al, `AAAI 2019`.
- <span id = "2191">[[C-TCN]](#1191)</span> [**Deep Concept-wise Temporal Convolutional Networks for Action Localization**](https://arxiv.org/abs/1908.09442) - Xin Li et al, `arXiv 2019`.
