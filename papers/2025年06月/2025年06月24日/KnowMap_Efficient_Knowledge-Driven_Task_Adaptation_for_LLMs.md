# KnowMap：面向大语言模型的高效知识驱动任务适配

发布时间：2025年06月24日

`LLM应用` `人工智能` `知识管理`

> KnowMap: Efficient Knowledge-Driven Task Adaptation for LLMs

# 摘要

> 大型语言模型 (LLMs) 虽然在开放世界代理任务中表现出色，但受限于静态预训练知识，难以快速适应新领域和专业任务。传统微调方法不仅成本高昂、数据密集，还可能引发“灾难性遗忘”。为此，我们提出了一种名为 KnowMap 的创新方法，它能够从环境和经验数据中动态构建知识库。通过微调小型知识嵌入模型，KnowMap 赋予大型 LLM 特定任务的实用知识。在 ScienceWorld 基准测试中，我们的实验显示 gpt-4-turbo 模型性能提升了 17.71%。KnowMap 不仅提供了一种高效的任务适应方案，更揭示了整合环境与经验知识对提升 LLM 推理能力的显著作用。

> While Large Language Models (LLMs) possess significant capabilities in open-world agent tasks, they also face challenges in rapidly adapting to new, specialized tasks due to their reliance on static pre-trained knowledge. Traditional methods such as fine-tuning are often costly, data-intensive, and may lead to "catastrophic forgetting." Therefore, we present KnowMap, a novel approach that dynamically constructs a knowledge base from environmental and experiential data. KnowMap fine-tunes a small knowledge-embedding model to equip a larger LLM with valuable task-specific knowledge. Our experiments on the ScienceWorld benchmark demonstrate 17.71% improvement for the performance of gpt-4-turbo model. KnowMap not only provides an efficient and effective means for LLM task-adapting, but also highlights how integrating environmental and experiential knowledge can enhance LLMs' reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2506.19527)