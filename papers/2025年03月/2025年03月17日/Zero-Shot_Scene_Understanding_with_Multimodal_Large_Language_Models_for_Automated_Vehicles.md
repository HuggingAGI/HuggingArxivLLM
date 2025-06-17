# # 零样本场景理解：多模态大型语言模型赋能自动驾驶

发布时间：2025年03月17日

`LLM应用` `自动驾驶` `智能驾驶`

> Zero-Shot Scene Understanding with Multimodal Large Language Models for Automated Vehicles

# 摘要

> 场景理解在自动驾驶中发挥着关键作用，它不仅有助于驾驶员与自动驾驶系统之间的沟通，还能提升人们对自动驾驶决策的理解。本文研究了四个多模态大语言模型（MLLMs），包括较小规模的模型，在零样本和上下文学习设置下的场景理解能力。此外，我们还探索了通过集成方法结合多数投票来提升场景理解的效果。实验结果显示，GPT-4o作为最大的模型，在场景理解方面表现最佳。然而，GPT-4o与较小模型之间的差距并不悬殊，这表明通过改进上下文学习、检索增强生成（RAG）或微调等方法，可以进一步优化较小模型的性能。对于集成方法，我们发现其效果并不一致：某些场景属性在F1分数等指标上有所提升，但也有部分属性表现下降。这些结果表明，我们需要更先进的集成技术，才能在所有场景属性上实现一致的性能提升。本研究不仅展示了MLLMs在场景理解方面的潜力，还为优化其在自动驾驶中的应用提供了有价值的见解。


> Scene understanding is critical for various downstream tasks in autonomous driving, including facilitating driver-agent communication and enhancing human-centered explainability of autonomous vehicle (AV) decisions. This paper evaluates the capability of four multimodal large language models (MLLMs), including relatively small models, to understand scenes in a zero-shot, in-context learning setting. Additionally, we explore whether combining these models using an ensemble approach with majority voting can enhance scene understanding performance. Our experiments demonstrate that GPT-4o, the largest model, outperforms the others in scene understanding. However, the performance gap between GPT-4o and the smaller models is relatively modest, suggesting that advanced techniques such as improved in-context learning, retrieval-augmented generation (RAG), or fine-tuning could further optimize the smaller models' performance. We also observe mixed results with the ensemble approach: while some scene attributes show improvement in performance metrics such as F1-score, others experience a decline. These findings highlight the need for more sophisticated ensemble techniques to achieve consistent gains across all scene attributes. This study underscores the potential of leveraging MLLMs for scene understanding and provides insights into optimizing their performance for autonomous driving applications.

[Arxiv](https://arxiv.org/abs/2506.12232)