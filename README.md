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

| Year | Title                                                        |       CA        |                         Institution                         | **Venue** |                            Paper                             |                             Code                             |
| :--: | :----------------------------------------------------------- | :-------------: | :---------------------------------------------------------: | :-------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024 | **Advanced Graph Clustering Methods: A Comprehensive and In-Depth Analysis** | Timothé Watteau | UTBM, Energy and IT Division, F-90010 Belfort cedex, France |  *arXIv*  |           [Link](https://arxiv.org/pdf/2407.09055)           |                              --                              |
| 2024 | **Advanced Graph Clustering Methods: A Comprehensive and In-Depth Analysis** | Timothé Watteau |                UTBM, Energy and IT Division                 |  *arXiv*  |           [Link](https://arxiv.org/abs/2407.09055)           | [Link](https://github.com/timothewt/AdvancedGraphClustering) |
| 2023 | **An Overview of Advanced Deep Graph Node Clustering**       |   William Zhu   |  University of Electronic Science and Technology of China   |  *TCSS*   | [Link](https://ieeexplore.ieee.org/abstract/document/10049408/) |                              --                              |
| 2022 | **A Survey of Deep Graph Clustering: Taxonomy, Challenge, Application, and Open Resource** |   Xinwang Liu   |          National University of Defense Technology          |  *arXiv*  |           [Link](https://arxiv.org/abs/2211.12875)           | [Link](https://github.com/yueliu1999/Awesome-Deep-Graph-Clustering) |
| 2022 | **A Comprehensive Survey on Community Detection with Deep Learning** |     Jia Wu      |                    Macquarie University                     |  *TNNLS*  | [Link](https://arxiv.org/pdf/2105.12584.pdf?ref=https://githubhelp.com) |                              --                              |
| 2021 | **A survey of community detection approaches: From statistical modeling to deep learning** |  Pengfei Jiao   |                     Tianjin University                      |  *TKDE*   | [Link](https://ieeexplore.ieee.org/abstract/document/9511798/) |                              --                              |

### Deep Learning-based Methods

#### Reconstructive Deep Graph Clustering

| Year | Title                                                        |          CA           |                    Institution                     | **Venue** |                            Paper                             |                           Code                           |
| :--: | :----------------------------------------------------------- | :-------------------: | :------------------------------------------------: | :-------: | :----------------------------------------------------------: | :------------------------------------------------------: |
| 2024 | **Multi-scale graph clustering network**                     |        Wei Wu         |                Zhejiang University                 |   *IS*    | [Link](https://www.sciencedirect.com/science/article/abs/pii/S002002552400937X) | [Link](https://github.com/wangtong627/MSGA-NeuroCom.git) |
| 2024 | **Deep Masked Graph Node Clustering**                        |     Shiping Wang      |                 Fuzhou University                  |  *IEEE*   | [Link](https://ieeexplore.ieee.org/abstract/document/10550181) |                            --                            |
| 2024 | **Towards attributed graph clustering using enhanced graph  and reconstructed graph structure** |      Xuejin Yang      |            Wuhan Polytechnic University            |   *AIR*   | [Link](https://link.springer.com/content/pdf/10.1007/s10462-024-10958-1.pdf) |                            --                            |
| 2024 | **DAG: Deep Adaptive and Generative *𝐾*-Free Community Detection on Attributed Graphs** |       Yue Ding        |           Shanghai Jiao Tong University            |   *KDD*   |    [Link](https://edwlin.github.io/pubs/kdd2024-dag.pdf)     |                            --                            |
| 2024 | **Boosting Pseudo-Labeling With Curriculum Self-Reflection for Attributed Graph Clustering** |        Yu Wang        |                 Tianjin University                 |  *IEEE*   |      [Link](https://doi.org/10.1109/TNNLS.2024.3416167)      |                            --                            |
| 2024 | **Graph Decoding via Generalized Random Dot Product Graph**  | Alvaro Ciudad Serrano |                         --                         |  *ICLR*   |       [Link](https://openreview.net/pdf?id=AxYTFpdlvj)       |                            --                            |
| 2024 | **Masked AutoEncoder for Graph Clustering without Pre-defined Cluster Number k** |      Yuanchi Ma       |             University of Pennsylvania             |  *arXiv*  |           [Link](https://arxiv.org/pdf/2401.04741)           |                            --                            |
| 2024 | **Dual Fusion AutoEncoder for Graph Clustering**             |      Yuanchi Ma       |             University of Pennsylvania             |  *ICLR*   |       [Link](https://openreview.net/pdf?id=VTdGLgmQQM)       |                            --                            |
| 2024 | **Self‑supervised graph clustering via attention auto‑encoder  with distribution specifcity** |       Zishi Li        |                 Xiamen University                  |   *MS*    | [Link](https://link.springer.com/article/10.1007/s00530-024-01346-4) |                            --                            |
| 2023 | **GLASS: A Graph Laplacian Autoencoder with Subspace Clustering Regularization for Graph Clustering** |      Dengdi Sun       |                  Anhui University                  |   *CC*    | [Link](https://link.springer.com/article/10.1007/s12559-022-10098-0) |                            --                            |
| 2023 | **Wiener Graph Deconvolutional Network Improves Graph Self-Supervised Learning** |        Jia Li         | The Hong Kong University of Science and Technology |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/25870/25642) |       [Link](https://github.com/jcheng66/WGDN.git)       |
| 2018 | **Deep Autoencoder-like Nonnegative Matrix Factorization for Community Detection** |      Zibin Zheng      |               Sun Yat-sen University               |  *CIKM*   | [Link](https://www.researchgate.net/profile/Chuan-Chen-11/publication/328439632_Deep_Autoencoder-like_Nonnegative_Matrix_Factorization_for_Community_Detection/links/5d7dc4b3a6fdcc2f0f6fbf3a/Deep-Autoencoder-like-Nonnegative-Matrix-Factorization-for-Community-Detection.pdf) | [Link](https://github.com/benedekrozemberczki/DANMF.git) |

#### Adversarial Deep Graph Clustering

| Year | Title       |  CA  | Institution |  **Venue**   |   Paper   |   Code    |
| :--: | :---------- | :--: | :---------: | :----------: | :-------: | :-------: |
| 2021 | Paper Title |      | University  | Journal Name | [Link](#) | [Link](#) |

#### Contrastive Deep Graph Clustering

| Year | Title                                                        |       CA       |                     Institution                      | **Venue** |                            Paper                             |                           Code                           |
| :--: | :----------------------------------------------------------- | :------------: | :--------------------------------------------------: | :-------: | :----------------------------------------------------------: | :------------------------------------------------------: |
| 2024 | **Reliable Node Similarity Matrix Guided Contrastive Graph Clustering** |    Tieke He    |                  Nanjing University                  |  *IEEE*   |           [Link](https://arxiv.org/pdf/2408.03765)           |     [Link](https://github.com/Cloudy1225/NS4GC.git)      |
| 2024 | **Deep Attributed Graph Clustering with Feature Consistency** |  Yuanyuan Li   | Chongqing University of Posts and Telecommunications |   *KBS*   | [Link](https://www.sciencedirect.com/science/article/pii/S0950705124012681) |                            --                            |
| 2024 | **GMNI: Achieve good data augmentation in unsupervised graph contrastive learning** |  Suorong Yang  |                  Nanjing University                  |   *NN*    | [Link](https://www.sciencedirect.com/science/article/pii/S0893608024007287) |                            --                            |
| 2024 | **Enhancing Contrastive Learning on Graphs with Node Similarity** | Hongliang Chi  |           Rensselaer Polytechnic Institute           |   *KDD*   |  [Link](https://dl.acm.org/doi/abs/10.1145/3637528.3671898)  | [Link](https://github.com/frankhlchi/SimEnhancedGCL.git) |
| 2024 | **Deep Contrastive Graph Learning with Clustering-Oriented Guidance** |   Xuelong Li   |        Northwestern Polytechnical University         |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/download/29016/29927) |   [Link](https://github.com/drongwbc/DCGL-AAAI24.git)    |
| 2024 | **Towards Faster Deep Graph Clustering via Efficient Graph Auto-Encoder** |  Hongmei Liao  |      China University of Mining and Technology       |  *TKDD*   |      [Link](https://dl.acm.org/doi/abs/10.1145/3674983)      |    [Link](https://github.com/Marigoldwu/FastDGC.git)     |
| 2024 | **Attributed Graph Clustering Under the Contrastive Mechanism with Cluster-preserving Augmentation** |   Caiyan Jia   |             Beijing Jiaotong University              |   *IS*    | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0020025524011393) |                            --                            |
| 2024 | **Revisiting Modularity Maximization for Graph Clustering: A Contrastive Learning Perspective** |   Jintang Li   |                Sun Yat-Sen University                |  *arXiv*  |  [Link](https://dl.acm.org/doi/pdf/10.1145/3637528.3671967)  |                            --                            |
| 2023 | **Community-Aware Efficient Graph Contrastive Learning via Personalized Self-Training** |   Chuan Chen   |                Sun Yat-Sen University                |  *arXiv*  |           [Link](https://arxiv.org/pdf/2311.11073)           |                            --                            |
| 2023 | **Cluster-guided Contrastive Graph Clustering Network**      |  Xinwang Liu   |      National University of Defense Technology       |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/download/26285/26057) |    [Link](https://github.com/xihongyang1999/CCGC.git)    |
| 2023 | **A Contrastive Variational Graph Auto-Encoder** **for Node Clustering** | Nairouz Mrabah |                 University of Quebec                 |  *arXiv*  |           [Link](https://arxiv.org/pdf/2312.16830)           |     [Link](https://github.com/nairouz/CVGAE_PR.git)      |
| 2023 | **CONVERT: Contrastive Graph Clustering with Reliable Augmentation** |  Xinwang Liu   |      National University of Defense Technology       |  *arXiv*  |           [Link](https://arxiv.org/pdf/2308.08963)           |  [Link](https://github.com/xihongyang1999/CONVERT.git)   |
| 2022 | **Self-consistent Contrastive Attributed Graph Clustering with Pseudo-label Prompt** |  Quanxue Gao   |                  Xidian University                   |  *IEEE*   | [Link](https://ieeexplore.ieee.org/abstract/document/9914670) |      [Link](https://github.com/xdweixia/SCAGC.git)       |

### Spectral Methods

| Year | Title       |  CA  | Institution |  **Venue**   |   Paper   |   Code    |
| :--: | :---------- | :--: | :---------: | :----------: | :-------: | :-------: |
| 2021 | Paper Title |      | University  | Journal Name | [Link](#) | [Link](#) |

### Label Propagation

| Year | Title       |  CA  | Institution |  **Venue**   |   Paper   |   Code    |
| :--: | :---------- | :--: | :---------: | :----------: | :-------: | :-------: |
| 2021 | Paper Title |      | University  | Journal Name | [Link](#) | [Link](#) |

### Modularity Optimization

| Year | Title                                                        |       CA       |               Institution               | **Venue** |                            Paper                             | Code |
| :--: | :----------------------------------------------------------- | :------------: | :-------------------------------------: | :-------: | :----------------------------------------------------------: | :--: |
| 2024 | **Attributed Graph Clustering via Coarsening with Modularity** | Samarth Bhatia |       Indian Institute of Science       |  *ICLR*   |       [Link](https://openreview.net/pdf?id=ukmh3mWFf0)       |  --  |
| 2024 | **Higher-order Fuzzy Membership in Motif Modularity Optimization** |   Xiao-Ke Xu   |        Beijing Normal University        |  *arXiv*  |           [Link](https://arxiv.org/pdf/2407.07301)           |  --  |
| 2024 | **Modularity aided consistent attributed graph clustering via coarsening** | Samarth Bhatia |     Indian Institute of Technology      |  *arXiv*  |           [Link](https://arxiv.org/pdf/2407.07128)           |  --  |
| 2023 | **DGCLUSTER: A Neural Framework for Attributed Graph Clustering via Modularity Maximization** |   Mert Kosan   | University of California, Santa Barbara |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/28983/29868) |  --  |

### Stochastic Block Models

| Year | Title       |  CA  | Institution |  **Venue**   |   Paper   |   Code    |
| :--: | :---------- | :--: | :---------: | :----------: | :-------: | :-------: |
| 2021 | Paper Title |      | University  | Journal Name | [Link](#) | [Link](#) |

### **Nonnegative** Matrix Factorization

| Year | Title                                                        |     CA      |          Institution          | **Venue** |                            Paper                             |                     Code                      |
| :--: | :----------------------------------------------------------- | :---------: | :---------------------------: | :-------: | :----------------------------------------------------------: | :-------------------------------------------: |
| 2024 | **Dual-learning Multi-hop Nonnegative Matrix Factorization for Community Detection** | Bilian Chen |       Xiamen University       |   *NN*    | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0893608024002843) |                      --                       |
| 2024 | **Contrastive Deep Nonnegative Matrix Factorization For Community Detection** | Chuan Chen  |    Sun Yat-sen University     |  *IEEE*   | [Link](https://ieeexplore.ieee.org/abstract/document/10446107) |   [Link](https://github.com/6lyc/CDNMF.git)   |
| 2024 | **Community detection in attributed networks via adaptive deep nonnegative matrix factorization** |  Chaobo He  | South China Normal University |   *NCA*   | [Link](https://link.springer.com/article/10.1007/s00521-023-09066-y) | [Link](https://github.com/GDM-SCNU/ADNMF.git) |

### Other Methods

| Year | Title                                                        |         CA         |                         Institution                          |    **Venue**     |                            Paper                             |                      Code                      |
| :--: | :----------------------------------------------------------- | :----------------: | :----------------------------------------------------------: | :--------------: | :----------------------------------------------------------: | :--------------------------------------------: |
| 2024 | **A Multi-Embedding Fusion Network for attributed graph clustering** |     Xianbin Lu     |     Chongqing University of Posts and Telecommunications     |      *ASC*       | [Link](https://www.sciencedirect.com/science/article/abs/pii/S1568494624008470) |                       --                       |
| 2024 | **𝑘-plex-based community detection with graph neural networks** |    Qifeng Zhou     |                      Xiamen University                       |       *IS*       | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0020025524014233) |  [Link](https://github.com/lol12854/KPGN.git)  |
| 2024 | **Network Tight Community Detection**                        |    Huimin Cheng    |                      Boston University                       |      *ICML*      |       [Link](https://openreview.net/pdf?id=XQz7ytgETQ)       |                       --                       |
| 2024 | **A graph convolutional network model based on regular equivalence for identifying influential nodes in complex networks** |     Yanmei Hu      |               Chengdu University of Technology               |      *KBS*       | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0950705124008694) |                       --                       |
| 2024 | **Synergistic Deep Graph Clustering Network**                |    Shifei Ding     |          China University of Mining and Technology           |     *arXiv*      |           [Link](https://arxiv.org/pdf/2406.15797)           | [Link](https://github.com/Marigoldwu/SynC.git) |
| 2024 | **XLoCoFC: A Fast Fuzzy Community Detection Approach Based on Expandable Local Communities Through Max-Membership Degree Propagation** |  Pranab K. Muhuri  |                    South Asian University                    |      *IEEE*      | [Link](https://ieeexplore.ieee.org/abstract/document/10550008) |                       --                       |
| 2024 | **Information-enhanced deep graph clustering network**       |     Jiahao Wei     |     Chongqing University of Posts and Telecommunications     | *NEUROCOMPUTING* | [Link](https://www.sciencedirect.com/science/article/abs/pii/S092523122400763X) |                       --                       |
| 2024 | **Multi-scale Graph Clustering Network**                     |       Wei Wu       |                     Zhejiang University                      |       *IS*       | [Link](https://www.sciencedirect.com/science/article/abs/pii/S002002552400937X) |                       --                       |
| 2024 | **Deep graph clustering by integrating community structure with neighborhood information** |   Xiaopeng Zhao    | Integrated system operation and maintenance center, Hebei Provincial Department of Finance, Shijiazhuang 050091, China |       *IS*       | [Link](https://www.sciencedirect.com/science/article/abs/pii/S002002552400865X) |                       --                       |
| 2024 | **Feature Graph Augmented Network Representation for Community Detection** |     Lei Zhang      |                       Anhui University                       |      *IEEE*      | [Link](https://doctor-nobody.github.io/papers/tcss2024-2.pdf) |                       --                       |
| 2024 | **Attribute Diversity Aware Community Detection on Attributed Graphs  Using Three-view Graph Attention Neural Networks** |     Yang Zhang     | Research Center for Data Hub and Security, Zhejiang Laboratory, China |      *TKDD*      |      [Link](https://dl.acm.org/doi/abs/10.1145/3672081)      |                       --                       |
| 2024 | **CDC: A Simple Framework for Complex Data Clustering**      |     Zhao Kang      |   University of Electronic Science and Technology of China   |     *arXiv*      |           [Link](https://arxiv.org/pdf/2403.03670)           |                       --                       |
| 2024 | **Provable Filter for Real-world Graph Clustering**          |     Zhao Kang      |   University of Electronic Science and Technology of China   |     *arXiv*      |           [Link](https://arxiv.org/pdf/2403.03666)           |                       --                       |
| 2024 | **A Differentially Private Clustering Algorithm for Well-Clustered Graphs** |      Pan Peng      |        University of Science and Technology of China         |     *arXiv*      |           [Link](https://arxiv.org/pdf/2403.14332)           |                       --                       |
| 2024 | **Every Node is Different: Dynamically Fusing Self-Supervised Tasks for Attributed Graph Clustering** |      Yu Wang       |                      Tianjin University                      |      *AAAI*      | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/29664/31133) |                       --                       |
| 2023 | **Local Graph Clustering with Noisy Labels**                 | Artur Back de Luca |                    University of Waterloo                    |     *arXiv*      |           [Link](https://arxiv.org/abs/2310.08031)           |                       --                       |
| 2023 | **The projection method: a unified formalism for community detection** |  Martijn Gösgens   |              Eindhoven University of Technology              |     *arXiv*      | [Link](https://www.frontiersin.org/articles/10.3389/fcpxs.2024.1331320/pdf) |                       --                       |
| 2023 | **Multi-class Graph Clustering via Approximated Effective *p*-Resistance** |    Shota Saito     |                  University College London                   |      *PMLR*      | [Link](https://proceedings.mlr.press/v202/saito23a/saito23a.pdf) |                       --                       |
| 2023 | **Constrained Social Community Recommendation**              |     Sibo Wang      |             The Chinese University of Hong Kong              |      *KDD*       | [Link](https://edwlin.github.io/pubs/kdd2023-community.pdf)  |                       --                       |
| 2010 | **Local resolution-limit-free Potts model for community detection** |   Peter Ronhovde   |                    Washington University                     |     *arXiv*      |           [Link](https://arxiv.org/pdf/0803.2548)            |                       --                       |

### Community Detection with Unknown Cluster Number

| Year | Title                                                        |     CA     |              Institution              | **Venue** |                       Paper                        | Code |
| :--: | :----------------------------------------------------------- | :--------: | :-----------------------------------: | :-------: | :------------------------------------------------: | :--: |
| 2024 | **Parameter-Agnostic Deep Graph Clustering**                 | Cheng Deng |           Xidian University           |  *TKDD*   | [Link](https://dl.acm.org/doi/abs/10.1145/3633783) |  --  |
| 2024 | **LSEnet: Lorentz Structural Entropy Neural Network for Deep Graph Clustering** |   Li Sun   | North China Electric Power University |  *arXiv*  |      [Link](https://arxiv.org/pdf/2405.11801)      |  --  |

### Overlapping Community Detection

| Year | Title       |  CA  | Institution |  **Venue**   |   Paper   |   Code    |
| :--: | :---------- | :--: | :---------: | :----------: | :-------: | :-------: |
| 2021 | Paper Title |      | University  | Journal Name | [Link](#) | [Link](#) |

### Temporal Community Detection

| Year | Title                                                        |         CA          |                Institution                | **Venue** |                  Paper                   |                             Code                             |
| :--: | :----------------------------------------------------------- | :-----------------: | :---------------------------------------: | :-------: | :--------------------------------------: | :----------------------------------------------------------: |
| 2024 | **Deep Temporal Graph Clustering**                           |     Xinwang Liu     | National University of Defense Technology |  *arXiv*  | [Link](https://arxiv.org/pdf/2305.10738) | [Link](https://github.com/MGitHubL/Deep-Temporal-Graph-Clustering.git) |
| 2024 | **A Near-Linear Time Approximation Algorithm for Beyond-Worst-Case Graph Clustering** | Vincent Cohen-Addad |            Sorbonne University            |  *arXiv*  | [Link](https://arxiv.org/pdf/2406.04857) |                              --                              |

### Attribute-Missing Community Detection

| Year | Title                                          |     CA      |                Institution                | **Venue** |                            Paper                             |                   Code                   |
| :--: | :--------------------------------------------- | :---------: | :---------------------------------------: | :-------: | :----------------------------------------------------------: | :--------------------------------------: |
| 2024 | **Attribute-Missing Graph Clustering Network** | Xinwang Liu | National University of Defense Technology |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/29464/30760) | [Link](https://github.com/WxTu/AMGC.git) |

### Multi-layer Community Detection

| Year | Title                                                        |        CA        |                       Institution                        | **Venue** |                            Paper                             |                             Code                             |
| :--: | :----------------------------------------------------------- | :--------------: | :------------------------------------------------------: | :-------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024 | **Multi-Graph Contrastive Learning for Community Detection in Multi-Layer Networks** |    Yaxiong Ma    |                    Xidian University                     |  *IEEE*   | [Link](https://ieeexplore.ieee.org/abstract/document/10679162) |                              --                              |
| 2024 | **Mixture Stochastic Block Model for Multi-Group Community Detection in Multiplex Graphs** | Noureddine Henka |          National Polytechnic School of Algiers          |  *ICLR*   |       [Link](https://openreview.net/pdf?id=vjHCyOWc7h)       | [Link](https://openreview.net/attachment?id=vjHCyOWc7h&name=supplementary_material) |
| 2022 | **Multilayer graph contrastive clustering network**          |    Zhao Kang     | University of Electronic Science and Technology of China |   *IS*    |           [Link](https://arxiv.org/pdf/2112.14021)           | [Link](https://github.com/Lliang97/Multilayer-Clutering-Network) |

### Multi-view graph clustering

| Year | Title                                                        |       CA        |                       Institution                        | **Venue** |                            Paper                             |                         Code                         |
| :--: | :----------------------------------------------------------- | :-------------: | :------------------------------------------------------: | :-------: | :----------------------------------------------------------: | :--------------------------------------------------: |
| 2024 | **Dual-Adaptive Fusion Multi-View Clustering Based  on Graph Autoencoder** |   Lijuan Zhou   |                   Zhengzhou University                   |  *IEEE*   |       [Link](https://ieeexplore.ieee.org/abstract/document/10650084/)       |                          --                          |
| 2024 | **Trusted Multi-view Learning with Label Noise**             |    Ziyu Guan    |                    Xidian University                     |  *arXiv*  |           [Link](https://arxiv.org/pdf/2404.11944)           |  [Link](https://github.com/YilinZhang107/TMNR.git)   |
| 2024 | **Dual-Optimized Adaptive Graph Reconstruction for Multi-View Graph Clustering** |   Yazhou Ren    | University of Electronic Science and Technology of China |   *MM*    |       [Link](https://openreview.net/pdf?id=kBfPB0i98K)       |                          --                          |
| 2024 | **Balanced Multi-Relational Graph Clustering**               |    Zhao Kang    | University of Electronic Science and Technology of China |  *arXiv*  |           [Link](https://arxiv.org/pdf/2407.16863)           |  [Link](https://github.com/zxlearningdeep/BMGC.git)  |
| 2024 | **Dynamic Weighted Graph Fusion for Deep Multi-View Clustering** |   Yazhou Ren    | University of Electronic Science and Technology of China |  *IJCAI*  |   [Link](https://www.ijcai.org/proceedings/2024/0535.pdf)    |                          --                          |
| 2024 | **Homophily-Related: Adaptive Hybrid Graph Filter for Multi-View GraphClusterning** |   Yazhou Ren    | University of Electronic Science and Technology of China |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/29514) |     [Link](https://github.com/ZichenWen1/AHGFC)      |
| 2024 | **Dual Information Enhanced Multi-view Attributed Graph Clustering** | Chang-Dong Wang |                  Sun Yat-sen University                  |  *TNNLS*  |           [Link](https://arxiv.org/pdf/2211.14987)           |     [Link](https://github.com/JiaqiLin-AI/DIAGC)     |
| 2024 | **Graph Clustering Contrastive Multiview Attribute Graph Clustering With Adaptive Encoders** | Chang-Dong Wang |                  Sun Yat-sen University                  |  *TNNLS*  | [Link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10509800) |                          --                          |
| 2024 | **Multi-view attributed graph clustering based on graph diffusion convolution with adaptive fusion** | Zhi hong Zhang  |                   Zhengzhou University                   |  *ESWA*   | [Link](https://www.sciencedirect.com/science/article/pii/S0957417424021535) |                          --                          |
| 2024 | **Scalable and Structural Multi-view Graph Clustering with Adaptive Anchor Fusion** |   Xinwang Liu   |        National University of Defense Technology         |   *TIP*   | [Link](https://ieeexplore.ieee.org/abstract/document/10643455) |  [Link](https://github.com/wangsiwei2010/SMVAGC-SF)  |
| 2024 | **Multi-view fair-augmentation contrastive graph clustering with reliable pseudo-labels** |     Wei Xu      |                    Renmin University                     |   *IS*    | [Link](https://www.sciencedirect.com/science/article/pii/S0020025524006534) |        [Link](https://github.com/buthi/MFCGC)        |
| 2023 | **Sample-level Multi-view Graph Clustering**                 |  Shudong Huang  |                    Sichuan University                    |  *CVPR*   | [Link](https://openaccess.thecvf.com/content/CVPR2023/papers/Tan_Sample-Level_Multi-View_Graph_Clustering_CVPR_2023_paper.pdf) | [Link](https://github.com/huangsd/Sample-Level-MVGC) |
| 2023 | **Metric Multi-View Graph Clustering**                       |  Shudong Huang  |                    Sichuan University                    |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/26188) |       [Link](https://github.com/huangsd/MMGC)        |
| 2023 | **Efficient Multi-View Graph Clustering with Local and Global Structure Preservation** |   Xinwang Liu   |        National University of Defense Technology         |  *arXiv*  |           [Link](https://arxiv.org/pdf/2309.00024)           |  [Link](https://github.com/wenyiwy99/EMVGC-LG.git)   |
| 2023 | **Clustering Information-guided Multi-view Contrastive Graph Clustering** |   Jinke Wang    |                     Henan University                     | *ICPADS*  | [Link](https://ieeexplore.ieee.org/abstract/document/10476196/) |      [Link](https://github.com/tczgithub/IGMC)       |
| 2023 | **Simultaneous linear multi-view attributed graph representation learning and clustering** |  Mohamed Nadif  |                  Université Paris Cité                   |  *WSDM*   |      [Link](https://hal.science/hal-04467651/document)       |      [Link](https://github.com/chakib401/LMGEC)      |
| 2023 | **Deep multi-view graph clustering network with weighting mechanism and collaborative training** |   Fuyuan Cao    |                    Shanxi University                     |  *ESWA*   | [Link](https://www.sciencedirect.com/science/article/pii/S0957417423018006) |                          --                          |
| 2021 | **Multi-view Contrastive Graph Clustering**                  |    Zhao Kang    | University of Electronic Science and Technology of China |  *NIPS*   | [Link](https://proceedings.neurips.cc/paper/2021/file/10c66082c124f8afe3df4886f5e516e0-Paper.pdf) |        [Link](https://github.com/Panern/MCGC)        |
| 2021 | **Graph Filter-based Multi-view Attributed Graph Clustering** |    Zhao Kang    | University of Electronic Science and Technology of China |  *IJCAI*  |   [Link](https://www.ijcai.org/proceedings/2021/0375.pdf)    |       [Link](https://github.com/sckangz/MvAGC)       |
| 2021 | **Multi-view Attributed Graph Clustering**                   |    Zhao Kang    | University of Electronic Science and Technology of China |  *TKDE*   | [Link](https://www.researchgate.net/profile/Zhao-Kang-6/publication/353747180_Multi-view_Attributed_Graph_Clustering/links/612059cd0c2bfa282a5cd55e/Multi-view-Attributed-Graph-Clustering.pdf) |       [Link](https://github.com/sckangz/MAGC)        |
| 2020 | **Multi-View Attribute Graph Convolution Networks for Clustering** |   Quanxue Gao   |                    Xidian University                     |  *IJCAI*  |   [Link](https://www.ijcai.org/proceedings/2020/0411.pdf)    |       [Link](https://github.com/IMKBLE/MAGCN)        |
| 2019 | **Contextual Correlation Preserving Multiview Featured Graph Clustering** |    Yang Liu     |               Hong Kong Baptist Universit                |  *TCYB*   | [Link](https://dr.ntu.edu.sg/bitstream/10356/147805/2/T-Cyber-v19.pdf) |   [Link](https://github.com/he-tiantian/CCPMVFGC)    |

---

## <a name="weekly-paper-presentations"></a> 📆 Weekly Paper Presentations

Each week, we present a paper related to community detection in our research group. This section includes summaries and key takeaways from the weekly papers discussed in our meetings. Click on the links below to access each presentation.

- **Week 1- [Synergistic Deep Graph Clustering Network(SDGCN)](https://github.com/Derick077/Weekly-meeting)and[UltraGcn](https://github.com/fal1winter/graph-notebook)**
- **Week 2- [Contrastive Multiview Attribute Graph Clustering With Adaptive Encoders(CMAGC)](https://github.com/Derick077/Weekly-meeting)and[Heterogeneous Graph Contrastive Learning for Recommendation（HGCL）](https://github.com/fal1winter/graph-notebook)**
- **Week 3- [Motif-Based Contrastive Learning for Community Detection（MotifCC）](https://github.com/Derick077/Weekly-meeting)and[XSimGCL](https://github.com/fal1winter/graph-notebook)**
- **Week 4- [Revisiting Modularity Maximization for Graph Clustering: A Contrastive Learning Perspective(Magi)](https://github.com/Derick077/Weekly-meeting)and[Multi-View Attribute Graph Convolution Networks for Clustering(MAGCN)](https://github.com/guohanju/Weekly-Meeting.git) and [Cooperative Graph Neural Networks](https://github.com/fal1winter/graph-notebook)**
- **Week 5- [Community detection based on unsupervised attributed network embedding（CBDNE）](https://github.com/Derick077/Weekly-meeting)and[Multi-view Attributed Graph Clustering(MAGC)](https://github.com/guohanju/Weekly-Meeting.git) and [Adaptive Graph Contrastive Learning for Recommendation](https://github.com/fal1winter/graph-notebook)**
 - **Week 6- Writting Essay and [Deep multi-view graph clustering network with weighting mechanism and collaborative training(DMVGC)](https://github.com/guohanju/Weekly-Meeting.git) and [DiffKG: Knowledge Graph Diffusion Model for Recommendation](https://github.com/fal1winter/graph-notebook)**
 - **Week 7- Writting Essay and [Multi-view attributed graph clustering based on graph diffusion convolution with adaptive fusion](https://github.com/guohanju/Weekly-Meeting.git) and [Graph Collaborative Signals Denoising and Augmentation for Recommendation](https://github.com/fal1winter/graph-notebook)**
- **Week 9- Writting Essay and  [AdaGMLP: AdaBoosting GNN-to-MLP Knowledge Distillation/GRAPH-LESS NEURAL NETWORKS: TEACHING OLD  MLPS NEW TRICKS VIA DISTILLATION](https://github.com/fal1winter/graph-notebook)**
- **Week 10- Writting Essay and [Dual-Optimized Adaptive Graph Reconstruction for Multi-View Graph Clustering(DOAGC)](https://github.com/guohanju/Weekly-Meeting.git)**

## <a name="useful-libraries"></a> 📖 Useful Libraries

- [A Comprehensive Survey of Community Detection Approaches: From Statistical Modeling to Deep Learning](#)

---

Happy researching! If you find this repository useful, feel free to star ⭐ it and contribute.
