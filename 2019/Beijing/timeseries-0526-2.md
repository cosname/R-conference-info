# 时间序列预测专场

> 负责人：康雁飞  
> 会场时间：5月26日下午  

## 分会场主题

本专场将和大家分享时间序列预测领域的最新研究成果，具体将介绍大数据时代的需求预测、海量时间序列预测的深度学习框架、基于自我训练的时间序列预测方法、基于时间序列特征的概率预测等。

## 分会场组织者

康雁飞，北京航空航天大学经济管理学院数量经济与商务统计系“卓越百人计划”副教授，前百度大数据部高级研发工程师，澳大利亚莫纳什大学博士、博士后。

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

### 4 王孟樵：用R玩转中国生育率分析

#### 个人简介

王孟樵，四川大学华西公共卫生学院流行病与卫生统计学系助理教授。

#### 报告摘要

本研究利用R语言及ggplot2包对中国的生育率进行回顾性纵向研究，通过丰富精彩的静态和动态数据可视化呈现人口的不断老龄化和生育率的持续走低。时间序列研究基于霍尔特指数平滑模型恢复预测了删除的基于年龄组别和出生顺序的生育率数据，从而对中国生育率自2003年到2018年进行了完整而全面的分析。总的来说，生育率继续下降到一个相当低的水平，而以东北三省份为突出代表显示出与低生育陷阱紧密相关的显著社会经济问题。调整生育限制和推动相关生育扶持政策正当其时。(Wang, Heliyon 2019; https://doi.org/10.1016/j.heliyon.2019.e01460)

### 5 白云：Text based crude oil price forecasting

#### 个人简介

白云，北京航空航天大学本科生，统计学专业，已保研至北航管科专业继续攻读研究生，研究方向：时间序列分析和预测、文本挖掘、机器学习，曾获2018年ICIM优秀论文奖，参与中远海集团，工商银行总行等多个大数据项目的算法分析与设计工作。

#### 报告摘要

Crude oil price forecasting has attracted substantial attention in the field of forecasting. Recently, text based crude oil price forecasting has been an advanced research. Nonetheless, in order to achieve high performance, most of the existing approaches combine text and other factors related to crude oil price to forecast, which is computational and time consuming. Exploiting less factors and information to forecast the crude oil price becomes crucially important. In this paper, we only use news headlines related to the future price to forecast crude oil price. The two marketing index(sentiment index and topic intensity index) extracted from news is used to forecast. Specifically, for short news headlines, we use SeaNMF model to characterize the topic intensity of the market. Compared with other research, we take the time factor into consideration for the sentiment index. Our experiments show crude oil price forecasting based on text, with less factors related to crude oil price and a more accurate characterization of the market, yields better performance compared with others. Also, our text based forecasting method has been applied in other fields and yields good performance, which demonstrates the versatility and robustness of our approach.
