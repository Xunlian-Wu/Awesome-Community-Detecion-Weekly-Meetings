# Awesome-Community-Detecion-Weekly-Meetings

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) ![GitHub stars](https://img.shields.io/github/stars/Xunlian-Wu/Awesome-Community-Detecion-Weekly-Meetings?color=yellow&label=Stars) ![GitHub forks](https://img.shields.io/github/forks/Xunlian-Wu/Awesome-Community-Detecion-Weekly-Meetings?color=blue&label=Forks) 

Welcome to the **Awesome Community Detection** repository! This is a curated collection of resources, papers, and methods related to **Community Detection** in complex networks. Community detection, also known as graph clustering, is a crucial task in network science that aims to uncover modular structures in graphs representing real-world systems, such as social networks, biological networks, and communication networks.

This repository serves as a central hub for resources discussed in our weekly research group meetings and is continuously updated with new methods and papers in the field of community detection.

---

## 📚 **Contents**

- [Papers](#papers)  
  - [Surveys](#surveys)  
  - [Deep Learning-based Methods](#deep-learning-based-methods)  
    - [Reconstructive Deep Graph Clustering](#reconstructive-deep-graph-clustering)  
    - [Adversarial Deep Graph Clustering](#adversarial-deep-graph-clustering)  
    - [Contrastive Deep Graph Clustering](#contrastive-deep-graph-clustering)  
  - [Spectral Methods](#spectral-methods)  
  - [Label Propagation](#label-propagation)  
  - [Modularity Optimization](#modularity-optimization)  
  - [Stochastic Block Models](#stochastic-block-models)  
  - [Nonnegative Matrix Factorization](#nonnegative-matrix-factorization)  
  - [Other Methods](#other-methods)  
  - [Community Detection with Unknown Cluster Number](#community-detection-with-unknown-cluster-number)  
  - [Overlapping Community Detection](#overlapping-community-detection)  
  - [Temporal Community Detection](#temporal-community-detection)  
  - [Attribute-Missing Community Detection](#attribute-missing-community-detection)  
  - [Multi-layer Community Detection](#multi-layer-community-detection)
  - [Multi-view Graph Clustering](#multi-view-graph-clustering)  
- [Weekly Paper Presentations](#weekly-paper-presentations)
- [Useful Libraries](#useful-libraries)
- [References](#references)

---

## <a name="papers"></a> 📑 Papers

### Surveys

| Year | Title                                                        |       CA        |                       Institution                        | **Venue** |                            Paper                             |                             Code                             |
| :--: | :----------------------------------------------------------- | :-------------: | :------------------------------------------------------: | :-------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024 | **Advanced Graph Clustering Methods: A Comprehensive and In-Depth Analysis** | Timothé Watteau |               UTBM, Energy and IT Division               |  *arXiv*  |           [Link](https://arxiv.org/abs/2407.09055)           | [Link](https://github.com/timothewt/AdvancedGraphClustering) |
| 2023 | **An Overview of Advanced Deep Graph Node Clustering**       |   William Zhu   | University of Electronic Science and Technology of China |  *TCSS*   | [Link](https://ieeexplore.ieee.org/abstract/document/10049408/) |                              --                              |
| 2022 | **A Survey of Deep Graph Clustering: Taxonomy, Challenge, Application, and Open Resource** |   Xinwang Liu   |        National University of Defense Technology         |  *arXiv*  |           [Link](https://arxiv.org/abs/2211.12875)           | [Link](https://github.com/yueliu1999/Awesome-Deep-Graph-Clustering) |
| 2022 | **A Comprehensive Survey on Community Detection with Deep Learning** |     Jia Wu      |                   Macquarie University                   |  *TNNLS*  | [Link](https://arxiv.org/pdf/2105.12584.pdf?ref=https://githubhelp.com) |                              --                              |
| 2021 | **A survey of community detection approaches: From statistical modeling to deep learning** |  Pengfei Jiao   |                    Tianjin University                    |  *TKDE*   | [Link](https://ieeexplore.ieee.org/abstract/document/9511798/) |                              --                              |

### Deep Learning-based Methods

#### Reconstructive Deep Graph Clustering

| Year | Title                                                        |   CA   |                    Institution                     | **Venue** |                            Paper                             |                     Code                     |
| :--: | :----------------------------------------------------------- | :----: | :------------------------------------------------: | :-------: | :----------------------------------------------------------: | :------------------------------------------: |
| 2023 | **Wiener Graph Deconvolutional Network Improves Graph Self-Supervised Learning** | Jia Li | The Hong Kong University of Science and Technology |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/25870/25642) | [Link](https://github.com/jcheng66/WGDN.git) |

#### Adversarial Deep Graph Clustering

| Year | Title       |  CA  | Institution |  **Venue**   |   Paper   |   Code    |
| :--: | :---------- | :--: | :---------: | :----------: | :-------: | :-------: |
| 2021 | Paper Title |      | University  | Journal Name | [Link](#) | [Link](#) |

#### Contrastive Deep Graph Clustering

| Year | Title                                                        |       CA       |                     Institution                     | **Venue** |                            Paper                             |                         Code                          |
| :--: | :----------------------------------------------------------- | :------------: | :-------------------------------------------------: | :-------: | :----------------------------------------------------------: | :---------------------------------------------------: |
| 2024 | **Deep Contrastive Graph Learning with Clustering-Oriented Guidance** |   Xuelong Li   |        Northwestern Polytechnical University        |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/download/29016/29927) |  [Link](https://github.com/drongwbc/DCGL-AAAI24.git)  |
| 2023 | **Community-Aware Efficient Graph Contrastive Learning via Personalized Self-Training** |  Yuecheng Li   |               Sun Yat-Sen University                |  *arXiv*  |           [Link](https://arxiv.org/pdf/2311.11073)           |                          --                           |
| 2023 | **Cluster-guided Contrastive Graph Clustering Network**      |  Xihong Yang   | UniversityNational University of Defense Technology |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/download/26285/26057) |  [Link](https://github.com/xihongyang1999/CCGC.git)   |
| 2023 | **A Contrastive Variational Graph Auto-Encoder** **for Node Clustering** | Nairouz Mrabah |                University of Quebec                 |  *arXiv*  |           [Link](https://arxiv.org/pdf/2312.16830)           |    [Link](https://github.com/nairouz/CVGAE_PR.git)    |
| 2023 | **CONVERT: Contrastive Graph Clustering with Reliable Augmentation** |  Xinwang Liu   |           National University of Defense            |  *arXiv*  |           [Link](https://arxiv.org/pdf/2308.08963)           | [Link](https://github.com/xihongyang1999/CONVERT.git) |

### Spectral Methods

| Year | Title       |  CA  | Institution |  **Venue**   |   Paper   |   Code    |
| :--: | :---------- | :--: | :---------: | :----------: | :-------: | :-------: |
| 2021 | Paper Title |      | University  | Journal Name | [Link](#) | [Link](#) |

### Label Propagation

| Year | Title                                                        |         CA         |      Institution       | **Venue** |                            Paper                             |                     Code                      |
| :--: | :----------------------------------------------------------- | :----------------: | :--------------------: | :-------: | :----------------------------------------------------------: | :-------------------------------------------: |
| 2023 | **Local Graph Clustering with Noisy Labels**                 | Artur Back de Luca | University of Waterloo |  *arXiv*  |           [Link](https://arxiv.org/abs/2310.08031)           |                      --                       |
| 2022 | **Self-consistent Contrastive Attributed Graph Clustering with Pseudo-label Prompt** |      Wei Xia       |   Xidian University    |  *IEEE*   | [Link](https://ieeexplore.ieee.org/abstract/document/9914670) | [Link](https://github.com/xdweixia/SCAGC.git) |

### Modularity Optimization

| Year | Title                                                        |       CA       |               Institution               | **Venue** |                            Paper                             | Code |
| :--: | :----------------------------------------------------------- | :------------: | :-------------------------------------: | :-------: | :----------------------------------------------------------: | :--: |
| 2024 | **Attributed Graph Clustering via Coarsening with Modularity** | Samarth Bhatia |       Indian Institute of Science       |  *ICLR*   |       [Link](https://openreview.net/pdf?id=ukmh3mWFf0)       |  --  |
| 2023 | **DGCLUSTER: A Neural Framework for Attributed Graph Clustering via Modularity Maximization** |   Mert Kosan   | University of California, Santa Barbara |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/28983/29868) |  --  |

### Stochastic Block Models

| Year | Title       |  CA  | Institution |  **Venue**   |   Paper   |   Code    |
| :--: | :---------- | :--: | :---------: | :----------: | :-------: | :-------: |
| 2021 | Paper Title |      | University  | Journal Name | [Link](#) | [Link](#) |

### **Nonnegative** Matrix Factorization

| Year | Title                                                        |     CA     |      Institution       | **Venue** |                            Paper                             |                           Code                           |
| :--: | :----------------------------------------------------------- | :--------: | :--------------------: | :-------: | :----------------------------------------------------------: | :------------------------------------------------------: |
| 2024 | **Contrastive Deep Nonnegative Matrix Factorization For Community Detection** | Chuan Chen | Sun Yat-sen University |  *arXiv*  | [Link](https://ieeexplore.ieee.org/abstract/document/10446107) |        [Link](https://github.com/6lyc/CDNMF.git)         |
| 2024 | **Community detection in attributed networks via adaptive deep nonnegative matrix factorization** | Chaobo He  |   South China Normal   |   *NCA*   | [Link](https://link.springer.com/article/10.1007/s00521-023-09066-y) |      [Link](https://github.com/GDM-SCNU/ADNMF.git)       |
| 2018 | **Deep Autoencoder-like Nonnegative Matrix Factorization for Community Detection** | Fanghua Ye | Sun Yat-sen University |  *CIKM*   | [Link](https://www.researchgate.net/profile/Chuan-Chen-11/publication/328439632_Deep_Autoencoder-like_Nonnegative_Matrix_Factorization_for_Community_Detection/links/5d7dc4b3a6fdcc2f0f6fbf3a/Deep-Autoencoder-like-Nonnegative-Matrix-Factorization-for-Community-Detection.pdf) | [Link](https://github.com/benedekrozemberczki/DANMF.git) |

### Other Methods

| Year | Title                                                        |          CA           |                  Institution                  | **Venue** |                            Paper                             | Code |
| :--: | :----------------------------------------------------------- | :-------------------: | :-------------------------------------------: | :-------: | :----------------------------------------------------------: | :--: |
| 2024 | **A Differentially Private Clustering Algorithm for Well-Clustered Graphs** |       Pan Peng        | University of Science and Technology of China |  *arXiv*  |           [Link](https://arxiv.org/pdf/2403.14332)           |  --  |
| 2024 | **Dual Fusion AutoEncoder for Graph Clustering**             |      Yuanchi Ma       |          University of Pennsylvania           |  *ICLR*   |       [Link](https://openreview.net/pdf?id=VTdGLgmQQM)       |  --  |
| 2024 | **Graph Decoding via Generalized Random Dot Product Graph**  | Alvaro Ciudad Serrano |                      --                       |  *ICLR*   |       [Link](https://openreview.net/pdf?id=AxYTFpdlvj)       |  --  |
| 2024 | **Every Node is Different: Dynamically Fusing Self-Supervised Tasks for Attributed Graph Clustering** |        Yu Wang        |              Tianjin University               |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/29664/31133) |  --  |
| 2023 | **The projection method: a unified formalism for community detection** |    Martijn Gösgens    |      Eindhoven University of Technology       |  *arXiv*  | [Link](https://www.frontiersin.org/articles/10.3389/fcpxs.2024.1331320/pdf) |  --  |
| 2023 | **Multi-class Graph Clustering via Approximated Effective *p*-Resistance** |      Shota Saito      |           University College London           |  *PMLR*   | [Link](https://proceedings.mlr.press/v202/saito23a/saito23a.pdf) |  --  |

### Community Detection with Unknown Cluster Number

| Year | Title                                                        |     CA     |        Institution         | **Venue** |                  Paper                   | Code |
| :--: | :----------------------------------------------------------- | :--------: | :------------------------: | :-------: | :--------------------------------------: | :--: |
| 2024 | **Masked AutoEncoder for Graph Clustering without Pre-defined Cluster Number k** | Yuanchi Ma | University of Pennsylvania |  *arXiv*  | [Link](https://arxiv.org/pdf/2401.04741) |  --  |

### Overlapping Community Detection

| Year | Title       |  CA  | Institution |  **Venue**   |   Paper   |   Code    |
| :--: | :---------- | :--: | :---------: | :----------: | :-------: | :-------: |
| 2021 | Paper Title |      | University  | Journal Name | [Link](#) | [Link](#) |

### Temporal Community Detection

| Year | Title                              |     CA      |                Institution                | **Venue** |                  Paper                   |                             Code                             |
| :--: | :--------------------------------- | :---------: | :---------------------------------------: | :-------: | :--------------------------------------: | :----------------------------------------------------------: |
| 2024 | **Deep Temporal Graph Clustering** | Xinwang Liu | National University of Defense Technology |  *arXiv*  | [Link](https://arxiv.org/pdf/2305.10738) | [Link](https://github.com/MGitHubL/Deep-Temporal-Graph-Clustering.git) |

### Attribute-Missing Community Detection

| Year | Title       |  CA  | Institution |  **Venue**   |   Paper   |   Code    |
| :--: | :---------- | :--: | :---------: | :----------: | :-------: | :-------: |
| 2021 | Paper Title |      | University  | Journal Name | [Link](#) | [Link](#) |

### Multi-layer Community Detection

| Year | Title                                                        |        CA        |                       Institution                        | **Venue** |                      Paper                       |                             Code                             |
| :--: | :----------------------------------------------------------- | :--------------: | :------------------------------------------------------: | :-------: | :----------------------------------------------: | :----------------------------------------------------------: |
| 2024 | **Mixture Stochastic Block Model for Multi-Group Community Detection in Multiplex Graphs** | Noureddine Henka |          National Polytechnic School of Algiers          |  *ICLR*   | [Link](https://openreview.net/pdf?id=vjHCyOWc7h) | [Link](https://openreview.net/attachment?id=vjHCyOWc7h&name=supplementary_material) |
| 2022 | **Multilayer graph contrastive clustering network**          |    Zhao Kang     | University of Electronic Science and Technology of China |   *IS*    |     [Link](https://arxiv.org/pdf/2112.14021)     | [Link](https://github.com/Lliang97/Multilayer-Clutering-Network) |

### Multi-view graph clustering

| Year | Title                                                        |       CA        |                       Institution                        | **Venue** |                            Paper                             |                         Code                         |
| :--: | :----------------------------------------------------------- | :-------------: | :------------------------------------------------------: | :-------: | :----------------------------------------------------------: | :--------------------------------------------------: |
| 2024 | **Fast Multiview Anchor-Graph Clustering**                   |    Ben Yang     |                Xi’an Jiaotong University                 |  *IEEE*   | [Link](https://ieeexplore.ieee.org/abstract/document/10433571) |                          --                          |
| 2024 | **Homophily-Related: Adaptive Hybrid Graph Filter for Multi-View Graph Clustering** |   Yazhou Ren    | University of Electronic Science and Technology of China |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/29514/30852) |   [Link](https://github.com/ZichenWen1/AHGFC.git)    |
| 2024 | **Dual-Optimized Adaptive Graph Reconstruction for Multi-View Graph Clustering** |   Yazhou Ren    | University of Electronic Science and Technology of China |   *MM*    |       [Link](https://openreview.net/pdf?id=kBfPB0i98K)       |                          --                          |
| 2024 | **Dynamic Weighted Graph Fusion for Deep Multi-View Clustering** |   Yazhou Ren    | University of Electronic Science and Technology of China |  *IJCAI*  |   [Link](https://www.ijcai.org/proceedings/2024/0535.pdf)    |                          --                          |
| 2024 | **Homophily-Related: Adaptive Hybrid Graph Filter for Multi-View GraphClusterning** |   Yazhou Ren    | University of Electronic Science and Technology of China |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/29514) |     [Link](https://github.com/ZichenWen1/AHGFC)      |
| 2024 | **Dual Information Enhanced Multi-view Attributed Graph Clustering** | Chang-Dong Wang |                  Sun Yat-sen University                  |  *TNNLS*  |           [Link](https://arxiv.org/pdf/2211.14987)           |     [Link](https://github.com/JiaqiLin-AI/DIAGC)     |
| 2024 | **Graph Clustering Contrastive Multiview Attribute Graph Clustering With Adaptive Encoders** | Chang-Dong Wang |                  Sun Yat-sen University                  |  *TNNLS*  | [Link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10509800) |                          --                          |
| 2024 | **Multi-view attributed graph clustering based on graph diffusion convolution with adaptive fusion** | Zhi hong Zhang  |                   Zhengzhou University                   |  *ESWA*   | [Link](https://www.sciencedirect.com/science/article/pii/S0957417424021535) |                          --                          |
| 2024 | **Scalable and Structural Multi-view Graph Clustering with Adaptive Anchor Fusion** |   Xinwang Liu   |        National University of Defense Technology         |   *TIP*   | [Link](https://ieeexplore.ieee.org/abstract/document/10643455) |  [Link](https://github.com/wangsiwei2010/SMVAGC-SF)  |
| 2024 | **Multi-view fair-augmentation contrastive graph clustering with reliable pseudo-labels** |     Wei Xu      |                    Renmin University                     |   *IS*    | [Link](https://www.sciencedirect.com/science/article/pii/S0020025524006534) |        [Link](https://github.com/buthi/MFCGC)        |
| 2023 | **Sample-level Multi-view Graph Clustering**                 |  Shudong Huang  |                    Sichuan University                    |  *CVPR*   | [Link](https://openaccess.thecvf.com/content/CVPR2023/papers/Tan_Sample-Level_Multi-View_Graph_Clustering_CVPR_2023_paper.pdf) | [Link](https://github.com/huangsd/Sample-Level-MVGC) |
| 2023 | **Metric Multi-View Graph Clustering**                       |  Shudong Huang  |                    Sichuan University                    |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/26188) |       [Link](https://github.com/huangsd/MMGC)        |
| 2023 | **Clustering Information-guided Multi-view Contrastive Graph Clustering** |   Jinke Wang    |                     Henan University                     | *ICPADS*  | [Link](https://ieeexplore.ieee.org/abstract/document/10476196/) |      [Link](https://github.com/tczgithub/IGMC)       |
| 2023 | **Simultaneous linear multi-view attributed graph representation learning and clustering** |  Mohamed Nadif  |                 *Université Paris Cité*                  |  *WSDM*   |      [Link](https://hal.science/hal-04467651/document)       |      [Link](https://github.com/chakib401/LMGEC)      |
| 2023 | **Deep multi-view graph clustering network with weighting mechanism and collaborative training** |   Fuyuan Cao    |                    Shanxi University                     |  *ESWA*   | [Link](https://www.sciencedirect.com/science/article/pii/S0957417423018006) |                          --                          |
| 2021 | **Multi-view Contrastive Graph Clustering**                  |    Zhao Kang    | University of Electronic Science and Technology of China |  *NIPS*   | [Link](https://proceedings.neurips.cc/paper/2021/file/10c66082c124f8afe3df4886f5e516e0-Paper.pdf) |        [Link](https://github.com/Panern/MCGC)        |
| 2021 | **Graph Filter-based Multi-view Attributed Graph Clustering** |    Zhao Kang    | University of Electronic Science and Technology of China |  *IJCAI*  |   [Link](https://www.ijcai.org/proceedings/2021/0375.pdf)    |       [Link](https://github.com/sckangz/MvAGC)       |
| 2021 | **Multi-view Attributed Graph Clustering**                   |    Zhao Kang    | University of Electronic Science and Technology of China |  *TKDE*   | [Link](https://www.researchgate.net/profile/Zhao-Kang-6/publication/353747180_Multi-view_Attributed_Graph_Clustering/links/612059cd0c2bfa282a5cd55e/Multi-view-Attributed-Graph-Clustering.pdf) |       [Link](https://github.com/sckangz/MAGC)        |
| 2020 | **Multi-View Attribute Graph Convolution Networks for Clustering** |  Quanxue *Gao*  |                    Xidian University                     |  *IJCAI*  |   [Link](https://www.ijcai.org/proceedings/2020/0411.pdf)    |       [Link](https://github.com/IMKBLE/MAGCN)        |
| 2019 | **Contextual Correlation Preserving Multiview Featured Graph Clustering** |    Yang Liu     |               Hong Kong Baptist Universit                |  *TCYB*   | [Link](https://dr.ntu.edu.sg/bitstream/10356/147805/2/T-Cyber-v19.pdf) |   [Link](https://github.com/he-tiantian/CCPMVFGC)    |

---

## <a name="weekly-paper-presentations"></a> 📆 Weekly Paper Presentations

Each week, we present a paper related to community detection in our research group. This section includes summaries and key takeaways from the weekly papers discussed in our meetings. Click on the links below to access each presentation.

- **Week 1- [Synergistic Deep Graph Clustering Network(SDGCN)](https://github.com/Derick077/Weekly-meeting)and[UltraGcn](https://github.com/fal1winter/graph-notebook)**
- **Week 2- [Contrastive Multiview Attribute Graph Clustering With Adaptive Encoders(CMAGC)](https://github.com/Derick077/Weekly-meeting)and[Heterogeneous Graph Contrastive Learning for Recommendation（HGCL）](https://github.com/fal1winter/graph-notebook)**
- **Week 3- [Motif-Based Contrastive Learning for Community Detection（MotifCC）](https://github.com/Derick077/Weekly-meeting)and[XSimGCL](https://github.com/fal1winter/graph-notebook)**
- **Week 4- [Revisiting Modularity Maximization for Graph Clustering: A Contrastive Learning Perspective(Magi)](https://github.com/Derick077/Weekly-meeting)and[Multi-View Attribute Graph Convolution Networks for Clustering(MAGCN)](https://github.com/guohanju/Weekly-Meeting.git) and [Cooperative Graph Neural Networks](https://github.com/fal1winter/graph-notebook)**
- **Week 5- [Community detection based on unsupervised attributed network embedding（CBDNE）](https://github.com/Derick077/Weekly-meeting)and[Multi-view Attributed Graph Clustering(MAGC)](https://github.com/guohanju/Weekly-Meeting.git) and [Cooperative Graph Neural Networks](https://github.com/fal1winter/graph-notebook)**

---

## <a name="useful-libraries"></a> 📖 Useful Libraries

- [A Comprehensive Survey of Community Detection Approaches: From Statistical Modeling to Deep Learning](#)

---

Happy researching! If you find this repository useful, feel free to star ⭐ it and contribute.
