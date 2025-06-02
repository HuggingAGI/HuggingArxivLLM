# 从宏观到微观：探析语言模型微调中的数据集多样性

发布时间：2025年05月30日

`LLM理论` `机器学习`

> From Macro to Micro: Probing Dataset Diversity in Language Model Fine-Tuning

# 摘要

> 数据集多样性在机器学习模型训练中至关重要，尤其是在大型语言模型（LLM）的监督微调（SFT）阶段。尽管人们逐渐认识到其重要性，但系统性的数据分析仍较为匮乏。本研究提出了一套全面的多样性控制策略分类法，主要针对指令组件，分别从宏观（整体语义）和介观（单元级别）层面进行操作，并首次对响应组件中的微观多样性进行了深入分析，具体考察了SFT训练样本中令牌的统计分布。实验中，我们从11.7万个开源SFT样本中构建了固定规模的数据集（如每个包含10,000个样本），应用了涵盖宏观、介观和微观三个层面的六种多样性控制策略于指令和响应。通过在这些数据集上微调LLM，我们评估了这六种策略的效果。结果显示，宏观和介观策略随着多样性增加性能提升，而响应中的微观策略不仅与模型性能呈现更强的相关性，且在多样性最大时展现出最优性能。这些发现为构建高性能SFT数据集提供了实用指导。

> Dataset diversity plays a pivotal role for the successful training of many machine learning models, particularly in the supervised fine-tuning (SFT) stage of large language model (LLM) development. Despite increasing recognition of its importance, systematic analyses of dataset diversity still remain underexplored. To address this gap, this work presents a systematic taxonomy of existing diversity-control strategies, which primarily focus on the instruction component, operating at either macroscopic (entire instruction semantics) or mesoscopic levels (instruction units), and furthermore introduces a novel analysis of microscopic diversity within the response component, specifically analyzing the statistical distribution of tokens in SFT training samples. In the experimental evaluation, we construct fixed-size datasets (e.g., 10,000 samples each) from a corpus of 117,000 open-source SFT samples, incorporating six distinct diversity-control strategies spanning macro-, meso-, and microscopic levels applied to both instructions and responses. We then fine-tune LLMs on these datasets to assess the six diversity-control strategies. Results reveal that while macroscopic and mesoscopic strategies lead to higher performance with increasing diversity, the microscopic strategy in responses exhibits both a stronger correlation between model performance and the degree of diversity and superior performance with maximum diversity across all strategies. These findings offer actionable insights for constructing high-performance SFT datasets.

[Arxiv](https://arxiv.org/abs/2505.24768)