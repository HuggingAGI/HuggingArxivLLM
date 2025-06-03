# # 强数据处理不等式视角下的数据记忆权衡
探讨强数据处理不等式在数据记忆中的权衡与取舍

发布时间：2025年06月02日

`LLM理论` `数据隐私` `机器学习`

> Trade-offs in Data Memorization via Strong Data Processing Inequalities

# 摘要

> 近期研究表明，大型语言模型的训练过程会记忆大量训练数据。这种记忆机制在使用敏感用户数据进行训练时可能导致隐私泄露，因此研究数据记忆在学习过程中的作用具有重要意义。本研究提出了一种通用方法，用于证明过度数据记忆的下界，该方法基于强数据处理不等式与数据记忆之间的一种新关联。我们进一步展示了多个简单自然的二元分类问题中，样本数量与学习算法所需记忆的训练数据信息量之间存在权衡关系。具体而言，当提供$O(1)$个$d$维样本时，需要记忆$Ω(d)$比特的训练数据信息，而随着样本数量以问题特定速率增长，所需记忆的信息量会逐渐减少。此外，我们的下界通常（在对数因子内）与简单的学习算法相匹配。我们还将下界扩展到更一般的混合聚类模型。我们的定义和结果基于Brown等人的工作（2021年），并解决了他们工作中下界分析的若干限制。

> Recent research demonstrated that training large language models involves memorization of a significant fraction of training data. Such memorization can lead to privacy violations when training on sensitive user data and thus motivates the study of data memorization's role in learning. In this work, we develop a general approach for proving lower bounds on excess data memorization, that relies on a new connection between strong data processing inequalities and data memorization. We then demonstrate that several simple and natural binary classification problems exhibit a trade-off between the number of samples available to a learning algorithm, and the amount of information about the training data that a learning algorithm needs to memorize to be accurate. In particular, $Ω(d)$ bits of information about the training data need to be memorized when $O(1)$ $d$-dimensional examples are available, which then decays as the number of examples grows at a problem-specific rate. Further, our lower bounds are generally matched (up to logarithmic factors) by simple learning algorithms. We also extend our lower bounds to more general mixture-of-clusters models. Our definitions and results build on the work of Brown et al. (2021) and address several limitations of the lower bounds in their work.

[Arxiv](https://arxiv.org/abs/2506.01855)