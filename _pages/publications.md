---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Preprint
<b>[Winner-Take-All Column Row Sampling for Memory Efficient Adaptation of Language Model](https://arxiv.org/pdf/2305.15265.pdf)</b>
<br><b>Zirui Liu\*</b>, Guanchu Wang\*, Shaochen Zhong, Zhaozhuo Xu, Daochen Zha, Ruixiang Tang, Zhimeng Jiang, Kaixiong Zhou, Vipin Chaudhary, Shuai Xu, Xia Hu

<b>[Compress, Then Prompt: Improving Accuracy-Efficiency Trade-off of LLM Inference with Transferable Prompt](https://arxiv.org/pdf/2305.11186.pdf)</b>
<br><b>Zirui Liu\*</b>, Zhaozhuo Xu\*, Beidi Chen, Yuxin Tang, Jue Wang, Kaixiong Zhou, Xia Hu, Anshumali Shrivastava

## 2023
<b>[Editable Graph Neural Network for Node Classifications](https://arxiv.org/abs/2305.15529)</b>
<br><b>Zirui Liu</b>, Zhimeng Jiang, Shaochen Zhong, Kaixiong Zhou, Li Li, Rui Chen, Soo-Hyun Choi, Xia Hu <b>MLG Workshop @ KDD</b>

<b>[DSpar: Embarrassingly Simple Strategy for Efficient GNN training and inference via Degree-based Sparsification](https://openreview.net/forum?id=SaVEXFuozg&referrer=%5BTMLR%5D(%2Fgroup%3Fid%3DTMLR))</b>
<br><b>Zirui Liu</b>, Kaixiong Zhou, Zhimeng Jiang, Li Li, Rui Chen, Soo-Hyun Choi, and Xia Hu <b>TMLR</b>

<b>[Retiring ∆DP: New Distribution-Level Metrics for Demographic Parity.](https://openreview.net/forum?id=LjDFIWWVVa&referrer=%5BAuthor%20Console%5D)</b>
Xiaotian Han*, Zhimeng Jiang*, Hongye Jin*, <br><b>Zirui Liu</b>, Na Zou, Qifan Wang, Xia Hu<b>TMLR</b>

<b>[PME: Pruning-based Multi-size Embedding for Recommender Systems.](https://www.frontiersin.org/articles/10.3389/fdata.2023.1195742/full)</b>
<br><b>Zirui Liu</b>, , Qingquan Song, Li Li, Soo-Hyun Choi, Rui Chen, and Xia Hu. <b>Frontier in Big Data</b>

<b>[RSC: Accelerating Graph Neural Networks Training via Randomized Sparse Computations](https://arxiv.org/abs/2210.10737)</b>
<br><b>Zirui Liu</b>, Shengyuan Chen, Kaixiong Zhou, Daochen Zha, Xiao Huang, Xia Hu <b>ICML 2023</b>

<b>[DIVISION: Memory Efficient Training via Dual Activation Precision](https://arxiv.org/abs/2208.04187)</b>
<br>Guanchu Wang, <b>Zirui Liu</b>, Zhimeng Jiang, Ninghao Liu, Na Zou, Xia Hu <b>ICML 2023</b>

<b>[Pre-train and Search: Efficient Embedding Table Sharding with Pre-trained Neural Cost Models]()
</b><br> Daochen Zha, Louis Feng, Liang Luo, Bhargav Bhushanam, <b>Zirui Liu</b>, Yusuo Hu, Jade Nie, Yuzhen Huang, Yuandong Tian, Arun Kejariwal, Xia Hu <b>MLSys 2023</b>

## 2022
<b>[DreamShard: Generalizable Embedding Table Placement for Recommender Systems]()
</b><br> Daochen Zha, Louis Feng, Qiaoyu Tan, <b>Zirui Liu</b>, Kwei-Herng Lai, Bhargav Bhushanam, Yuandong Tian, Arun Kejariwal, Xia Hu <b>Neurips 2022</b>

<b>[A Comprehensive Study on Large-Scale Graph Training: Benchmarking and Rethinking](https://openreview.net/forum?id=2QrFr_U782Z)
</b><br>Keyu Duan, <b>Zirui Liu</b>, Peihao Wang, Wenqing Zheng, Kaixiong Zhou, Tianlong Chen, Xia Hu, Zhangyang Wang. <b>NeurIPS 2022 Datasets and Benchmarks</b>


<b>[EXACT: Scalable Graph Neural Networks Training via Extreme Activation Compression](https://openreview.net/pdf?id=vkaMaq95_rX)</b>
<br><b>Zirui Liu</b>, Kaixiong Zhou, Yang Fan, Li Li, Rui Chen, Xia Hu. <b>ICLR 2022</b>

<b>[An Information Fusion Approach to Learning with Instance-Dependent Label Noise](https://openreview.net/pdf?id=ecH2FKaARUp)
</b><br>Zhimeng Jiang, Kaixiong Zhou, <b>Zirui Liu</b>, Li Li, Rui Chen, Soo-Hyun Choi, Xia Hu. <b>ICLR 2022</b>

## 2021

<b>[DivAug: Plug-in Automated Data Augmentation with Explicit Diversity Maximization](https://arxiv.org/abs/2103.14545)</b>
<br><b>Zirui Liu\*</b>, Haifeng Jin\*, Ting-Hsiang Wang, Kaixiong Zhou, Xia Hu. <b>ICCV 2021</b>

<b>[Mitigating Gender Bias in Captioning Systems](https://arxiv.org/abs/2006.08315)
</b><br>Ruixiang Tang, Mengnan Du, Yuening Li, <b>Zirui Liu</b> and Xia Hu. <b>WWW 2021</b>

## 2020
<b>[AutoRec: An Automated Recommender System](https://dl.acm.org/doi/abs/10.1145/3383313.3411529)
</b><br>Ting-Hsiang Wang, Xia Hu, Haifeng Jin, Qingquan Song, Xiaotian Han, <b>Zirui Liu</b>, and Xia Hu. <b>RecSys 2020</b>

<b> [Towards Interaction Detection Using Topological Analysis on Neural Networks](https://proceedings.neurips.cc/paper/2020/file/473803f0f2ebd77d83ee60daaa61f381-Paper.pdf)
</b><br><b>Zirui Liu</b>, Qingquan Song, Kaixiong Zhou, Ting-Hsiang Wang, Ying Shan and Xia Hu. <b>Neurips 2020</b>

## Paper related to Control Science
<b>[Motor speed signature analysis for local bearing fault detection with noise cancellation based on improved drive algorithm](https://ieeexplore.ieee.org/abstract/document/8741216/)
</b><br>Ming Yang, Na Chai, <b>Zirui Liu</b>, Boyang Ren, Dianguo Xu. <b>IEEE Transactions on Industrial Electronics</b>

<b>[An algorithm for online inertia identification and load torque observation via adaptive Kalman observer-recursive least squares](https://www.mdpi.com/1996-1073/11/4/778)
</b><br>Ming Yang, <b>Zirui Liu</b>, Jiang Long, Wanying Qu, Dianguo Xu. <b>Energies</b>

<b>[Speed measurement error reduction via adaptive strong tracking Kalman filters](https://ieeexplore.ieee.org/abstract/document/8080941/)
</b><br><b>Zirui Liu</b>, Ming Yang, Jiang Long, Dianguo Xu. <b>ITEC Asia-Pacific 2017 </b>

<b>[Current sensorless predictive control based on extended Kalman filter for PMSM drives](https://ieeexplore.ieee.org/abstract/document/8080902/)
</b><br>Yingqiang Li, Ming Yang, Jiang Long, <b>Zirui Liu</b>, Dianguo Xu. <b>ITEC Asia-Pacific 2017 </b>

<b>[A novel algorithm for on-line inertia identification via adaptive recursive least squares](https://ieeexplore.ieee.org/abstract/document/8216502/)
</b><br><b>Zirui Liu</b>, Ming Yang, Dianguo Xu. <b>IECON 2017 </b>
