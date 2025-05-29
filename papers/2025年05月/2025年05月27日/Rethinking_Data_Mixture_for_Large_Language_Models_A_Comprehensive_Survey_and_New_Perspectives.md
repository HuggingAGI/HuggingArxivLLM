# 大型语言模型的数据混合策略：系统性综述与全新视角

发布时间：2025年05月27日

`LLM理论` `数据混合` `模型训练`

> Rethinking Data Mixture for Large Language Models: A Comprehensive Survey and New Perspectives

# 摘要

> 使用多领域数据训练大型语言模型，能有效提升其下游任务表现。然而，在固定训练预算下，如何分配各领域的数据比例，是影响模型性能的关键。本文将全面概述现有数据混合方法。首先，我们提出了现有方法的详细分类，超越了传统的离线和在线分类方式。离线方法细分为基于启发式、基于算法和基于函数拟合的方法。在线方法则分为在线最优化、在线混合法则和其他方法。其次，我们总结了各类方法的问题建模、代表性算法，并明确了它们之间的关系与区别。最后，我们分析了每种方法的优缺点，并指出了数据混合领域面临的关键挑战。

> Training large language models with data collected from various domains can improve their performance on downstream tasks. However, given a fixed training budget, the sampling proportions of these different domains significantly impact the model's performance. How can we determine the domain weights across different data domains to train the best-performing model within constrained computational resources? In this paper, we provide a comprehensive overview of existing data mixture methods. First, we propose a fine-grained categorization of existing methods, extending beyond the previous offline and online classification. Offline methods are further grouped into heuristic-based, algorithm-based, and function fitting-based methods. For online methods, we categorize them into three groups: online min-max optimization, online mixing law, and other approaches by drawing connections with the optimization frameworks underlying offline methods. Second, we summarize the problem formulations, representative algorithms for each subtype of offline and online methods, and clarify the relationships and distinctions among them. Finally, we discuss the advantages and disadvantages of each method and highlight key challenges in the field of data mixture.

[Arxiv](https://arxiv.org/abs/2505.21598)