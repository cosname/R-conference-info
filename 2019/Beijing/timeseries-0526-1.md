# 时间序列预测分会场

> 负责人：康雁飞  
> 会场时间：5月26日上午  

## 分会场主题

本专场将和大家分享时间序列预测领域的最新研究成果，具体将介绍大数据时代的需求预测、海量时间序列预测的深度学习框架、基于自我训练的时间序列预测方法、基于时间序列特征的概率预测等。

## 分会场组织者

康雁飞，北京航空航天大学经济管理学院数量经济与商务统计系“卓越百人计划”副教授，前百度大数据部高级研发工程师，澳大利亚莫纳什大学博士后、博士。

## 本届精彩预告

### 1 陈艺天：大数据时代的需求预测

#### 个人简介

陈艺天，Bigo算法专家，前京东资深算法工程师。在京东期间，主要从事电商统计建模与运筹优化相关的数据建模工作，带领团队搭建着京东第一个动态定价系统，该系统目前管理着京东自营约50%~70%中长尾商品的自动价格管理；参与京东的销量预测系统的优化，率先搭建起基于神经网络的预测模型框架，该框架提升原京东物流单量约50%的准确度。多次受邀去KDD作技术报告。

#### 报告摘要

时序预测在诸多的商业决策中扮演着至关重要的角色；在大数据爆炸的今天，许多公司与机构面临对成千上万相关时序的预测问题: 如电商平台,需要对未来一段时间所有商品销量做预测，物流行业对库房每天的出单量作预测，交通领域对一个城每条的街道的车流量作又没, 等等。在诸如此类的场景中，应用经典的时序模型，如基于State space model的ARIMA, Exponential smoothing模型 , 又或是基于Bayesian方法的结构化时序模型, generalized additive model，面临着诸多的挑战: 一方面大量的数据使得对单一时序的建模与调参变得不太现实;另一方面，在这些场景中，其中大量的时序存着需要冷启动预测又没或数据稀疏的问题(如电商平台每周都会有新产品上架)，而经典时序模型在这种场景下变得无能为力; 在本次的报告中，我们将展现我们设计的基于时序因果卷积的深度学习模型，并提出了基于该模型的两种概率预测的框架。 中国最大的零售商的电商销售数据和物流数据的实验，表明该模型可以大幅度提升预测准确度；我们同时也在公开数据集和当前时序最新state-of-the-art的模型作了比较，结果表明我们的框架在准确度和计算效率都大幅度优于其他模型。

### 2 Yanfei Kang：Feature-based time series forecasting

#### 个人简介

Dr. Yanfei Kang is Associate Professor of Statistics at Beihang University in China. Prior to that, she was Senior R&D Engineer in Big Data Group of Baidu Inc. Yanfei obtained her Ph.D. degree at Monash University in 2014. She worked as a postdoctoral research fellow during 2014 and 2015 at Monash University. Her research interests include time series forecasting, time series visualization, statistical computing and machine learning.

#### 报告摘要

Feature-based time series representation has attracted substantial attention in a wide range of time series analysis methods. Recently, the use of time series features for forecast model selection and model averaging has been an emerging research focus in the forecasting community.  That calls for a more diverse time series benchmarks as the training data to model time series features and forecasting algorithm performances. We propose GeneRAting TIme Series with diverse and controllable characteristics, named GRATIS, with the use of mixture autoregressive (MAR) models. We generate sets of time series using MAR models and investigate the diversity and coverage of the generated time series in a time series feature space.  Efficient Bayesian surface regression is used on the generated data to examine how time series features influence forecasting method performances, which enables us to predict the performances of the forecasting methods on test data.  We illustrate the usefulness of our time series generation process and feature-based forecasting scheme with their applications on the M3 forecasting competition data.

### 3 Xiaoqian Wang：Probabilistic forecasting based on time series features

#### 个人简介

北京航空航天大学经济管理学院统计学专业在读博士。研究方向包括时间序列分析，统计建模和机器学习。

#### 报告摘要

The surge of time series data in the big data era leads to an explosive demand for time series forecasting methods. Compared with point forecasting, the literature on probabilistic forecasting, which can provide a comprehensive outlook of the expected future value and the future uncertainty, is highly limited. In this paper, we propose a general feature-based probabilistic forecasting framework, which is divided into “offline” and “online” parts. In the “offline” part, we explore how time series features affect the probabilistic forecasting accuracy of different forecasting methods by generalized additive models (GAM). Moreover, we introduce a threshold ratio for the selection of individual forecasting methods in the model averaging process. In the “online” part, we obtain the model average forecasts of new series by pre-trained GAM and optimal threshold ratio. We illustrate that our probabilistic forecasting framework outperforms all individual benchmark forecasting methods on M3 data, with improved computational efficiency. Another key advantage of our proposed framework is its interpretability of the effects of features on the probabilistic forecasting accuracy.

持续更新，敬请期待！
