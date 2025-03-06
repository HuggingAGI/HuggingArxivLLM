# 大型语言模型作为动态文本属性图预测器的潜力探索

发布时间：2025年03月05日

`Agent` `图结构` `动态图预测`

> Exploring the Potential of Large Language Models as Predictors in Dynamic Text-Attributed Graphs

# 摘要

> 大型语言模型（LLMs）的兴起激发了人们对图基础模型（GFMs）在图结构任务中应用的兴趣。GFMs通过将LLMs作为预测器，在各类任务和数据集上展现了卓越的泛化能力。然而，现有研究主要聚焦于静态图的预测，忽视了LLMs在动态图预测中的潜力。本研究首次尝试将LLMs应用于动态图预测任务，并发现两大关键挑战：大规模历史数据处理时的上下文长度限制，以及不同领域特征的巨大差异，这些都增加了构建统一预测器的难度。

为应对这些挑战，我们提出了GraphAgent-Dynamic（GAD）框架——一个基于协作LLMs的多智能体系统。与传统方法使用单一LLM作为预测器不同，GAD引入了全局和局部摘要智能体，用于生成特定领域的知识，从而提升跨领域的迁移能力。此外，知识反思智能体能够对GAD的知识进行自适应更新，保持其架构的一致性和自洽性。

实验结果显示，GAD在无需特定数据集训练的情况下，性能可与全监督图神经网络相媲美，甚至超越。最后，为提升LLM预测器的任务特定性能，我们探讨了潜在改进方向，如针对特定数据集对LLMs进行微调。通过为不同任务制定定制化策略，我们为未来基于LLM的预测器设计提供了新的视角。

> With the rise of large language models (LLMs), there has been growing interest in Graph Foundation Models (GFMs) for graph-based tasks. By leveraging LLMs as predictors, GFMs have demonstrated impressive generalizability across various tasks and datasets. However, existing research on LLMs as predictors has predominantly focused on static graphs, leaving their potential in dynamic graph prediction unexplored. In this work, we pioneer using LLMs for predictive tasks on dynamic graphs. We identify two key challenges: the constraints imposed by context length when processing large-scale historical data and the significant variability in domain characteristics, both of which complicate the development of a unified predictor. To address these challenges, we propose the GraphAgent-Dynamic (GAD) Framework, a multi-agent system that leverages collaborative LLMs. In contrast to using a single LLM as the predictor, GAD incorporates global and local summary agents to generate domain-specific knowledge, enhancing its transferability across domains. Additionally, knowledge reflection agents enable adaptive updates to GAD's knowledge, maintaining a unified and self-consistent architecture. In experiments, GAD demonstrates performance comparable to or even exceeds that of full-supervised graph neural networks without dataset-specific training. Finally, to enhance the task-specific performance of LLM-based predictors, we discuss potential improvements, such as dataset-specific fine-tuning to LLMs. By developing tailored strategies for different tasks, we provide new insights for the future design of LLM-based predictors.

[Arxiv](https://arxiv.org/abs/2503.03258)