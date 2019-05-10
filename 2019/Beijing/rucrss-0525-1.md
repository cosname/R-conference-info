# 人大统计专场

> 负责人：李扬  
会场时间：5月25日上午  

## 分会场主题

本届专场和大家分享中国人民大学青年教师在数据科学各领域的理论方法研究与应用实践成果，涵盖经济社会、风险管理、生物医学等方面。

## 分会场组织者

李扬，中国人民大学统计学院教授、博士生导师、统计咨询研究中心主任，国际统计学会推选会员、中国商业统计学会数据科学与商业智能分会学术委员会副主任、全国工业统计学教学研究会中国青年统计学家协会常务理事、国际生物统计学会中国分会青年理事、北京生物医学统计与数据管理研究会监事长。主要从事基于深度学习的复杂数据分析方法、模型选择与不确定性分析、生物医学统计大数据算法等领域研究，承担国家重点研发计划精准医学研究重点专项子课题、国家自然科学基金面上项目等科研项目二十余项，发表Biometrics、Statistics in Medicine、Statistical Methods in Medical Research、Briengs in Bioinformatics、Applied Stochastic Models in Business and Industry、统计研究、数理统计与管理等国内外期刊研究论文六十余篇。

## 演讲列表

### 1 杨翰方：Two-Way Partial AUC and Its Properties

#### 个人简介

杨翰方，副教授，博士生导师。现就职于中国人民大学统计学院，隶属经济与社会统计教研室，中国人民大学统计与大数据研究院师资团队成员。2007年毕业于同济大学数学与应用系，获得理学学士学位， 2012年先后获得美国佐治亚州立大学风险管理硕士以及统计学博士学位。回国后在中国人民大学统计学院任讲师，2016年晋升副教授，2017年获得博士生导师资格。

#### 报告摘要

Simultaneous control on true positive rate (TPR) and false positive rate (FPR) is of  significant importance in the performance evaluation of diagnostic tests. Most of the established literature utilizes partial area under the receiver operating characteristic (ROC) curve with restrictions only on FPR, called FPR pAUC, as a performance measure. However, its indirect control on TPR is conceptually and practically misleading. In this paper, a novel and intuitive performance measure, named as two-way pAUC, is proposed, which directly quantiﬁes partial area under the ROC curve with explicit restrictions on both TPR and FPR. To estimate two- way pAUC, we devise a nonparametric estimator. Based on the estimator, a bootstrap-assisted testing method for two-way pAUC comparison is established. Moreover, to evaluate possible covariate effects on two-way pAUC, a regression analysis framework is constructed. Asymptotic normalities of the methods are provided. Advantages of the proposed methods are illustrated by simulation and Wisconsin Breast Cancer Data. We encode the methods as a publicly available R package tpAUC.

### 2 孙怡帆：An integrative sparse boosting analysis of cancer genomic commonality and difference

#### 个人简介

An integrative sparse boosting analysis of cancer genomic commonality and difference

#### 报告摘要

In cancer research, high-throughput profiling has been extensively conducted. In recent studies, the integrative analysis of data on multiple cancer patient groups/subgroups has been conducted. Such analysis has the potential to reveal the genomic commonality as well as difference across groups/subgroups. However, in the existing literature, methods with a special attention to the genomic commonality and difference are very limited. In this study, a novel estimation and marker selection method based on the sparse boosting technique is developed to address the commonality/difference problem. In terms of technical innovation, a new penalty and computation of increments are introduced. The proposed method can also effectively accommodate the grouping structure of covariates. Simulation shows that it can outperform direct competitors under a wide spectrum of settings. The analysis of two TCGA (The Cancer Genome Atlas) datasets is conducted, showing that the proposed analysis can identify markers with important biological implications and have satisfactory prediction and stability.

### 3 马维：Properties of Covariate-Adaptive Randomization with Misclassification in Covariate

#### 个人简介

2009年毕业于浙江大学数学系，2013年毕业于美国弗吉尼亚大学并取得统计学博士学位。博士毕业后曾任职于世界知名制药企业研发部门担任资深生物统计学家。于2017年加入中国人民大学统计与大数据研究院并担任助理教授。研究兴趣包括生物统计、临床试验设计、健康医疗大数据等。

#### 报告摘要

Covariate-adaptive randomization is extensively used in clinical trials to balance treatment allocation over covariates, which is often viewed as an essential component in ensuring valid treatment comparisons. Most randomization procedures and tests in clinical trials are based on the assumption that the covariates are measured accurately. However, in practice, measurement error is inevitable, and it will cause misclassification in covariate. Under covariate-adaptive randomization, the impact is tied to both randomization and analysis. It is unclear how the misclassification affects the treatment assignment and the corresponding statistical inference. In this talk, we study the impact of covariate misclassification on the properties of covariate-adaptive randomization.  In particular, we show that, if there is misclassification, the within-stratum imbalance is no longer bounded in probability and the two sample t-test is still conservative. Numerical studies are also performed to assess the finite sample properties.

### 4 高光远：Evaluation of driving risk at different speeds

#### 个人简介

高光远为中国人民大学统计学院讲师，毕业于同济大学（学士）和澳洲国立大学（博士）。目前的研究方向包括UBI车险定价，贝叶斯准备金评估模型等。已在ASTIN Bulletin，Scandinavia Actuarial Journal，Insurance：Mathematics and Economics，保险研究等精算期刊上发表多篇论文，并著有一本Bayesian Claims Reserving Methods in Non-life Insurance with Stan: An Introduction (Springer)。

#### 报告摘要

Telematics car driving data describes drivers' driving characteristics. This paper studies the driving characteristics at different speeds and their predictive power for claims frequency modeling. We first extract covariates from telematics car driving data using $K$-medoids clustering and principal components analysis. These telematics covariates are then used as explanatory variables for claims frequency modeling, in which we analyze their predictive power. Moreover, we use these telematics covariates to challenge the classical covariates usually used in practice.
