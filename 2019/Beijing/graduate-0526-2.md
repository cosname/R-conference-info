# 研究生专场

> 负责人：张心雨  
会场时间：5月26日下午  

## 分会场主题

本次为R会议第一次开设研究生会场，目的希望为研究生提供展示平台和交流机会。主题不限，希望广大硕士生博士生踊跃报名，分享学术成果，研究内容！

## 分会场组织者

张心雨，清华大学统计学研究中心博士生。

## 本届精彩预告

### 1 黄涛：Large-scale Regression with Two-stage Best-score Random Forest

#### 个人简介

黄涛，男，本科毕业于中国人民大学统计学院，现为中国人民大学统计与大数据研究院博士一年级研究生。

#### 报告摘要

我们提出了一种针对大规模回归问题的新算法，即两阶段最佳得分随机森林（TBRF）。 “最佳得分”意味着从一定数量的纯随机回归树候选中选择一个具有最佳经验性能的回归树，而“两阶段”意味着将原始随机树的切割过程分成两阶段：第一阶段，特征空间基于树结构被划分为非重叠的单元（即叶节点）;第二阶段，在上阶段得到的非重叠的每一个单元，我们继续基于树结构对特征空间进行划分。该算法的优点可归纳如下：首先，TBRF中的纯随机性使得几乎最优的收敛速率能够达到，并且这解决了长期困扰现有大规模回归算法的边界不连续性问题。其次，两阶段过程为并行计算铺平了道路，从而提高了计算效率。最后，作为一个一般性的框架，TBRF可以令各种回归器，例如线性预测器和最小二乘支持向量机（LS-SVM）也嵌入到第一阶段的树的叶节点里，具体取决于基础数据集的特征。在大规模回归数据集上的实验，TBRF良好的预测精度和高计算效率得到验证。

### 2 李杰：Kolmogorov-Smirnov simultaneous confidence bands for time series distribution function

#### 个人简介

李杰，清华大学统计学研究中心直博二年级学生，师从杨立坚教授。主要研究方向为非参数统计、时间序列和函数型数据分析。

#### 报告摘要

Claims about distribution functions of time series are more often folklores than substantiated conclusions, due to lack of hypotheses testing tools. In this work, Kolmogorov-Smirnov type simultaneous confidence bands (SCBs) are constructed based on a simple random sample (SRS) drawn from a realization of time series, together with smooth SCBs using kernel distribution estimator (KDE). All SCBs are shown to enjoy the same limiting distribution as the standard Kolmogorov-Smirnov SCB for i.i.d. sample. This theoretical fact has been validated in simulation experiments performed on various time series. Hypotheses testing based on these SCBs has led to the unexpected finding that with proper rescaling, Gaussian distribution and most student's t-distributions are all acceptable alternatives of the S&P 500 daily returns' stationary distribution. This discovery challenges the long held belief that daily financial returns' distribution is fat-tailed and leptokurtic.

### 3 Xixi Li：Time series forecasting based on automatic feature extraction

#### 个人简介

A master student from Beihang University. My research focuses on time series forecasting, machine learning and business intelligence.

#### 报告摘要

Feature-based time series representation has attracted substantial attention in a wide range of time series analysis methods. Recently, the use of time series features for forecast model selection and model averaging has been an emerging research focus in the forecasting community. Nonetheless, most of the existing approaches depend on the manual choice of an appropriate set of features. Exploiting machine learning methods to automatically extract features from time series becomes crucially important in the state-of-the-art time series analysis. In this paper, we introduce an automated approach to extract time series features based on images. Time series are first transformed into recurrence images, from which local features can be extracted using computer vision algorithms. The extracted features are used for forecast model selection and model averaging. Our experiments show that forecasting based on automatically extracted features, with less human intervention and a more comprehensive view of the raw time series data, yields comparable performances with the top best methods proposed in the largest forecasting competition M4.


持续更新，敬请期待！
