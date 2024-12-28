# 通过思维链进行知识编辑

发布时间：2024年12月23日

`LLM应用` `知识编辑`

> Knowledge Editing through Chain-of-Thought

# 摘要

> 大型语言模型（LLMs）在众多自然语言处理（NLP）任务中展现出卓越能力。然而，因频繁重训成本高昂，让这些模型跟上不断演进的世界知识成了重大难题。为应对此难题，知识编辑技术出现了，能在不重新构建模型的情况下用新信息更新 LLMs。其中，上下文编辑范式因能在融入新知识时保留模型原有能力而表现出色。尽管潜力巨大，但现有的上下文知识编辑方法往往针对特定任务，主要聚焦于使用结构化知识三元组的多跳问答任务。而且，它们依赖少样本提示进行任务分解，导致在不同任务中的泛化不稳定且效果欠佳。
  鉴于这些局限，我们提出了 EditCoT，这是一个新颖的知识编辑框架，无需重训就能灵活高效地在各种任务中更新 LLMs。EditCoT 先为给定输入生成思维链（CoT），然后用基于更新知识的 CoT 编辑器对这个 CoT 过程进行迭代优化。我们在多种基准上对 EditCoT 进行评估，涵盖多种语言和任务。结果显示，与现有方法相比，我们的方法达到了最先进的性能，在泛化、有效性和稳定性方面表现出色，是知识更新领域的重大进步。代码和数据可在：https://github.com/bebr2/EditCoT 获取。

> Large Language Models (LLMs) have demonstrated exceptional capabilities across a wide range of natural language processing (NLP) tasks. However, keeping these models up-to-date with evolving world knowledge remains a significant challenge due to the high costs of frequent retraining. To address this challenge, knowledge editing techniques have emerged to update LLMs with new information without rebuilding the model from scratch. Among these, the in-context editing paradigm stands out for its effectiveness in integrating new knowledge while preserving the model's original capabilities. Despite its potential, existing in-context knowledge editing methods are often task-specific, focusing primarily on multi-hop QA tasks using structured knowledge triples. Moreover, their reliance on few-shot prompting for task decomposition makes them unstable and less effective in generalizing across diverse tasks.
  In response to these limitations, we propose EditCoT, a novel knowledge editing framework that flexibly and efficiently updates LLMs across various tasks without retraining. EditCoT works by generating a chain-of-thought (CoT) for a given input and then iteratively refining this CoT process using a CoT editor based on updated knowledge. We evaluate EditCoT across a diverse range of benchmarks, covering multiple languages and tasks. The results demonstrate that our approach achieves state-of-the-art performance while offering superior generalization, effectiveness, and stability compared to existing methods, marking a significant advancement in the field of knowledge updating. Code and data are available at: https://github.com/bebr2/EditCoT.

[Arxiv](https://arxiv.org/abs/2412.17727)