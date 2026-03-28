---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


<p style="text-align: justify;font-family: Roboto;">
I am Qiuping Jiang, a Full Professor with the School of Information Science and Engineering, Ningbo University, Ningbo, Zhejiang, China. I received the Ph.D. degree in Signal and Information Processing from Ningbo University, in June 2018. From Jan. 2017 to Jun. 2018, I visited the School of Computer Science and Engineering, Nanyang Technological University, Singapore, advised by  Prof. <a href = "https://personal.ntu.edu.sg/wslin/Home.html" target = "_blank"> Weisi Lin </a> (IEEE Fellow). The visit was supported by the Chinese Scholarship Council.
</p>
<p style="text-align: justify;font-family: Roboto;">
I am the recipient of the World's Top 2% Scientists List by Stanford University and Elsevier (2022-2024), the Distinguished Youth Scholar Funding by Zhejiang Provincial Natural Science Foundation (2022), the Elsevier JVCI 2017 Best Paper Hornerable Mention Award (2017). In 2023, I was selected to be a Senior Member of IEEE.
</p>
<span class='anchor' id='r-interests'></span>




# <font color="#2B6ADD" > Researh Interests </font>
<p style="font-family: Roboto;">
Visual Perception Modeling,
Image/Video Quality Assessment,
Image/Video Quality Enhancement,
Immersive Multimedia Computing.</p>
<br>
<font color=Brown>
<i style="font-family: Roboto;">*Positions for Interns/Master/PhD's Programme*</i>
<br>
 <i style="font-family: Roboto;">We are looking for students, who are self-motivated and have a solid foundation in mathematics and programming. Please feel free to drop me an email (jiangqiuping@nbu.edu.cn) if you are interested.</i>
</font>

<span class='anchor' id='pub'></span>

# <font color="#2B6ADD"> Selected Publications </font>

<style>
  table {
    border-collapse: collapse;
  }
  table, th, td {
    border-color: transparent;
  }
</style>
<style>
  img {
    max-width: 250px;
  }
</style>
<b>Visual perception modeling</b>
<table align="center" border="none">
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/IJCV2026.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        <b>Qiuping Jiang</b>, Feiyang Liu, Ziqi Wang, Zhihua Wang, Shiqi Wang, Feng Shao, Guangtao Zhai, Weisi Lin. InvJND: Just Noticeable Difference Estimation via Deep Invertible Network. International Journal of Computer Vision (IJCV), 2026.
        <a href="https://link.springer.com/article/10.1007/s11263-025-02583-4">[Paper-Link]</a>
        <a href="https://github.com/Knife646/InvJND">[Code & Datasets-Link]</a>
        </p>
      </td>
  </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/CDi-Net.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Zhihua Wang, Keshuo Xu, Keyan Ding, <b>Qiuping Jiang</b>, Yifan Zuo, Zhangkai Ni, Yuming Fang. CD-iNet: Deep Invertible Network for Perceptual Image Color Difference Measurement. International Journal of Computer Vision (IJCV), 2024.
        <a href="https://link.springer.com/article/10.1007/s11263-024-02087-7">[Paper-Link]</a>
        <a href="https://github.com/hellooks/CD-iNet">[Code-Link]</a>
        </p>
      </td>
  </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/KLTJND.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        <b>Qiuping Jiang*</b>, Zhentao Liu, Shiqi Wang, Feng Shao, Weisi Lin. Toward Top-Down Just Noticeable Difference Estimation of Natural Images. IEEE Transactions on Image Processing (TIP), 2022. 
        <a href="https://arxiv.org/abs/2108.05058v2">[Paper-Link]</a>
        <a href="https://github.com/Zhentao-Liu/KLT-JND">[Code-Link]</a>
        </p>
      </td>
  </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/ResJND.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        <b>Qiuping Jiang</b>, Feiyang Liu, Zhihua Wang*, Shiqi Wang, Weisi Lin. Rethinking and Conceptualizing Just Noticeable Difference Estimation by Residual Learning. IEEE Transactions on Circuits Systems for Video Technology (TCSVT), 2024.
        <a href="https://ieeexplore.ieee.org/abstract/document/10526290">[Paper-Link]</a>
        <a href="https://github.com/Knife646/CD-Reasoning">[Code-Link]</a>
        </p>
      </td>
  </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/CD-Reasoning.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Zhihua Wang, Yu Long, <b>Qiuping Jiang</b>, Chao Huang, Xiaochun Cao. Harnessing Multi-modal Large Language Models for Measuring and Interpreting Color Differences. IEEE Transactions on Image Processing (TIP), 2025.
        <a href="https://ieeexplore.ieee.org/abstract/document/10820056">[Paper-Link]</a>
        <a href="https://github.com/LongYu-LY/CD-Reasoning">[Code-Link]</a>
        </p>
      </td>
  </tr>
