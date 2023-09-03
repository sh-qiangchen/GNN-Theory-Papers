# GNN-Theory-Papers

This repository mainly lists some the latest research on graph neural network theory.



# Table of Contents

<table>
<tr><td colspan="2"><a href="#Survey">Survey</a></td></tr> 
<tr><td colspan="2"><a href="#Spectral-Domains">Spectral Domains</a></td></tr>
<tr><td colspan="2"><a href="#Spatial-Domains">Spatial Domains</a></td></tr>
<tr><td colspan="2"><a href="#Expressive-Power">Expressive Power</a></td></tr>
<tr><td colspan="2"><a href="#Dynamic-Graph">Dynamic Graph</a></td></tr> 
<tr><td colspan="2"><a href="#Application">Application</a></td></tr> 
</table>






## Survey

| **Name** | **Paper**                                                    |   **Venue**   | **Year** | **Code** | Hint |
| -------- | ------------------------------------------------------------ | :-----------: | :------: | :------: | :--: |
| Survey   | [A Comprehensive Survey on Graph Neural Networks](https://arxiv.org/pdf/1901.00596.pdf) |     arxiv     |   2019   |          |      |
| Survey   | [Graph neural networks: A review of methods and applications](https://www.sciencedirect.com/science/article/pii/S2666651021000012) | ScienceDirect |   2020   |          |      |
| Survey   | [Bridging the Gap between Spatial and Spectral Domains: A Survey on Graph Neural Networks](https://arxiv.org/pdf/2002.11867.pdf) |     arxiv     |   2020   |          |      |



## [Spectral Domains](#content)

| **Name**  | **Paper**                                                    | **Venue** | **Year** |                     **Code**                      | Hint |
| :-------: | ------------------------------------------------------------ | :-------: | :------: | :-----------------------------------------------: | :--: |
|           | [Spectral Networks and Deep Locally Connected Networks on Graphs](https://arxiv.org/pdf/1312.6203.pdf) |   arxiv   |   2013   |                                                   |      |
|           | [Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering](https://proceedings.neurips.cc/paper_files/paper/2016/hash/04df4d434d481c5bb723be1b6df1ee65-Abstract.html) |   NIPS    |   2016   |                                                   |      |
|    GCN    | [SEMI-SUPERVISED CLASSIFICATION WITH GRAPH CONVOLUTIONAL NETWORKS](https://arxiv.org/pdf/1609.02907.pdf) |   ICLR    |   2017   |     [Pytorch]( https://github.com/tkipf/gcn)      |      |
|  BernNet  | [BernNet: Learning Arbitrary Graph Spectral Filters via Bernstein Approximation](https://arxiv.org/pdf/2106.10994.pdf) |   arxiv   |   2019   |   [Pytorch](https://github.com/ivam-he/BernNet)   |      |
|  GPR-GNN  | [ADAPTIVE UNIVERSAL GENERALIZED PAGERANK GRAPH NEURAL NETWORK](https://arxiv.org/pdf/2006.07988.pdf) |   ICLR    |   2021   | [Pytorch](https://github.com/jianhao2016/GPRGNN)  |      |
|  EvenNet  | [EvenNet: Ignoring Odd-Hop Neighbors Improves Robustness of Graph Neural Networks](https://arxiv.org/pdf/2205.13892.pdf) |   NIPS    |   2022   |   [Code](https://github.com/Leirunlin/EvenNet)    |      |
|           | [How Powerful are Spectral Graph Neural Networks](https://arxiv.org/pdf/2205.11172.pdf) |   ICLR    |   2022   |                                                   |      |
| FavardGNN | [Graph Neural Networks with Learnable and Optimal Polynomial Bases](https://arxiv.org/pdf/2302.12432.pdf) |   arxiv   |   2023   | [Pytorch](https://github.com/yuziGuo/FarOptBasis) |      |
|  LON-GNN  | [LON-GNN: Spectral GNNs with Learnable Orthonormal Basis](https://arxiv.org/pdf/2303.13750.pdf) |   arxiv   |   2023   | [Pytorch](https://github.com/TaoLbr1993/LON-GNN)  |      |



## [Spatial Domains](#content)

| **Name** | **Paper**                                                    | **Venue** | **Year** |                           **Code**                           | Hint |
| :------: | ------------------------------------------------------------ | :-------: | :------: | :----------------------------------------------------------: | :--: |
|  MPNNs   | [Neural Message Passing for Quantum Chemistry](https://arxiv.org/pdf/1704.01212.pdf) |   arxiv   |   2017   |                                                              |      |
|   SGC    | [Simplifying Graph Convolutional Networks](https://arxiv.org/pdf/1902.07153.pdf) |   ICML    |   2019   |                                                              |      |
|          | [Can Graph Neural Networks Count Substructures?](https://arxiv.org/pdf/2002.04025.pdf) |   NIPS    |   2020   | [Code](https://github.com/leichen2018/GNN-Substructure-Counting) |      |
|  GNNML3  | [Breaking the Limits of Message Passing Graph Neural Networks](https://arxiv.org/pdf/2106.04319.pdf) |   ICML    |   2021   |                                                              |      |
|          | [MESSAGE PASSING ALL THE WAY UP](https://arxiv.org/pdf/2202.11097.pdf) |   arxiv   |   2022   |                                                              |      |
|          | [Shortest Path Networks for Graph Property Prediction](https://arxiv.org/pdf/2206.01003.pdf) |   arxiv   |   2022   |                                                              |      |
|          | [Towards Training GNNs using Explanation Directed Message Passing](https://arxiv.org/pdf/2211.16731.pdf) |   ICLR    |   2022   |                                                              |      |
|          | [ANISOTROPIC MESSAGE PASSING: GRAPH NEURAL NETWORKS WITH DIRECTIONAL AND LONG-RANGE INTERACTIONS](https://openreview.net/pdf?id=socffUzSIlx) |   ICLR    |   2023   |                                                              |      |
|          | [FUNDAMENTAL LIMITS IN FORMAL VERIFICATION OF MESSAGE-PASSING NEURAL NETWORKS](https://arxiv.org/pdf/2206.05070v2.pdf) |   ICLR    |   2023   |                                                              |      |



## [Expressive Power](#content)

| **Name** | **Paper**                                                    | **Venue** | **Year** |                           **Code**                           | Hint |
| :------: | ------------------------------------------------------------ | :-------: | :------: | :----------------------------------------------------------: | :--: |
|          | [Wasserstein Weisfeiler-Lehman Graph Kernels](https://arxiv.org/pdf/1906.01277.pdf) |   JMLR    |   2011   |                                                              |      |
|  k-GNNs  | [Weisfeiler and Leman Go Neural: Higher-order Graph Neural Networks](https://arxiv.org/pdf/1810.02244.pdf) |   arxiv   |   2018   |                                                              |      |
|   GIN    | [How Powerful are Graph Neural Networks?](https://arxiv.org/abs/1810.00826) |   ICLR    |   2019   | [Pytorch](https://github.com/weihua916/powerful-gnns/tree/master) |      |
|          | [Graph Neural Networks are Dynamic Programmers](https://arxiv.org/pdf/2203.15544.pdf) |   arxiv   |   2019   |                                                              |      |
|          | [Stability and Generalization of Graph Convolutional Neural Networks](https://arxiv.org/pdf/1905.01004.pdf) |   arxiv   |   2019   |                                                              |      |
|          | [Understanding the Representation Power of Graph Neural Networks in Learning Graph Topology](https://arxiv.org/pdf/1907.05008.pdf) |   arxiv   |   2019   | [Pytorch](https://github.com/nimadehmamy/Understanding-GCN)  |      |
|          | [GRAPH NEURAL NETWORKS EXPONENTIALLY LOSE EXPRESSIVE POWER FOR NODE CLASSIFICATION](https://arxiv.org/pdf/1905.10947.pdf) |   ICLR    |   2020   |     [Code](https://github.com/delta2323/gnn-asymptotics)     |      |
|  GNN-AK  | [FROM STARS TO SUBGRAPHS: UPLIFTING ANY GNN WITH LOCAL STRUCTURE AWARENESS](https://arxiv.org/pdf/2110.03753.pdf) |   ICLR    |   2022   |   [Pytorch](https://github.com/LingxiaoShawn/GNNAsKernel)    |      |
| GraphSNN | [A NEW PERSPECTIVE ON "HOW GRAPH NEURAL NETWORKS GO BEYOND WEISFEILER-LEHMAN?"](https://openreview.net/pdf?id=uxgg9o7bI_3) |   ICLR    |   2022   |        [Pytorch](https://github.com/wokas36/GraphSNN)        |      |
|  KP-GNN  | [How Powerful are K-hop Message Passing Graph Neural Networks](https://arxiv.org/pdf/2205.13328.pdf) |   ICLR    |   2022   |       [Pytorch](https://github.com/JiaruiFeng/KP-GNN)        |      |
|          | [Two-Dimensional Weisfeiler-Lehman Graph Neural Networks for Link Prediction](https://arxiv.org/pdf/2206.09567.pdf) |   arxiv   |   2022   |                                                              |      |
|          | [Efficiently Counting Substructures by Subgraph GNNs without Running GNN on Subgraphs](https://arxiv.org/pdf/2303.10576.pdf) |   arxiv   |   2023   |                                                              |      |
|          | [Improving Expressivity of Graph Neural Networks using Localization](https://arxiv.org/pdf/2305.19659.pdf) |   arxiv   |   2023   |    [Pytorch](https://github.com/Roy-Shubhajit/InSig-GNN)     |      |
|          | [Approximately Equivariant Graph Networks](https://arxiv.org/pdf/2308.10436v1.pdf) |   arxiv   |   2023   | [Pytorch](https://github.com/nhuang37/Approx_Equivariant_Graph_Nets) |      |
|          | [How Faithful are Self-Explainable GNNs? ](https://arxiv.org/pdf/2308.15096.pdf) |   arxiv   |   2023   |                                                              |      |
|          | [Generalizing Topological Graph Neural Networks with Paths](https://arxiv.org/pdf/2308.06838.pdf) |   arxiv   |   2023   |                                                              |      |
|  N2GNN   | [Towards Arbitrarily Expressive GNNs in O(n2) Space by Rethinking Folklore Weisfeiler-Lehman](https://arxiv.org/pdf/2306.03266.pdf) |   ICLR    |   2023   |        [Pytorch](https://github.com/JiaruiFeng/N2GNN)        |      |
|  I2GNN   | [BOOSTING THE CYCLE COUNTING POWER OF GRAPH NEURAL NETWORKS WITH I2 -GNNS](http://export.arxiv.org/pdf/2210.13978) |   ICLR    |   2023   |         [Pytorch](https://github.com/GraphPKU/I2GNN)         |      |
| VQGRAPH  | [VQGRAPH: Graph Vector-Quantization for Bridging GNNs and MLPs](https://arxiv.org/pdf/2308.02117.pdf) |   arxiv   |   2023   |      [Pytorch](https://github.com/YangLing0818/VQGraph)      |      |



## [Dynamic Graph](#content)

| **Name** | **Paper**                                                    |                          **Venue**                           | **Year** | **Code** | Hint |
| -------- | ------------------------------------------------------------ | :----------------------------------------------------------: | :------: | :------: | :--: |
| Survey   | [Foundations and Modeling of Dynamic Networks Using Dynamic Graph Neural Networks: A Survey](https://ieeexplore.ieee.org/abstract/document/9439502) | [IEEE Access](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6287639) |   2021   |          |      |
| Survey   | [Encoder-Decoder Architecture for Supervised Dynamic Graph Learning: A Survey](https://arxiv.org/pdf/2203.10480.pdf) |                            arxiv                             |   2022   |          |      |
|          | [Information Theoretically Optimal Sample Complexity of Learning Dynamical Directed Acyclic Graphs](https://arxiv.org/pdf/2308.16859.pdf) |                            arxiv                             |   2023   |          |      |
|          | [Reversible and irreversible bracket-based dynamics for deep graph neural networks](https://arxiv.org/pdf/2305.15616.pdf) |                            arxiv                             |   2023   |          |      |
| PIGNN    | [Continual Learning on Dynamic Graphs via Parameter Isolation](https://arxiv.org/pdf/2305.13825.pdf) |                            arxiv                             |   2023   |          |      |
|          | [Analysis of different temporal graph neural network configurations on dynamic graphs](https://arxiv.org/ftp/arxiv/papers/2305/2305.01128.pdf) |                            arxiv                             |   2023   |          |      |
|          |                                                              |                            arxiv                             |   2023   |          |      |



## Application

| **Name** | **Paper**                                                    | **Venue** | **Year** | **Code** | Hint |
| -------- | ------------------------------------------------------------ | :-------: | :------: | :------: | :--: |
| TGC      | [How Expressive are Spectral-Temporal Graph Neural Networks for Time Series Forecasting?](https://arxiv.org/pdf/2305.06587.pdf) |           |  arxiv   |   2023   |      |
| RDGT     | [Recurrent Transformer for Dynamic Graph Representation Learning with Edge Temporal States](https://arxiv.org/pdf/2304.10079.pdf) |           |  arxiv   |   2023   |      |
| Auto-HeG | [Auto-HeG: Automated Graph Neural Network on Heterophilic Graphs](https://arxiv.org/pdf/2302.12357.pdf) |           |  arxiv   |   2023   |      |
|          |                                                              |           |          |          |      |
|          |                                                              |           |          |          |      |
|          |                                                              |           |          |          |      |
|          |                                                              |           |          |          |      |

