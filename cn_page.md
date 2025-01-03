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

本科就读于中国农业大学，研究生就读于华中农业大学。
硕士期间（2020-2022）在[武玲娟教授](https://www.researchgate.net/profile/Lingjuan-Wu)的指导下研究**可解释稳健机器学习**算法设计以及在**硬件安全领域**的应用；博士期间（2022-）在[陈洪教授](https://chenhongml.github.io/)的指导下研究**可解释稳健优化算法设计**与**算法统计理论分析**。预计于2026年中旬毕业。

我的研究方向主要包括：

- 自动化机器学习（双层优化、元学习）

- 可解释/鲁棒算法设计（鲁棒度量函数设计、稀疏可加建模）

- 硬件安全应用（基于 自然语言与拓扑结构 等策略的硬件特洛伊木马检测）
  
如果你对我的研究方向感兴趣,请联系: zhangxuelin@webmail.hzau.edu.cn

# 🔥 新闻

- *2025.01*: &nbsp;🎉🎉  合作论文被**TCAD**(**ccf-A**类期刊)接收. 

- *2024.12*: &nbsp;🎉🎉  参加CCF武汉2024年会暨第八届优秀博士论坛并作口头汇报.

- *2024.11*: &nbsp;🎉🎉  荣获 **博士国家奖学金**.

# 📝 机器学习方向论文

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[8] ICDM 2024 [ccf-B]</div><img src='images/ICDM2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generalized Sparse Additive Model with Unknown Link Function](https://icdm2024.org/accepted_papers/)

Peipei Yuan, Xinge You*, Hong Chen, **Xuelin Zhang**, and Qinmu Peng. 

**IEEE International Conference on Data Mining 2024 [C]**

- 在这项工作中，我们提出了一种新型的广义加性模型，该模型具有一个通过双层方案自动学习的灵活链接函数。所提出的模型能够进行非线性逼近、隐藏交互和特征选择，同时也享有算法收敛的理论保证。

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[7] ESWA 2024 [sci-1 Top]</div><img src='images/eswa24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Error Density-dependent Empirical Risk Minimization](https://www.sciencedirect.com/science/article/pii/S0957417424011989)

Hong Chen*, **Xuelin Zhang**, Tieliang Gong, Bin Gu, Feng Zheng. 

**Expert Systems With Applications 2024 [J]**

- 这篇论文缓解了依赖误差值的稳健学习准则的局限性，并提出了误差密度依赖的经验风险最小化框架，用于对抗异常数据的稳健回归与分类。我们的方法的有效性通过充分的实证评估得到了验证。实现代码可以在以下网址找到： [https://github.com/zhangxuelincode/EDERM](https://github.com/zhangxuelincode/EDERM)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[6] IJCAI 2024 [ccf-A]</div><img src='images/ijcai24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-grained Analysis of Stability and Generalization for Stochastic Bilevel Optimization](https://www.ijcai.org/proceedings/2024/609)

**Xuelin Zhang**, Hong Chen*, Bin Gu, Tieliang Gong, Feng Zheng. 

**International Joint Conference on Artificial Intelligence 2024 [C] (Oral)**

- 在这篇论文中，我们基于（平均参数）算法稳定性技术，对一阶基于梯度的双层优化方法进行了系统的泛化分析。验证代码提供在: [https://github.com/zhangxuelincode/BilevelOptimization](https://github.com/zhangxuelincode/BilevelOptimization)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[5] IJCNN 2024 [ccf-C]</div><img src='images/ijcnn24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Improved Concentration Bound for CVaR](https://ieeexplore.ieee.org/abstract/document/10650860)

Peng Sima, Hao Deng*, **Xuelin Zhang**, Hong Chen. 

**International Joint Conference on Neural Networks 2024 [C]**

- 这篇论文介绍了一种新颖的估计器，该估计器依赖于风险价值（Value at Risk，简称VaR）的估计，并研究了在独立场景中的集中不等式，其中底层分布是次高斯（sub-Gaussian）、次指数（sub-exponential）或重尾（heavy-tailed）的。我们推导出的不等式是双边的，表现出指数衰减，并且不局限于有界场景.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[4] FCS 2023 [ccf-B]</div><img src='images/fcs23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neural Partially Linear Additive Model](https://link.springer.com/article/10.1007/s11704-023-2662-3)

Liangxuan Zhu, Han Li*, **Xuelin Zhang**, Lingjuan Wu, Hong Chen. 

**Frontiers of Computer Science 2023 [J]**

- 这篇论文提出了一种神经部分线性加性模型，该模型能够在神经网络中自动区分不显著、线性和非线性特征，从而实现模型级别的可解释性.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[3] AAAI 2023 [ccf-A]</div><img src='images/aaai23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Stepdown SLOPE for Controlled Feature Selection](https://ojs.aaai.org/index.php/AAAI/article/view/26050)

Jingxuan Liang, **Xuelin Zhang**, Hong Chen*, Weifu Li, Xin Tang. 

**Association for the Advancement of Artificial Intelligence 2023 [C] (Oral)**

- 这篇论文超越了之前对排序L-One惩罚估计（Sorted L-One Penalized Estimation，简称SLOPE）的担忧，SLOPE仅限于控制假发现率（False Discovery Rate，简称FDR）.论文考虑了基于逐步下降的SLOPE，以控制k个或更多假拒绝的概率（k-FWER）和假发现比例（False Discovery Proportion，简称FDP）.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[2] APIN 2023 [sci-2]</div><img src='images/apin23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust variable structure discovery based on tilted empirical risk minimization](https://dl.acm.org/doi/abs/10.1007/s10489-022-04409-z)

**Xuelin Zhang**, Yingjie Wang, Liangxuan Zhu, Hong Chen, Han Li, Lingjuan Wu*. 

**Applied Intelligence 2023 [J]**

- 在这篇论文中，我们提出了一种新的基于收敛双层优化框架的鲁棒变量结构发现方法，用于基于组套索（group lasso），其中采用了鲁棒倾斜的经验风险最小化。实现代码可以在以下网址找到: [https://github.com/zhangxuelincode/demoTERMGL](https://github.com/zhangxuelincode/demoTERMGL)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[1] ICCCS 2022</div><img src='images/icccs22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robustness of classifier to adversarial examples under imbalanced data](https://ieeexplore.ieee.org/document/9846074)

Wenqian Zhao, Han Li, Lingjuan Wu*, Liangxuan Zhu, **Xuelin Zhang**, Yizhi Zhao. 

**International Conference on Computer and Communication Systems 2022 [C]**

- 在这篇论文中，我们提供了一个理论框架，用于从AUC（ROC曲线下面积）的角度分析分类器对AE（Adversarial Examples，对抗性样本）在不平衡数据集下的鲁棒性，并推导出一个可解释的上限.
</div>
</div>


# 📝 硬件安全方向论文

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[4] TCAD 2025 [ccf-A]</div><img src='images/tcad2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Precise and Explainable Hardware Trojan Localization at LUT Level](https://zxlml.github.io/)

Hao Su, Wei Hu, **Xuelin Zhang**, Dan Zhu, Lingjuan Wu*. 

**IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems 2025 [J]**

- 提出的方法是旨在提取查找表（LUT）级别的丰富结构和行为特征，以训练一个可解释的图神经网络（GNN）模型，用于对FPGA网表中的设计节点进行分类，并识别感染木马的节点。实现代码可以在以下网址找到: [https://github.com/zhangxuelincode/node_label](https://github.com/zhangxuelincode/node_label)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[3] ITC-Asia 2024 [ccf-C]</div><img src='images/itc24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pinpointing Hardware Trojans Through Semantic Feature Extraction and Natural Language Processing](https://ieeexplore.ieee.org/abstract/document/10661348)

Yichen Li, Wei Hu, Hao Su, **Xuelin Zhang**, Yizhi Zhao, Lingjuan Wu*. 

**International Test Conference in Asia 2024 [C]**

- 在这项工作中，我们提出了一种新颖的RTL（寄存器传输级）硬件木马检测方法。我们的方法涉及将硬件设计转换为CDFG（控制数据流图），然后进行路径提取和分割.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[2] ICCAD 2023 [ccf-B]</div><img src='images/iccad23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Automated Hardware Trojan Detection at LUT Using Explainable Graph Neural Networks](https://ieeexplore.ieee.org/document/10323915)

Lingjuan Wu, Hao Su, **Xuelin Zhang**, Yu Tai, Han Li, Wei Hu*. 

**International Conference on Computer-Aided Design 2023 [C]**

- 在这项工作中，我们提出了一种基于图神经网络（GNNs）的新型硬件木马检测方法，针对FPGA网表。我们利用LUT级别的丰富显式结构特征和行为特征，这为木马检测提供了一个理想的抽象层次和粒度。通过训练一个优化的类别平衡焦点损失的GNN模型，实现了自动化的木马特征提取和分类. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[1] HOST 2022</div><img src='images/host22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hardware Trojan Detection at LUT: Where Structural Features Meet Behavioral Characteristics](https://ieeexplore.ieee.org/document/9840276)

Lingjuan Wu, **Xuelin Zhang**, Siyi Wang, Wei Hu*. 

**International Symposium on Hardware Oriented Security and Trust 2022 [C]**

- 这项工作提出了一种新颖的硬件木马检测方法，该方法利用现场可编程门阵列（FPGA）网表中的静态结构特征和行为特征。将硬件设计源映射到查找表（LUT）网络使得这些特征变得明确，允许通过机器学习自动化特征提取，并进一步有效地检测木马.
</div>
</div>


# 📝 审稿中工作

- **Xuelin Zhang**, et al,.  Meta Additive Model for Auto Weighting and Sparse Approximation. 
- **Xuelin Zhang**, et al,. S2MAM: Semi-supervised Meta Additive Model for Robust Estimation and Variable Selection. 
- **Xuelin Zhang**, et al,. Meta Additive Model: Learning Theory Analysis and Applications. 
- Ricehng Zhou, **Xuelin Zhang**, et al,. Pairwise Generalized Importance Weighting for Metric Learning under Distribution Shift. 
- Lingjuan Wu, Hao Su, **Xuelin Zhang**, et al,. Explainable Hardware Trojan Detection and Localization in FPGA Netlists. 

# 🎖️ 活动与奖项
- *2024.12:* 受邀汇报： [**CCF武汉2024年会暨第八届优秀博士生学术风采展示论坛**.](https://www.ccf.org.cn/Chapters/Chapters/Wuhan/hyhdzxdt/2024-12-23/836269.shtml)
- *2024.11:* 荣获 [2024年度**博士国家奖学金**.](https://aisle.hzau.edu.cn/info/1097/2216.htm)
- *2024.11:* 荣获 [2024年度**三好研究生**.](https://yjs.hzau.edu.cn/info/1192/10321.htm)
- *2024.11:* 海报参展： [**第二十二届中国工业与应用数学学会年会**.](https://aisle.hzau.edu.cn/info/1097/2201.htm)
- *2024.8:* 受邀汇报： [**IJCAI-2024国际人工智能会议口头汇报与海报展示**.](https://aisle.hzau.edu.cn/info/1097/1911.htm)
- *2024.4:* 受邀汇报： [**湖北省工业与应用数学学会2024年学术交流大会**.](https://aisle.hzau.edu.cn/info/1097/1901.htm)
- *2023.11:* 荣获 **华中农业大学信息学院“电子信息研究生论坛”一等奖**

# 🛠️ 专利
- *2024.06:* 陈洪, **张学林**, 李伟夫, 郑锋. [**一种混凝土抗压能力预测方法、装置、设备及存储介质(已授权)**](https://patents.google.com/patent/CN114580299A/zh)
- *2024.06:* 武玲娟, 胡伟, 宿豪, **张学林**, 李函. **一种基于FPGA网表特征子图的硬件木马检测方法(实质审查中)**
- *2024.10.:* 武玲娟, 李奕晨, 胡伟, **张学林**, 李函. **一种基于语义特征自动提取的硬件木马检测方法(实质审查中)**
- *2023.01:* 武玲娟, 胡伟, 宿豪, **张学林**, 邰瑜. **一种基于图神经网络的硬件木马自动检测方法(实质审查中)**


# 💬 学术服务

- 会议审稿人: ICLR, ICML, IJCNN.

- 期刊审稿人: Expert Systems With Applications, Journal of Infrastructure, Policy and Development.
  
# 🌏 浏览记录
<a href="https://info.flagcounter.com/LoqT"><img src="https://s05.flagcounter.com/countxl/LoqT/bg_FFFFFF/txt_061414/border_CC4BBB/columns_8/maxflags_12/viewers_0/labels_1/pageviews_1/flags_0/percent_0/" alt="Flag Counter" border="0"></a>