</table>
<b>Image quality assessment</b>
<table align="center" border="none">
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/RealSRQ_KLTSRQA.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        <b>Qiuping Jiang</b>, Zhentao Liu*, Ke Gu, Feng Shao, Xinfeng Zhang, Hantao Liu, Weisi Lin. Single Image Super-Resolution Quality Assessment: A Real-World Dataset, Subjective Studies, and an Objective Metric. IEEE Transactions on Image Processing (TIP), 2022. <b>(Top50 Popular Articles)</b>
        <a href="https://ieeexplore.ieee.org/document/9727079">[Paper-Link]</a>
        <a href="https://github.com/Zhentao-Liu/RealSRQ-KLTSRQA">[Code & Dataset-Link]</a>
        </p>
      </td>
  </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/TIP19.png"/>
      </td>
      <td>
        <p style="text-align: justify">
       <b>Qiuping Jiang</b>, Feng Shao*, Wei Gao, Zhuo Chen, Gangyi Jiang, Yo-Sung Ho. Unified No-Reference Quality Assessment of Singly and Multiply Distorted Stereoscopic Images. IEEE Transactions on Image Processing (TIP), 2019. 
        <a href="https://ieeexplore.ieee.org/abstract/document/8540445/">[Paper-Link]</a>
        </p>
      </td>
  </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/CDTIQ.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        <b>Qiuping Jiang</b>, Xiwen Li, Xinyi Wang*, Zhihua Wang, Guangtao Zhai. Dataset and Metric for Quality Assessment of HDR Tone Mapping: Detail Visibility, Color Naturalness, and Overall Quality. IEEE Transactions on Multimedia (TMM), 2025.
        <a href="https://ieeexplore.ieee.org/abstract/document/10855594/">[Paper-Link]</a>
        <a href="https://github.com/zzeu001/CDTIQ">[Code & Dataset-Link]</a>
        </p>
      </td>
  </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/TMM2023.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Zhihua Wang, <b>Qiuping Jiang*</b>, Shanshan Zhao, Wensen Feng, Weisi Lin. Deep Blind Image Quality Assessment Powered by Online Hard Example Mining. IEEE Transactions on Multimedia (TMM), 2023.
        <a href="https://ieeexplore.ieee.org/abstract/document/10070789/">[Paper-Link]</a>
        <a href="https://github.com/wangzhihua520/IQA_with_OHEM">[Code-Link]</a>
        </p>
      </td>
  </tr>
   <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/LGGD+.png"/>
      </td>
      <td>
        <p style="text-align: justify">
       Zhenyu Peng, <b>Qiuping Jiang*</b>, Feng Shao, Wei Gao, Weisi Lin. LGGD+: Image Retargeting Quality Assessment by Measuring Local and Global Geometric Distortions. IEEE Transactions on Circuits Systems for Video Technology (TCSVT), 2022. 
        <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9537816">[Paper-Link]</a>
        </p>
      </td>
  </tr>
   <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/TCSVT2019.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        <b>Qiuping Jiang</b>, Feng Shao*, Weisi Lin, Gangyi Jiang. BLIQUE-TMI: Blind Quality Evaluator for Tone-Mapped Images Based on Local and Global Feature Analyses. IEEE Transactions on Circuits Systems for Video Technology (TCSVT), 2019. 
        <a href="https://ieeexplore.ieee.org/abstract/document/8214257/">[Paper-Link]</a>
        </p>
      </td>
  </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/StereoARS.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        <b>Qiuping Jiang</b>, Zhenyu Peng, Feng Shao*, Ke Gu, Yabin Zhang, Wenjun Zhang, Weisi Lin. StereoARS: Quality Evaluation for Stereoscopic Image Retargeting With Binocular Inconsistency Detection. IEEE Transactions on Broadcasting (TBC), 2022. 
        <a href="https://ieeexplore.ieee.org/abstract/document/9546995/">[Paper-Link]</a>
        </p>
      </td>
  </tr>
