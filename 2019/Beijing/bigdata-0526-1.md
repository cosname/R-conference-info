# 大数据应用专场

> 负责人：李舰  
会场时间：5月26日上午  

## 分会场主题

大数据时代下，学术界的各种新方法层出不穷，业界的应用场景也日新月异，在大数据的基础上，结合R语言等开源而灵活的工具，越来越多的实际问题得到了更好的解决方法，学界和业界的界限开始变得模糊。

本次中国R会议的大数据应用会场邀请了活跃在学术界和业界的研究者，和我们分享各自在大数据领域的最新研究成果与应用案例。每个报告的演讲时间为30分钟，听众可以自由提问并和嘉宾进行专业的讨论，共同打造一次成功的盛会。

## 分会场组织者

李舰，统计之都的老成员，中国R会议的常客，开发了tmcn、Rwordseg等R包，著有《统计之美：人工智能时代的科学思维》《数据科学中的 R 语言》，参与翻译了《R 语言核心技术手册》《机器学习与 R 语言》。

## 演讲列表

### 1 张耀峰：基于警务大数据的犯罪事件智能预测

#### 个人简介

张耀峰，博士、教授，现任湖北经济学院湖北数据与分析中心主任，中国现场统计研究会大数据统计分会秘书长，中国商业统计学会数据科学与商务智能分会副秘书长，武汉烽火普天信息技术有限公司等多家企业合作伙伴和高级顾问，研究方向为商业大数据、舆情大数据、警务大数据等。

#### 报告摘要

随着警务信息化的发展，公安大数据平台建设日益完善，为利用大数据技术开展智慧警务研究提供了基础。本报告利用2015-2018年武汉市近70000条入户盗窃的110报警数据，分别利用深度学习方法对入户盗窃犯罪行为进行预测研究。通过数据提取、数据预处理、模型训练等过程，预测下一时间段犯罪行为发生的具体地点，预测准确率达50%以上。根据该研究结果，已经申请了国家专利1项，为武汉市公安局大数据实战应用中心开发可视化大屏一块，2018年7月大屏系统上线以来运行良好。

### 2 张忠元：聚类方法的评价研究

#### 个人简介

中央财经大学统计与数学学院教授, 博士生导师。

#### 报告摘要

Clustering analysis is critical towards understanding the hidden patterns behind the data. However, how to evaluate the quality of different clustering methods is still challenging and remains unsolved. The most widely used metric, normalized mutual information (NMI), was proved to have finite size effect, and its improved form relative normalized mutual information (rNMI) has reverse finite size effect. Corrected normalized mutual information (cNMI) was thus proposed and has neither finite size effect nor reverse finite size effect. However, in this paper we show that cNMI violates the so-called proportionality assumption. In addition, NMI-type metrics have the problem of ignoring importance of small clusters. Finally, they cannot be used to evaluate a single cluster of interest. In this paper, we map the computed cluster labels to the ground-truth ones through integer linear programming, then use kappa index and F-score to evaluate the clustering methods.

### 3 蔡锐：Online learning在大规模机器学习中的理论与应用

#### 个人简介

蔡锐，曾于统计之都打杂，后远遁美国宾州苦寒之地读博，现为宾州州立大学博士学生。

#### 报告摘要

Online learning是处理大数据时很常用的一种方法。与分布式计算不同，online learning在有内存和存储限制的情况下依然可以实现对大数据的处理。具体来说，当新的数据点或数据集到达的时候，我们依据这些新的数据来更新模型中的参数，从而实现对数据的建模。本次报告将回顾online learning发展历程，主要关注点，理论性质，实际应用，以及本人的一点微不足道的工作。

### 4 曾梓龙：神经影像大数据中机器学习的应用

#### 个人简介

曾梓龙，北京师范大学认知神经科学与国家重点实验室硕士生，研究涉及脑连接组、神经影像数据处理和机器学习。

#### 报告摘要

随着神经影像数据的日益丰富，越来越多的研究者采用机器学习算法或者深度学习算法进行神经科学的研究。本次报告将介绍机器学习算法如何应用到大脑皮层的划分任务以及婴幼儿自闭症的早期诊断任务。


### 5 何德琳：阿里巴巴在"AI+车险"领域的探索和实践

#### 个人简介

何德琳，阿里巴巴算法专家，持续在AI+车险领域多年探索和实践。

#### 报告摘要

阿里巴巴拥有海量互联网数据及前沿的AI技术，针对车险行业的发展诉求，持续在车险定价、反欺诈等领域专门构建了业界领先的车险业务解决方案。通过精准的车主画像、建立了囊括车、人、路、驾驶等独特的风险特征体系，构建了业界领先的AI定价和反欺诈模型，让更多车主能够享受AI 技术带来的更加公平的定价，有效判别用户行车风险、预测车险赔付成本、理赔欺诈风险，帮助保险公司提升优质客户转化率、优化承保客户质量、提高风险定价能力、降低车险赔付成本。
