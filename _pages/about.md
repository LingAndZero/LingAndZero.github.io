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

I am currently a PhD student in the School of Software Technology, Zhejiang University (ZJU), advised by [Prof. Hailiang Zhao](http://hliangzhao.me/).

Prior to this, I obtained both my MS and BS degrees at East China Normal University (ECNU), under the supervision of [Prof. Mingsong Chen](https://faculty.ecnu.edu.cn/_s43/cms_en/main.psp).

My current research primarily focuses on the following areas:

* ***Out-of-Distribution Detection***
    * DNN-based and VLM-based methods
    * Multiple data modalities, including images, text, audio, and graph
* ***Federated Learning***
    * Data, device and model heterogeneity 
    * Model security
* ***Trustworthy Intelligent System***
    * Backdoor defense 
    * Anomaly detection
    * Machine unlearning

 <!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->
 If you are interested with my research, feel free to contact me by email: zwling@zju.edu.cn.


<!-- # 🔥 News
- *2025.03*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

- (<span style="color:green">CCF-C</span>) Tian Liu, **Zhiwei Ling**, Ziqi Wang, Jiahui Zhai, Chenggang Shan, Zhen Yang, Bin Yang, FedCAD: Federated Learning with Clustering, Adaptive Selection, and Delayed Aggregation for Heterogeneous IoT Environments. IEEE Internet of Things Journal (IoTJ), 2026. (IF=8.9)

- (<span style="color:red">CCF-A</span>) **Zhiwei Ling**, Yachen Chang, Hailiang Zhao, Xinkui Zhao, Kingsum Chow, Shuiguang Deng, [CADRef: Robust Out-of-Distribution Detection via Class-Aware Decoupled Relative Feature Leveraging](https://openaccess.thecvf.com/content/CVPR2025/papers/Ling_CADRef_Robust_Out-of-Distribution_Detection_via_Class-Aware_Decoupled_Relative_Feature_Leveraging_CVPR_2025_paper.pdf). IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), Nashville, USA, June 11-15, 2025. (Acceptance Rate: 22.1%)

- (<span style="color:red">CCF-A</span>) Jun Xia, Zhihao Yue, Yingbo Zhou, **Zhiwei Ling**, Yiyu Shi, Xian Wei, Mingsong Chen, [Waveattack: Asymmetric frequency obfuscation-based backdoor attacks against deep neural networks](https://proceedings.neurips.cc/paper_files/paper/2024/file/4ce18228ececb78bca04cbce069891b1-Paper-Conference.pdf). Conference on Neural Information Processing Systems (NeurIPS), Vancouver, Canada, December 10-15, 2024. (Acceptance Rate: 25.8%)

- (<span style="color:red">CCF-A</span>) Ming Hu, Peiheng Zhou, Zhihao Yue, **Zhiwei Ling**, Yihao Huang, Anran Li, Yang Liu, Xiang Lian, Mingsong Chen, [FedCross: Towards accurate federated learning via multi-model cross-aggregation](https://ieeexplore.ieee.org/document/10597740/). IEEE International Conference on Data Engineering (ICDE), Utrecht, The Netherlands, May 13-16, 2024. (Acceptance Rate: 25.4%)

- (<span style="color:green">CCF-C</span>) **Zhiwei Ling**, Zhihao Yue, Jun Xia, Ting Wang, Mingsong Chen, Xiang Lian, [FedEntropy: Efficient Federated Learning for Non-IID Scenarios Using Maximum Entropy Judgment-based Client Selection](https://ieeexplore.ieee.org/abstract/document/10491750). International Symposium on Parallel and Distributed Processing with Applications (ISPA), Wuhan, China, December 21-24, 2023. (Acceptance Rate: 19.6%)

- (<span style="color:red">CCF-A</span>) Yutong Ye, **Zhiwei Ling**, Yaning Yang, Xian Wei, Chen Cheng, Su Chen, Mingsong Chen, [Brief industry paper: Rtlight: Digital twin-based real-time federated traffic signal control](https://ieeexplore.ieee.org/abstract/document/10406112). IEEE Real-Time Systems Symposium (RTSS), Taipei, China, December 5-8, 2023. (Acceptance Rate: 28.0%)

- (<span style="color:red">CCF-A</span>) Zhihao Yue, Jun Xia, **Zhiwei Ling**, Ming Hu, Ting Wang, Xian Wei, Mingsong Chen, [Model-contrastive learning for backdoor elimination](https://dl.acm.org/doi/abs/10.1145/3581783.3612415). ACM International Conference on Multimedia (MM), Ottawa, Canada, October 29-November 3, 2023. (Acceptance Rate: 29.3%)

- (<span style="color:green">CCF-C</span>) Tian Liu, Jun Xia, **Zhiwei Ling**, Xin Fu, Shui Yu, Mingsong Chen, [Efficient federated learning for AIoT applications using knowledge distillation](https://ieeexplore.ieee.org/abstract/document/9987477). IEEE Internet of Things Journal (IoTJ), 2023. (IF=8.2)

- (<span style="color:red">CCF-A</span>) Jun Xia, Tian Liu, **Zhiwei Ling**, Ting Wang, Xin Fu, Mingsong Chen, [PervasiveFL: Pervasive federated learning for heterogeneous IoT systems](https://ieeexplore.ieee.org/abstract/document/9925684). IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2022. (IF=2.9)


# 🎖 Honors and Awards

- 2025 China Service Computing Innovation Competition, Second Prize (2025 CCF中国服务计算创新大赛暨深信服杯算法竞赛决赛, 二等奖)
- 2023 China International College Students “Internet+” Innovation and Entrepreneurship Competition, Silver Award in Shanghai (2023 中国国际“互联网+”大学生创新创业大赛, 上海赛区银奖) 
- 2022 National College IoT Design Competition (Huawei Cup),  Third Prize in Final (2022 全国大学生物联网设计竞赛（华为杯）, 全国总决赛三等奖) 
- 2022 National College IoT Design Competition (Huawei Cup),  First Prize in East China Region (2022 全国大学生物联网设计竞赛（华为杯）, 华东赛区一等奖) 
- 2022 China Post-Graduate Mathematical Contest in Modeling, Second Prize (2022 “中国光谷·华为杯”第十九届中国研究生数学建模竞赛, 二等奖)

# ✍️ Academic Service

Conference Reviewer for:
- European Conference on Computer Vision (ECCV), 2026
- IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026
- Conference on Neural Information Processing Systems (NeurIPS), 2025
- International Conference on Service Oriented Computing (ICSOC), 2025

Journal Reviewer for:
- International Journal of Computer Vision (IJCV)
- IEEE Transactions on Mobile Computing (TMC)
- IEEE Transactions on Industrial Informatics (TII)
- IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD)
- IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)
- IEEE Internet of Things Journal (IoTJ)
- IEEE Signal Processing Letters 
- IEEE Access


# 📖 Educations
- *2024.09 - (now)*, **Ph.D** at Zhejiang University (ZJU), Hangzhou, China. 
- *2021.09 - 2024.06*, **M.S** at East China Normal University (ECNU), Shanghai, China.
- *2017.09 - 2021.06*, **B.S** at East China Normal University (ECNU), Shanghai, China. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->