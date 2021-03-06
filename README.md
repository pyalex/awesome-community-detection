# Awesome Community Detection
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A collection of community detection papers with implementations.

A similar collection of [[graph embedding]](https://github.com/benedekrozemberczki/awesome-graph-embedding) papers.

<p align="center">
  <img width="460" src="coms.png">
</p>

##### Table of Contents  

1. [Factorization](#factorization)  
2. [Deep Learning](#deep-learning) 
3. [Percolation](#percolation) 
4. [Label Propagation and Random Walks](#label-propagation-and-random-walks) 
5. [Tensor Decomposition](#tensor-decomposition)
6. [Spectral Methods](#spectral-methods) 
7. [Temporal Methods](#temporal-methods) 
8. [Cyclic Patterns](#cyclic-patterns)
9. [Centrality and Cuts](#centrality-and-cuts) 
10. [Physics Inspired](#physics-inspired) 
11. [Others](#others) 
  
## Factorization
- **Graph Embedding with Self-Clustering (Arxiv 2018)**
  - Benedek Rozemberczki, Ryan Davies, Rik Sarkar and Charles Sutton
  - [[paper]](https://arxiv.org/abs/1802.03997)
  - [[Python Reference]](https://github.com/benedekrozemberczki/GEMSEC)
  
- **Sentiment-driven Community Profiling and Detection on Social Media (ACM HSM 2018)**
  - Amin Salehi, Mert Ozer, and Hasan Davulcu
  - [[paper]](https://arxiv.org/abs/1805.04191)
  - [[Python reference]](https://github.com/amin-salehi/GSNMF)
  
- **A Unified Framework for Community Detection and Network Representation Learning (TKDE 2018)**
  - Cunchao Tu, Xiangkai Zeng, Hao Wang, Zhengyan Zhang, Zhiyuan Liu, Maosong Sun, Bo Zhang and Leyu Lin
  - [[paper]](https://arxiv.org/pdf/1611.06645.pdf)
  - [[Java Reference]](http://nlp.csai.tsinghua.edu.cn//~tcc/datasets/simplified_CNRL.zip)
  
- **Community Preserving Network Embedding (AAAI 17)**
  - Xiao Wang, Peng Cui, Jing Wang, Jain Pei, WenWu Zhu, Shiqiang Yang
  - [[paper]](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14589/13763)
  - [[Python Reference]](https://github.com/benedekrozemberczki/M-NMF)
  
- **Semi-supervised Clustering in Attributed Heterogeneous Information Networks (WWW 17)**
  - Xiang Li, Yao Wu, Martin Ester, Ben Kao, Xin Wang, and Yudian Zheng
  - [[paper]](https://dl.acm.org/citation.cfm?id=3052576)
  - [[Python Reference]](https://github.com/wedoso/SCHAIN-NL)
  
- **Learning Community Embedding with Community Detection and Node Embedding on Graph (CIKM 2017)**
  - Sandro Cavallari, Vincent W. Zheng, Hongyun Cai, Kevin Chen-Chuan Chang, and Erik Cambria
  - [[paper]](http://sentic.net/community-embedding.pdf)
  - [[Python Reference]](https://github.com/andompesta/ComE)
  
- **Joint Community and Structural Hole Spanner Detection via Harmonic Modularity (KDD 2016)**
  - Lifang He, Chun-Ta Lu, Jiaqi Mu, Jianping Cao, Linlin Shen, and Philip S Yu
  - [[paper]](https://www.kdd.org/kdd2016/papers/files/rfp1184-heA.pdf)
  - [[Python Reference]](https://github.com/LifangHe/KDD16_HAM)
  
- **A Uniﬁed Semi-Supervised Community Detection Framework Using Latent Space Graph Regularization (IEEE TOC 2015)**
  - Liang Yang, Xiaochun Cao, Di Jin, Xiao Wang and Dan Meng
  - [[paper]](http://yangliang.github.io/pdf/06985550.pdf)
  - [[Matlab reference]](http://yangliang.github.io/code/LSGR.rar)
  
- **Overlapping Community Detection at Scale: a Nonnegative Matrix Factorization Approach (WSDM 2013)**
  - Jaewon Yang and Jure Leskovec
  - [[paper]](http://i.stanford.edu/~crucis/pubs/paper-nmfagm.pdf)
  - [[C++ reference]](https://github.com/snap-stanford/snap/tree/master/examples/bigclam)
  - [[Java Spark]](https://github.com/thangdnsf/BigCLAM-ApacheSpark)
  - [[Python]](https://github.com/RobRomijnders/bigclam)
  
- **Overlapping Community Detection Using Bayesian Non-negative Matrix Factorization (Physical Review E 2011)**
  - Ionnis Psorakis, Stephen Roberts, Mark Ebden, and Ben Sheldon
  - [[paper]](http://www.orchid.ac.uk/eprints/38/1/PRE_NMF.pdf)
  - [[Matlab reference]](https://github.com/ipsorakis/commDetNMF)
  
## Deep Learning
- **Improving the Efficiency and Effectiveness of Community Detection via Prior-Induced Equivalent Super-Network (Scientific Reports 2017)**
  - Liang Yang, Di Jin, Dongxiao He, Huazhu Fu, Xiaochun Cao and Francoise Fogelman-Soulie
  - [[paper]](http://yangliang.github.io/pdf/sr17.pdf)
  - [[Python Reference]](http://yangliang.github.io/code/SUPER.zip)
  
- **Community Detection with Graph Neural Networks (ArXiv 2017)**
  - Zhengdao Chen, Xiang Li, Joan Bruna
  - [[paper]](https://arxiv.org/abs/1705.08415)
  - [[LUA Reference]](https://github.com/joanbruna/GNN_community)
  - [[Python reference]](https://github.com/afansi/multiscalegnn)
  
- **Modularity based Community Detection with Deep Learning (IJCAI 2016)**
  - Liang Yang, Xiaochun Cao, Dongxiao He, Chuan Wang, Xiao Wang and Weixiong Zhan
  - [[paper]](http://yangliang.github.io/pdf/ijcai16.pdf)
  - [[Python Reference]](http://yangliang.github.io/code/DC.zip)
  
## Percolation

## Label Propagation and Random Walks

- **Community Detection by Information Flow Simulation (ArXiv 2018)**
  - Rajagopal Venkatesaramani and Yevgeniy Vorobeychik 
  - [[paper]](https://arxiv.org/abs/1805.04920)
  - [[Python Reference]](https://github.com/rajagopalvenkat/Community_Detection-Flow_Simulation)

- **Community Detection Based on Structure and Content: A Content Propagation Perspective (CIKM 2015)**
  - Liyuan Liu, Linli Xu, Zhen Wangy, and Enhong Chen 
  - [[paper]](http://home.ustc.edu.cn/~llychina/papers/CommunityICDM15.pdf)
  - [[Matlab reference]](https://github.com/LiyuanLucasLiu/Content-Propagation)
  
- **Overlapping Community Detection Using Seed Set Expansion (CIKM 2013)**
  - Joyce Jiyoung Whang, David F. Gleich and Inderjit S. Dhillon
  - [[paper]](http://www.cs.utexas.edu/~inderjit/public_papers/overlapping_commumity_cikm13.pdf)
  - [[Python reference]](https://github.com/pratham16/community-detection-by-seed-expansion)
  
- **SLPA: Uncovering Overlapping Communities in Social Networks via A Speaker-listener Interaction Dynamic Process (ICDMW 2011)**
  - Jierui Xie and Boleslaw K Szymanski and Xiaoming Liu
  - [[paper]](https://arxiv.org/pdf/1109.5720.pdf)
  - [[Java]](https://github.com/sebastianliu/SLPA-community-detection)
  - [[Python]](https://github.com/kbalasu/SLPA)
  - [[C++]](https://github.com/arminbalalaie/graphlab-slpa)
  
## Tensor Decomposition
- **Community Detection, Link Prediction, and Layer Interdependence in Multilayer Networks (Physical Review E 2017)**
  - Caterina De Bacco, Eleanor A. Power, Daniel B. Larremore and Cristopher Moore
  - [[paper]](https://arxiv.org/abs/1701.01369)
  - [[Python Reference]](https://github.com/cdebacco/MultiTensor)
  
- **Overlapping Community Detection via Constrained PARAFAC: A Divide and Conquer Approach (ICDM 2017)**
  - Fatemeh Sheikholeslami and Georgios B. Giannakis 
  - [[Paper]](https://ieeexplore.ieee.org/document/8215485)
  - [[Python Reference]](https://github.com/FatemehSheikholeslami/EgoTen)
  
- **Fast Detection of Overlapping Communities via Online Tensor Methods on GPUs (ArXiV 2013)**
  - Furong Huang and Niranjan, UN and Hakeem, M and Anandkumar, Animashree
  - [[paper]](https://www.semanticscholar.org/paper/Fast-Detection-of-Overlapping-Communities-via-on-Huang-Niranjan/356e6c7eacca6caa94a5a96f41a9c785064f5693)
  - [[C++](https://github.com/mapleyustat/Fast-Detection-of-Overlapping-Communities-via-Online-Tensor-Methods)

## Spectral Methods

- **Community Detection on Euclidean Random Graphs (Electronic Journal of Statistics 2018)**
  - Abishek Sankararaman and Francois Baccelli
  - [[paper]](hhttp://abishek90.github.io/CommDet.pdf)
  - [[Python Reference]](https://github.com/abishek90/Community-Detection-on-a-Spatial-Graph)

- **Community detection by L0-penalized graph Laplacian (Electronic Journal of Statistics 2018)**
  - Chong Chen, Ruibin Xi, and Nan Lin
  - [[paper]](https://projecteuclid.org/euclid.ejs/1528769122)
  - [[Matlab Reference]](https://github.com/ChongC1990/L0Lap)

- **Local Lanczos Spectral Approximation for Community Detection (ECML PKDD 2017)**
  - Pan Shi and He Kun and David Bindel and John Hopcroft
  - [[paper]](http://ecmlpkdd2017.ijs.si/papers/paperID161.pdf)
  - [[Python Reference]](https://github.com/PanShi2016/LLSA)
  
- **Uncovering the Small Community Structure in Large Networks: a Local Spectral Approach (WWW 2015)**
  - Li Yixuan and He Kun and David Bindel and John Hopcroft
  - [[paper]](https://arxiv.org/abs/1509.07715)
  - [[Python Reference]](https://github.com/YixuanLi/LEMON)
  
- **Asymptotic Analysis of the Stochastic Block Model for Modular Networks and its Algorithmic Applications (Physical Review 2011)**
  - Aurelien Decelle, Florent Krzakala, Cristopher Moore and Lenka Zdeborova
  - [[paper]](https://arxiv.org/abs/1109.3041)
  - [[C++]](https://github.com/junipertcy/sbm-bp)
  
- **Phase Transition in the Detection of Modules in Sparse Networks (Physical Review Letters 2011)**
  - Aurelien Decelle, Florent Krzakala, Cristopher Moore and Lenka Zdeborova
  - [[paper]](https://arxiv.org/abs/1102.1182)
  - [[C++]](https://github.com/junipertcy/sbm-bp)
  
## Temporal Methods

- **Sequential Detection of Temporal Communities by Estrangement Confinement (Scientific Reports 2012)**
  - Vikas Kawadia and Sameet Sreenivasan
  - [[paper]](https://www.nature.com/articles/srep00794)
  - [[Python Reference]](https://github.com/kawadia/estrangement)
  
## Cyclic Patterns

- **ComSim: A Bipartite Community Detection Algorithm Using Cycle and Node’s Similarity (Complex Networks 2017)**
  - Raphael Tack, Fabien Tarissan, and Jean-Loup Guillaume
  - [[paper]](https://link.springer.com/chapter/10.1007/978-3-319-72150-7_23)
  - [[C++]](https://github.com/rtackx/ComSim)
  
- **High Quality, Scalable and Parallel Community Detection for Large Real Graphs (WWW 2014)**
  - Arnau Prat-Perez David Dominguez-Sal and Josep-Lluis Larriba-Pey
  - [[Paper]](http://wwwconference.org/proceedings/www2014/proceedings/p225.pdf)
  - [[C++ Reference]](https://github.com/Het-SCD/Het-SCD)
  
- **GMAC: A Seed-Insensitive Approach to Local Community Detection (DaWak 2013)**
  - Lianhang Ma, Hao Huang, Qinming He, Kevin Chiew, Jianan Wu, and Yanzhe Che
  - [[Paper]](https://link.springer.com/chapter/10.1007/978-3-642-40131-2_26)
  - [[Python Reference]](https://github.com/SnehaManjunatha/Local-Community-Detection)
  
## Centrality and Cuts

- **Real-Time Community Detection in Large Social Networks on a Laptop (PLOS 2018)**
  - Benjamin Paul Chamberlain, Josh Levy-Kramer, Clive Humby, and Marc Peter Deisenroth
  - [[paper]](https://arxiv.org/pdf/1601.03958.pdf)
  - [[Python Reference]](https://github.com/melifluos/LSH-community-detection)
  
- **A Community Detection Algorithm Using Network Topologies and Rule-based Hierarchical Arc-merging Strategies (PLOS 2018)**
  - Yu-Hsiang Fu, Chung-Yuan Huang, and Chuen-Tsai Sun
  - [[paper]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0187603)
  - [[Python Reference]](https://github.com/yuhsiangfu/Hierarchical-Arc-Merging)
  
- **Detecting Community Structures in Social Networks by Graph Sparsification (CODS 2016)**
  - Partha Basuchowdhuri, Satyaki Sikdar, Sonu Shreshtha, and Subhasis Majumder
  - [[paper]](http://dl.acm.org/citation.cfm?id=2888479)
  - [[Python Reference]](https://github.com/satyakisikdar/spanner-comm-detection)
  
## Physics Inspired
- **Community Detection Using Preference Networks (Physica A 2018)**
  - Mursel Tasgin and Halu Bingol
  - [[paper]](https://arxiv.org/pdf/1708.08305.pdf)
  - [[Java Reference]](https://github.com/murselTasginBoun/CDPN)
  
- **Thermodynamics of the Minimum Description Length on Community Detection (ArXiv 2018)**
  - Juan Ignacio Perotti, Claudio Juan Tessone, Aaron Clauset and Guido Caldarelli
  - [[paper]](https://arxiv.org/pdf/1806.07005.pdf)
  - [[Python Reference]](https://github.com/jipphysics/bmdl_edm)

- **A Local Perspective on Community Structure in Multilayer Networks (Network Science 2017)**
  - Lucas GS Jeub, Michael Mahoney, Peter J Mucha and Mason A Porter
  - [[paper]](https://arxiv.org/pdf/1510.05185.pdf)
  - [[Python]](https://github.com/LJeub/LocalCommunities)
  
- **Defining Least Community as a Homogeneous Group in Complex Networks (Physica A 2015)**
  - Bin Jiang and Ding Ma
  - [[paper]](https://arxiv.org/pdf/1502.00284.pdf)
  - [[Python]](https://github.com/dingmartin/HeadTailCommunityDetection)
  
- **Think Locally, Act Locally: Detection of Small, Medium-Sized, and Large Communities in Large Networks (Physica Review E 2015)**
  - Lucas G. S. Jeub, Prakash Balachandran, Mason A. Porter, Peter J. Mucha, and Michael W. Mahoney
  - [[paper]](https://arxiv.org/abs/1403.3795v1)
  - [[Python]](https://github.com/LJeub/LocalCommunities)
  
## Others
  
- **Discovering Fuzzy Structural Patterns for Graph Analytics (IEEE TFS 2018)**
  - Tiantian He  and Keith C. C. Chan 
  - [[paper]](https://ieeexplore.ieee.org/document/8253904)
  - [[Reference]](https://github.com/he-tiantian/FSPGA)
  
- **An Overlapping Community Detection Algorithm Based on Density Peaks (NeuroComputing 2017)**
  - Xueying Bai, Peilin Yang and Xiaohu Shi
  - [[paper]](https://www.sciencedirect.com/science/article/pii/S092523121631400X)
  - [[Matlab Reference]](https://github.com/XueyingBai/An-overlapping-community-detection-algorithm-based-on-density-peaks)
  
- **Fast Heuristic Algorithm for Multi-scale Hierarchical Community Detection (ASONAM 2017)**
  - Eduar Castrillo, Elizabeth León and Jonatan Gómez
  - [[paper]](https://arxiv.org/abs/1707.02362)
  - [[Python Reference]](https://github.com/eduarc/HAMUHI)
  
- **A Smart Local Moving Algorithm for Large-Scale Modularity-Based Community Detection (The European Physical Journal B 2013)**
  - Ludo Waltman and Nees Jan Van Eck
  - [[paper]](https://link.springer.com/content/pdf/10.1140/epjb/e2013-40829-0.pdf)
  - [[Python]](https://github.com/chen198328/slm)
