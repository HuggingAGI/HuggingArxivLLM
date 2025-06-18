# AssistedDS: 评估外部领域知识如何助力LLMs在自动数据科学中的表现

发布时间：2025年05月25日

`LLM应用` `数据科学` `机器学习`

> AssistedDS: Benchmarking How External Domain Knowledge Assists LLMs in Automated Data Science

# 摘要

> 大型语言模型（LLMs）显著提升了数据科学工作流的自动化水平。然而，它们能否像人类数据科学家那样批判性地运用外部领域知识，仍是一个未解之谜。为解答这一问题，我们推出了AssistedDS（辅助数据科学）基准测试，旨在系统评估LLMs在表格预测任务中对领域知识的处理能力。AssistedDS包含了具有明确生成机制的合成数据集和真实世界Kaggle竞赛数据集，每个数据集均配有经过精心整理的有用和对抗性文档包。这些文档为数据清洗、特征工程和模型选择提供了领域特定的深度见解。我们评估了当前最先进的LLMs在辨别和应用有益与有害领域知识方面的效能，从提交的有效性、信息召回率和预测性能三个维度进行了全面考察。研究结果揭示了三个重要发现：（1）LLMs往往表现出对所提供信息的盲目采纳，当引入对抗性内容时，这种做法会对其预测性能造成严重损害，（2）有益的指导常常不足以抵消对抗性信息带来的负面影响，（3）在Kaggle数据集中，LLMs在处理时间序列数据、跨不同折叠应用一致的特征工程以及正确解释分类变量方面常常出现失误。这些发现凸显了当前模型在批判性评估和利用专业知识方面的显著能力差距，突显了开发更强大、知识感知的自动化数据科学系统的重要研究方向。
    

> Large language models (LLMs) have advanced the automation of data science workflows. Yet it remains unclear whether they can critically leverage external domain knowledge as human data scientists do in practice. To answer this question, we introduce AssistedDS (Assisted Data Science), a benchmark designed to systematically evaluate how LLMs handle domain knowledge in tabular prediction tasks. AssistedDS features both synthetic datasets with explicitly known generative mechanisms and real-world Kaggle competitions, each accompanied by curated bundles of helpful and adversarial documents. These documents provide domain-specific insights into data cleaning, feature engineering, and model selection. We assess state-of-the-art LLMs on their ability to discern and apply beneficial versus harmful domain knowledge, evaluating submission validity, information recall, and predictive performance. Our results demonstrate three key findings: (1) LLMs frequently exhibit an uncritical adoption of provided information, significantly impairing their predictive performance when adversarial content is introduced, (2) helpful guidance is often insufficient to counteract the negative influence of adversarial information, and (3) in Kaggle datasets, LLMs often make errors in handling time-series data, applying consistent feature engineering across different folds, and interpreting categorical variables correctly. These findings highlight a substantial gap in current models' ability to critically evaluate and leverage expert knowledge, underscoring an essential research direction for developing more robust, knowledge-aware automated data science systems.

[Arxiv](https://arxiv.org/abs/2506.13992)