</table>
<b>Point cloud quality assessment and denoising</b>
<table align="center" border="none">
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/ACM.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Wu Chen, Hehe Fan, <b>Qiuping Jiang*</b>, Chao Huang, Yi Yang. Progressive Point Cloud Denoising with Cross-Stage Cross-Coder Adaptive Edge Graph Convolution Network. ACM International Conference on Multimedia (ACM MM), 2024. 
        <a href="https://openreview.net/pdf?id=LOJdqiqbAt">[Paper-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/DEHN.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Wu Chen, <b>Qiuping Jiang*</b>, Wei Zhou, Long Xu, Weisi Lin. Dynamic Hypergraph Convolutional Network for No-Reference Point Cloud Quality Assessment. IEEE Transactions on Circuits Systems for Video Technology (TCSVT), 2024.       
        <a href="https://ieeexplore.ieee.org/abstract/document/10549980">[Paper-Link]</a>
        <a href="https://github.com/chenwuwq/DHCN">[Code-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/wu_tmm.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Wu Chen, <b>Qiuping Jiang*</b>, Wei Zhou, Feng Shao, Guangtao Zhai, Weisi Lin. No-Reference Point Cloud Quality Assessment via Graph Convolutional Network. IEEE Transactions on Multimedia (TMM), 2024.     
        <a href="https://ieeexplore.ieee.org/abstract/document/10814096/">[Paper-Link]</a>
        <a href="https://github.com/chenwuwq/GC-PCQA">[Code-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/Plain.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Xiongli Chai, Feng Shao, Baoyang Mu, Hangwei Chen, <b>Qiuping Jiang</b>,  Yo-Sung Ho. Plain-PCQA: No-Reference Point Cloud Quality Assessment by Analysis of Plain Visual and Geometrical Components. IEEE Transactions on Circuits Systems for Video Technology (TCSVT), 2024.     
        <a href="https://ieeexplore.ieee.org/abstract/document/10381826/">[Paper-Link]</a>
        </p>
      </td>
    </tr>
</table>
<b>Underwater/low-light image processing</b>
<table align="center" border="none">
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/TIP2025_03.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Huiyang Wu, <b>Qiuping Jiang*</b>, Zongwei Wu, Runmin Cong, Cédric Demonceaux, Yi Yang. High-Resolution Underwater Creature Segmentation. IEEE Transactions on Image Processing (TIP), 2025.
        <a href="https://ieeexplore.ieee.org/document/11267001">[Paper-Link]</a>
        <a href="https://github.com/WHYfromNUT/RADAR">[Code & Datasets-Link]</a>
        </p>
      </td>
    </tr>
   <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/TIP2025_02222.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Jingchun Zhou, Dehuan Zhang, Zongxin He, Qilin Gai, <b>Qiuping Jiang*</b>. Multi-Prior Fusion Transfer Plugin for Adapting In-Air Models to Underwater Image Enhancement and Detection. IEEE Transactions on Image Processing (TIP), 2025. 
        <a href="https://ieeexplore.ieee.org/document/11267029?denied=">[Paper-Link]</a>
        <a href="https://github.com/zhoujingchun03/IA2U">[Code-Link]</a>
        </p>
      </td>
    </tr>
   <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/HCLR-Net.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Jingchun Zhou, Jiaming Sun, Chongyi Li, <b>Qiuping Jiang*</b>, Man Zhou, Kin-Man Lam, Weishi Zhang, Xianping Fu. HCLR-net: Hybrid contrastive learning regularization with locally randomized perturbation for underwater image enhancement. International Journal of Computer Vision (IJCV), 2024. <b>(ESI Highly Cited Paper)</b>🏆
        <a href="https://link.springer.com/article/10.1007/s11263-024-01987-y">[Paper-Link]</a>
        <a href="https://github.com/zhoujingchun03/HCLR-Net">[Code-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/TIP2025.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Yi Liu, <b>Qiuping Jiang*</b>, Xingbo Li, Ting Luo, Wenqi Ren. Toward Better Than Pseudo-Reference in Underwater Image Enhancement. IEEE Transactions on Image Processing (TIP), 2025. 
        <a href="https://ieeexplore.ieee.org/document/11176916">[Paper-Link]</a>
        <a href="[https://github.com/lewis081/PSPL">[Code-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/EDANet.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        <b>Qiuping Jiang</b>, Yuese Gu, Zongwei Wu, Chongyi Li, Huan Xiong, Feng Shao, Zhihua Wang*. Deep Underwater Image Quality Assessment with Explicit Degradation Awareness Embedding. IEEE Transactions on Image Processing (TIP), 2025. 
        <a href="https://ieeexplore.ieee.org/document/10897305">[Paper-Link]</a>
        <a href="https://github.com/yia-yuese/EDANet">[Code-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/MCOLE.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        <b>Qiuping Jiang</b>, Xiao Yi, Li Ouyang, Jingchun Zhou, Zhihua Wang*. Towards Dimension-Enriched Underwater Image Quality Assessment. IEEE Transactions on Circuits Systems for Video Technology (TCSVT), 2024. 
        <a href="https://ieeexplore.ieee.org/document/10689635">[Paper-Link]</a>
        <a href="https://github.com/0117Tzx/MCOLE">[Code-Link]</a>
        </p>
      </td>
    </tr>
   <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/TCSVT22.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        <b>Qiuping Jiang*</b>, Yuese Gu, Chongyi Li, Runmin Cong, Feng Shao. Underwater Image Enhancement Quality Evaluation: Benchmark Dataset and Objective Metric. IEEE Transactions on Circuits Systems for Video Technology (TCSVT), 2022. <b>(ESI Highly Cited Paper)</b>🏆
        <a href="https://ieeexplore.ieee.org/document/9749233/">[Paper-Link]</a>
        <a href="https://github.com/yia-yuese/SAUD-Dataset">[Code-Link]</a>
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/DA.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Shihui Wu, <b>Qiuping Jiang*</b>, Guanghui Yue, Shiqi Wang, Guangtao Zhai. Generalizable Underwater Image Quality Assessment With Curriculum Learning-Inspired Domain Adaption. IEEE Transactions on Broadcasting (TBC), 2024. 
        <a href="https://ieeexplore.ieee.org/abstract/document/10817078">[Paper-Link]</a>
        <a href="https://github.com/zzeu001/CLIDA">[Code-Link]</a>
        </p>
      </td>
    </tr>
   <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/TMM2024.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        <b>Qiuping Jiang</b>, Yaozu Kang, Zhihua Wang*, Wenqi Ren, Chongyi Li. Perception-Driven Deep Underwater Image Enhancement Without Paired Supervision. IEEE Transactions on Multimedia (TMM), 2024. <b>(ESI Highly Cited Paper)</b>🏆
        <a href="https://ieeexplore.ieee.org/abstract/document/10319078">[Paper-Link]</a>
        <a href="https://github.com/59Kkk/PDDNet">[Code-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/CCL-Net.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Yi Liu, <b>Qiuping Jiang*</b>, Xinyi Wang, Ting Luo, Jingchun Zhou. Underwater Image Enhancement with Cascaded Contrastive Learning. IEEE Transactions on Multimedia (TMM), 2024. 
        <a href="https://ieeexplore.ieee.org/abstract/document/10814077">[Paper-Link]</a>
        <a href="https://github.com/lewis081/CCL-Net">[Code-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/SPDF.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Yaozu Kang, <b>Qiuping Jiang*</b> Chongyi Li, Wenqi Ren, Hantao Liu, Pengjun Wang*. A Perception-Aware Decomposition and Fusion Framework for Underwater Image Enhancement. IEEE Transactions on Circuits and Systems for Video Technology (TCSVT), 2023. <b>(ESI Highly Cited Paper)</b>🏆<b>(ESI Hot Paper)</b>🔥
        <a href="https://ieeexplore.ieee.org/abstract/document/9895452">[Paper-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/UDCN.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        <b>Qiuping Jiang</b>, Yudong Mao, Runmin Cong, Wenqi Ren, Chao Huang*, Feng Shao. Unsupervised Decomposition and Correction Network for Low-Light Image Enhancement. IEEE Transactions on Intelligent Transportation Systems (TITS), 2022. 
        <a href="https://ieeexplore.ieee.org/document/9757816">[Paper-Link]</a>
        <a href="https://github.com/myd945/UDCN">[Code-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/jin_tcsvt.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Jianhui Jin, <b>Qiuping Jiang*</b>, Qingyuan Wu, Binwei Xu, Runmin Cong. Underwater Salient Object Detection via Dual-stage Self-paced Learning and Depth Emphasis. IEEE Transactions on Circuits and Systems for Video Technology (TCSVT), 2024. 
        <a href="https://ieeexplore.ieee.org/document/10744585/">[Paper-Link]</a>
        <a href="https://github.com/NIT-JJH/SPDE">[Code-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/BCMNet.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Jinguang Cheng, Zongwei Wu, Shuo Wang, Cédric Demonceaux, <b>Qiuping Jiang*</b>. Bidirectional Collaborative Mentoring Network for Marine Organism Detection and Beyond. IEEE Transactions on Circuits and Systems for Video Technology (TCSVT), 2023. 
        <a href="https://ieeexplore.ieee.org/document/10093775/">[Paper-Link]</a>
        <a href="https://github.com/chasecjg/BCMNet">[Code-Link]</a>
        </p>
      </td>
    </tr>
</table>
<table align="center" border="none">
<b>Image segmentation, object detection and anomaly detection</b>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/TNNLS2025.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Wujie Zhou, Bitao Jian, Yuanyuan liu, <b>Qiuping Jiang*</b>. Multiattentive Perception and Multilayer Transfer Network Using Knowledge Distillation for RGB-D Indoor Scene Parsing. IEEE Transactions on Neural Networks and Learning Systems (TNNLS), 2025.
        <a href="https://ieeexplore.ieee.org/document/11029670">[Paper-Link]</a>
        <a href="https://github.com/XUEXIKUAIL/MPMTNet">[Code-Link]</a>
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/Chaohuangtmm2025.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Chao Huang, Weiliang Huang, <b>Qiuping Jiang*</b>, Wei Wang, Jie Wen, Bob Zhang. Multimodal Evidential Learning for Open-World Weakly-Supervised Video Anomaly Detection. IEEE Transactions on Multimedia (TMM), 2025.
        <a href="https://ieeexplore.ieee.org/document/10948323">[Paper-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/FSANet.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        <b>Qiuping Jiang</b>, Jinguang Cheng, Zongwei Wu, Runmin Cong, Radu Timofte. High-Precision Dichotomous Image Segmentation With Frequency and Scale Awareness. IEEE Transactions on Neural Networks and Learning Systems (TNNLS), 2024.
        <a href="https://ieeexplore.ieee.org/document/10638122">[Paper-Link]</a>
        <a href="https://github.com/chasecjg/FSANet">[Code-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/SAM.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Binwei Xu, <b>Qiuping Jiang*</b>, Xing Zhao, Chenyang Lu, Haoran Liang, Ronghua Liang. Multidimensional Exploration of Segment Anything Model for Weakly Supervised Video Salient Object Detection. IEEE Transactions on Circuits Systems for Video Technology (TCSVT), 2024.
        <a href="https://ieeexplore.ieee.org/abstract/document/10443051">[Paper-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/FSM.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Binwei Xu, <b>Qiuping Jiang*</b>, Haoran Liang, Dingwen Zhang, Ronghua Liang, Peng Chen. Learning Video Salient Object Detection Progressively from Unlabeled Videos. IEEE Transactions on Multimedia (TMM), 2024.
        <a href="https://ieeexplore.ieee.org/abstract/document/10812846">[Paper-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/WaveNet.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Wujie Zhou, Fan Sun, <b>Qiuping Jiang*</b>, Runmin Cong, Jenq-Neng Hwang. WaveNet: Wavelet Network With Knowledge Distillation for RGB-T Salient Object Detection. IEEE Transactions on Image Processing (TIP), 2023. <b>(ESI Highly Cited Paper)</b>🏆
        <a href="https://ieeexplore.ieee.org/document/10127616">[Paper-Link]</a>
        <a href="https://github.com/nowander/WaveNet">[Code-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/DCNet.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Guanghui Yue, Houlu Xiao, Hai Xie, Tianwei Zhou, Wei Zhou, Weiqing Yan, Baoquan Zhao, Tianfu Wang, <b>Qiuping Jiang*</b>. Dual-Constraint Coarse-to-Fine Network for Camouflaged Object Detection. IEEE Transactions on Circuits Systems for Video Technology (TCSVT), 2024.
        <a href="https://ieeexplore.ieee.org/abstract/document/10262011">[Paper-Link]</a>
        </p>
      </td>
    </tr>
  <tr>
      <td>
        <img align="left" width="700" height="400" src="../images/PRBE-Net.png"/>
      </td>
      <td>
        <p style="text-align: justify">
        Guanghui Yue, Shangjie Wu, Tianwei Zhou, Gang Li, Jie Du, Yu Luo, <b>Qiuping Jiang*</b>. Progressive Region-to-Boundary Exploration Network for Camouflaged Object Detection. IEEE Transactions on Multimedia (TMM), 2024.
        <a href="https://ieeexplore.ieee.org/abstract/document/10262011">[Paper-Link]</a>
        </p>
      </td>
    </tr>
  
  </table>

<!--    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/HCLR_Net.png"/>
      </td>
      <td>
        <p text-align="left">
        Jingchun Zhou, Jiaming Sun, Chongyi Li, <b>Qiuping Jiang*</b>, Man Zhou, Kin-Man Lam, Weishi Zhang. HCLR-Net: Hybrid Contrastive Learning Regularization with Locally Randomized Perturbation for Underwater Image Enhancement. International Journal of Computer Vision (IJCV), 2024.
        <b>(ESI Highly Cited Paper)</b>
        <a href="https://link.springer.com/article/10.1007/s11263-024-01987-y">[Paper-Link]</a>
        <a href="https://github.com/zhoujingchun03/HCLR-Net">[Code-Link]</a>
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/IJCV2023.png"/>
      </td>
      <td>
        <p text-align="left">
        Jingchun Zhou, Qian Liu, <b>Qiuping Jiang</b>, Wenqi Ren, Kin-Man Lam*, Weishi Zhang*. Underwater Camera: Improving Visual Perception Via Adaptive Dark Pixel Prior and Color Correction. International Journal of Computer Vision (IJCV), 2024. 
        <a href="https://link.springer.com/article/10.1007/s11263-023-01853-3">[Paper-Link]</a>
        </p>
      </td>
    </tr> -->
For more papers, please kindly refer to [my Google Scholar page](https://scholar.google.com/citations?user=PbPTiKYAAAAJ&hl=zh-CN&oi=ao).

<span class='anchor' id='ha'></span>

# <font color="#2B6ADD"> Honors and Awards </font>
- "Robust Enhancement and Precise Evaluation of Ubiquitous Low-Quality Visual Information" project, <b>awarded First Prize of Zhejiang Provincial Natural Science Award 2024 (Lead Researcher)</b>
- "Theory and Methods for Visual Quality Enhancement of Underwater Optical Imaging" project, <b>awarded Second Prize of Ningbo Municipal Natural Science Award 2024 (Lead Researcher)</b>


<span class='anchor' id='Service'></span>

# <font color="#2B6ADD"> Academic Service </font>
+ **Associate Editors:**
  - Pattern Recognition, 2024~
  - Displays, 2024~
  - Journal of Visual Communication and Image Representation, 2023~
  - IET Image Processing, 2022~
+ **(Senior) Program Committee Member:**
  - International Joint Conference on Artificial Intelligence (IJCAI)
  - AAAI Conference on Artificial Intelligence (AAAI)
  - ACM International Conference on Multimedia (ACM MM) 
  - IEEE International Conference on Multimedia &amp; Expo (ICME)
  - IEEE International Conference on Image Processing (ICIP)
  - IEEE International Conference on Visual Communiaction and Image Processing (VCIP)
+ **Reviewer for Journals:**
  - IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)
  - ACM Transactions on Graphics (TOG)
  - IEEE Transactions on Visualization and Computer Graphics (TVCG)
  - IEEE Transactions on Image Processing (TIP)
  - IEEE Transactions on Neural Networks and Learning Systems (TNNLS)
  - IEEE Transactions on Cybernetics (TCYB)
  - IEEE Transactions on Circuits Systems for Video Technology (TCSVT)
  - IEEE Transactions on Multimedia (TMM)

  

