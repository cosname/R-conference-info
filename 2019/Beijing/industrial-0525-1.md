# 工业工程分会场

> 负责人：梁巧  
会场时间：5月25日上午  

## 分会场主题

作为一门跨学科的专业，工业工程关注复杂过程及组织系统的优化，以提高效率、保证质量和降低成本为目标。解决工业工程领域的实际问题，需要与生产和服务过程中复杂多类型数据打交道，将数据科学与工业工程系统优化的思维融合。

本分会场主题围绕以数据分析为核心完成的工业工程领域各项相关研究与应用，涉及到的数据类型包括生产及服务过程中的产品质量数据、轮廓数据、文本评论数据、交通数据、网络结构数据等，体现了统计学、大数据、人工智能相关理论在工业工程学科各方向的具体应用。

## 分会场组织者

梁巧，清华大学工业工程系三年级博士生，研究方向包括制造及服务过程中的统计建模和数据分析，特别是基于文本类数据的统计过程控制。

## 演讲列表

### 1 张晨：Modeling Tunnel Profile in Presence of Coordinate Errors: A Gaussian Process Based Approach

#### 个人简介

Zhang Chen (张晨) is an Assistant Professor in Industrial Engineering, Tsinghua University. She received her B.Eng. degree in Electronic Science and Technology (Optics) from Tianjin University in 2012, and her Ph.D. degree in Industrial Systems Engineering from National University of Singapore in 2017. Her research interests include developing methodologies and algorithms for complex or large-scale systems with multivariate or high-dimensional data, including intelligent sampling and sensing for data collection, data mining and information extraction for system modeling, and on-line monitoring and efficient anomaly detection for streaming data.

#### 报告摘要

This talk presents a Gaussian process (GP) based approach to model a tunnel's inner surface profile with point cloud data provided by Terrestrial Laser Scanner (TLS). We introduce a reading-surface profile which uniquely determines a three-dimensional tunnel in a Cartesian coordinate system. This reading surface transforms the cylindrical tunnel to a two-dimensional surface profile, hence allowing us to model the tunnel profile by GP. To account for coordinate errors induced by TLS, we take repeated measurements at designed coordinates. We apply Taylor approximation to extract mean and gradient estimations from the repeated measurements, and then fit the GP model with both estimations to obtain a more robust reconstruction of the tunnel profile. We present a case study to demonstrate that our method provides a more accurate result than the existing cylinder-fitting approach and has great potential for deformation monitoring in presence of coordinate errors.

### 2 唐昕迪：Dynamic Management of Autonomous Electric Taxis using Reinforcement Learning Method

#### 个人简介

Xindi Tang received her bachelor's degree from Department of Automation, Tsinghua University in 2012. She is now a 3rd year Ph.D. student in Department of Industrial Engineering, Tsinghua University. Her research interests lie on planning and operation strategies of urban electricial transportation system as well as intelligent transportation management.

#### 报告摘要

Electrification and automatization are two tendencies of intelligent transportation. It is foreseeable that autonomous electric taxi will play an important role in the future. However, the travel pattern of autonomous vehicles are different from traditional ones, not mentioning there is extra charging need for electric vehicles. In this study, we propose a reinforcement learning method to dynamically assign vehicles to customers, which tackles the curse of dimensionality in traditional optimization model. We conduct numerical examples to verify effectiveness of proposed method.

### 3 董航：Modeling and Change Detection for Count-weighted Multi-layer Networks

#### 个人简介

董航，本科毕业于清华大学工业工程系，现清华大学工业工程系博士四年级在读，研究方向为网络数据的统计建模与监控。

#### 报告摘要

In a typical network with a set of individuals, it is common to have multiple types of interactions between two individuals. In practice, these interactions are usually sparse and correlated, which is not sufficiently accounted for in the literature. We proposes a multi-layer weighted stochastic block model (MZIP-SBM) based on a multivariate zero-inflated Poisson (MZIP) distribution to characterize the sparse and correlated multi-layer interactions of individuals. A variational-EM algorithm is developed in order to estimate the parameters in this model. We further propose a monitoring statistic based on the score test of MZIP-SBM model parameters for change detection in multi-layer networks. The proposed model and monitoring scheme are validated using extensive simulation studies and the case study from Enron email network.

### 4 刘心广：R在某工厂自动化制造产线质量监控中的应用

#### 个人简介

刘心广，质瑞信息CTO，中国科学院博士，副教授、高级工程师职称；持有高校教师资格证，IEEE会员，美国质量协会ASQ高级会员。擅长机器学习和人工智能算法研究，通过大数据采集、清洗、存储、分析计算和应用的一体化技术，推动提升工业质量大数据的分析和应用，实现数据的信息化和价值化。曾在杭州电子科技大学、聚光科技、艾维思通讯技术、OCLARO、II-VI研发中心等从事电子信息领域数据分析、解决方案和智能软件产品研发，目前负责工业领域大数据分析、智能算法和应用整合的数字化一体解决方案开发。

#### 报告摘要

某3C制造工厂在产品的自动化生产和组装过程中，由于多工位多类型自动化设备的引入，数据实时产生，但类型多样、各自孤立，产品质量相关数据分散在各个局部点位。本项目基于工厂业务应用场景需求，通过数据的自动采集、互联互通和质量工程技术分析，构建了三个层次的在线监控与报警系统，对工厂制造质量进行实时数字化管理，并在工厂内私有化部署上线，是R语言在生产环境中的一个应用案例。


### 5 梁巧：基于电商评论数据的产品及服务质量在线监控

#### 个人简介

梁巧，清华大学工业工程系三年级博士生，研究方向包括制造及服务过程中的统计建模和数据分析，特别是基于文本类数据的统计过程控制。

#### 报告摘要

随着电子商务的兴起和快速发展，人们逐渐习惯从网上购买商品和服务，电商平台每天都会产生大量的用户评论，这些评论直接反映了消费者的关注点和喜恶情况。与单一的打分形式相比，文字评论涵盖的维度更广，内容更丰富，成为评估和监控网络商品和服务质量的有力工具。在评论文字中，往往包含两种类型的信息：一是“主题”，它主要对应用户关注的商品或服务维度，比如商品的各个质量特性；二是“情感”，反映了用户对商品或服务的好感度。这两部分信息结合起来，则反映了用户感知到的商品和服务质量。已有的产品质量监控研究，往往针对的是制造过程本身产生的波动和异常，所用到的数据类型也大多是连续型、分类型数据，本研究则从产品全生命周期的角度出发，在售后阶段入手，利用用户反馈的评论数据进行产品质量的监控，为我们实现质量管理提供新的思路。

