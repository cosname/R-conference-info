# 本科生专场

> 负责人：冉佳璐  
会场时间：5月26日上午  

## 分会场主题

本届专场将邀请多位优秀本科生分享其在数据科学领域的研究经历和学习心得，内容包括伊辛图模型研究，医疗图像的深度学习，高光谱图像分析，高效计算R包制作研究等。

## 分会场组织者

冉佳鹭，中国人民大学统计学院2015级本科生，主修数理统计，辅修数学，美国埃默里大学生物统计博士2019 Fall录取。于2017-2018年赴美国加州大学戴维斯分校交换一年，期间参与多个函数型数据和生存分析等方向科研；于2018年9月起在人民大学统计系教授指导下研究新型聚类分析理论。

## 演讲列表

### 1 李家郡：使用Rstudio结合RcppArmadillo制作可以快速随机计算稀疏矩阵奇异值分解的包（Cooking the Package about computing the singular value decomposition of sparse matrix with Rstudio and RCppArmadillo）

#### 个人简介

李家郡，中国人民大学统计学院2015级本科生，主修统计学，辅修计算机科学技术，编程、羽毛球、足球、骑行爱好者。主要研究方向包括大数据流算法、矩阵计算，有多年C++、R、Python、Java编程经验，初步开始探索制作个人博客https://llijiajun.github.io/github-io/。

#### 报告摘要

制作R包是件挺有意思的事，但仅仅使用R语言制作的R包在计算一些结果时，很难达到令人满意的效率。利用Rcpp手段制作高效运算包可以很大程度上提高工作效率。而矩阵的奇异值分解问题可以广泛应用于各个领域，随着社交网络、自然语义识别等领域的发展，这些问题往往面临着求解大规模稀疏矩阵奇异值分解的问题，R语言现有的奇异值分解手段仍有优化空间。本演讲基于制作R包的过程展开，以快速随机计算稀疏矩阵奇异值分解为例，探究使用Rcpp结合现有矩阵代数库Armadillo实现R包的中可能遇到的问题，并借此倡导广大R语言和其他兼修多种语言使用者加入到扩充R包的队伍中，以实现更多有趣的课题。

### 2 刘秋华：Densely Dilated Spatial Pooling Convolutional Network using benign loss functions for imbalanced volumetric prostate segmentation （基于前列腺分割任务的DDSP网络设计和损失函数探讨）

#### 个人简介

刘秋华，中国人民大学信息学院2015级本科生，主修应用数学，美国密歇根大学生物统计硕士2019FALL录取。于2017-2018年间获两次北美大学生数学建模竞赛一等奖、一次全国大学生数学建模竞赛国家二等奖；于2017年3月加入中国人民大学数学科学研究院数学智能应用实验室，期间参与三个科研项目，目前学生二作BMC Systems Biology发表一篇，一作投稿SIAM Journal on Imaging Science一篇；于2018年6-9月到美国斯坦福大学参加暑期科研，目前一作正撰稿一篇。研究方向主要为深度学习领域数学统计理论、医疗图像处理、机器学习建模等。

#### 报告摘要

The high incidence rate of prostate disease poses a requirement in early detection for diagnosis. As one of the main imaging methods used for prostate cancer detection, Magnetic Resonance Imaging (MRI) has wide range of appearance and imbalance problems, making automated prostate segmentation fundamental but challenging. Here we propose a novel Densely Dilated Spatial Pooling Convolutional Network (DDSP ConNet) in encoder-decoder structure, which employs dense structure to combine dilated convolution and global pooling, thus supplying coarse segmentation results from encoder and decoder subnet and preserving more contextual information. Furtherly, to obtain richer hierarchical feature maps, residual long connection is adopted to fuse contexture features. Meanwhile, we adopt DSC loss and Jaccard loss functions to train our DDSP ConNet and we surprisingly found and proved that, in contrast to re-weighted cross entropy, DSC loss and Jaccard loss have a lot of benign properties in theory, including symmetry, continuity and differentiability about the parameters of network. To corroborate the effectiveness of our DDSP ConNet with DSC loss and Jaccard loss, extensive experiments have been done on the MICCAI PROMISE12 challenge dataset. In the test dataset , our method achieves a score of 85.78, outperforming most of other competitors.

### 3 康越：基于岭比收缩的高光谱图像端元个数估计方法

#### 个人简介

康越，西安交通大学数学与应用数学专业大四在读，毕业后将前往加州大学戴维斯分校攻读统计学博士，研究兴趣为高维数据分析及其在各个领域的应用。在IEEE Transactions on Geoscience and Remote Sensing杂志上投稿文章一篇，运用统计学知识对高光谱图像端元个数的估计问题提出了更为高效的方法。

#### 报告摘要

高光谱图像端元个数的估计问题一直都是该领域的核心问题之一。经典的算法如HFC、HySime等对于很多实际数据的模拟效果很差，这与他们对算法内部的参数以及噪音类型的高敏感度有很大关系，并且本身的理论也普遍存在一定缺陷。本研究着眼于利用统计理论构造了一种克服上述缺点新方法(thresholding ridge ratio criterion)，并且在模拟与实际数据中表现出了很大的优越性。

### 4 金滢：Computational-Statistical Tradeoffs in Inferring Combinatorial Structures of Ising Model （伊辛图模型组合结构推断问题的计算-统计权衡）

#### 个人简介

金滢，清华大学数学科学系2015级本科生，主修概率与统计方向，美国斯坦福大学统计博士2019Fall录取。2017年9月加入清华统计学研究中心教授团队研究非平稳时间序列理论，一作正撰稿一篇；2018年3月起在西北大学运筹系及哈佛大学生物统计系教授指导下研究图模型结构推断理论，一作正撰稿一篇；2018年7-9月赴哈佛大学统计系进行网络分析模型算法相关暑期科研。现有研究方向主要为图模型和网络分析、高维统计、时间序列。

#### 报告摘要

In various problems, data are represented and interpreted in the form of graphs, where conditional dependency relationships among nodes are illustrated by edges between pairs of nodes. Ising model is a popular kind of graphical model that is suitable for binary-valued nodes. Under the framework of oracle model, which captures the computational properties of a wide range of algorithms, we focus on inferring combinatorial structures of Ising model, for example, the existence of an s-clique in a given graph. We are interested in the detection limits both with or without polynomial computational limits, equivalently, the computational-statistical tradeoffs in this problem. 

In our work, we establish the general computational lower bounds for inferring structural properties in simple zero-field Ising model, under which no polynomial-time queries can distinguish between two hypotheses. We found that the bound is related to certain structural property of the underlying graph which we define as vertex overlap ratio. Meanwhile, we propose specific query functions and test functions with polynomial computational budgets which attain the lower bounds for specific problems. We also discussed the relationship between information-theoretic limits and computational-efficient limits. We found that for clique detection and nearest neighbor graph detection problem, there is a gap between computational efficiency and statistical accuracy. However, for relatively sparse structure like perfect matching, there is no gap between computational efficiency and statistical accuracy. 

### 5 林枫：从零开始的COSplay 

#### 个人简介

统计之都副主编，中国科学技术大学在读硕士，感兴趣的领域包括机器学习、优化理论等。

#### 报告摘要

统计之都（COS）一直致力于推广与应用统计学知识，分享有趣的数据科学方法与观点，为国内统计学和数据科学的发展贡献力量。我们也一直欢迎有志于将统计学和数据科学发扬光大的各界朋友加入到这个大家庭来。让我们一起探秘COS编辑部时尚时尚最时尚的在线投稿系统，解锁COS丰富的“玩法”，从零开始一场统计学与数据科学的精彩PLAY！ 
