# Fane参加SemEval-2025任务10：基于大型语言模型的零样本实体框架

发布时间：2025年04月29日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在零样本分类任务中的应用，特别是如何通过优化输入上下文、提示策略和任务分解来提升模型的性能。研究重点在于实际任务中的应用和优化，属于LLM的应用研究。` `媒体与传播`

> Fane at SemEval-2025 Task 10: Zero-Shot Entity Framing with Large Language Models

# 摘要

> 理解新闻叙事如何构建实体框架对于研究媒体对社会事件认知的影响至关重要。本文中，我们评估了大型语言模型（LLMs）在零样本分类框架角色方面的能力。通过系统性实验，我们评估了输入上下文、提示策略和任务分解的影响。我们的研究发现，采用先识别宽泛角色再细化的分层方法，优于单一分类步骤。我们还证明，最优输入上下文和提示在不同任务层级上各不相同，凸显了子任务特异性策略的必要性。我们实现了89.4%的主要角色准确率和34.5%的精确匹配率，证明了我们方法的有效性。我们的研究结果强调了针对实体框架任务优化提示设计和输入上下文的重要性，以提升LLM的表现。

> Understanding how news narratives frame entities is crucial for studying media's impact on societal perceptions of events. In this paper, we evaluate the zero-shot capabilities of large language models (LLMs) in classifying framing roles. Through systematic experimentation, we assess the effects of input context, prompting strategies, and task decomposition. Our findings show that a hierarchical approach of first identifying broad roles and then fine-grained roles, outperforms single-step classification. We also demonstrate that optimal input contexts and prompts vary across task levels, highlighting the need for subtask-specific strategies. We achieve a Main Role Accuracy of 89.4% and an Exact Match Ratio of 34.5%, demonstrating the effectiveness of our approach. Our findings emphasize the importance of tailored prompt design and input context optimization for improving LLM performance in entity framing.

[Arxiv](https://arxiv.org/abs/2504.20469)