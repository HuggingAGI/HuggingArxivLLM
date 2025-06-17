# # 零样本场景理解：多模态大语言模型在自动驾驶中的应用
零样本场景理解（Zero-Shot Scene Understanding）是多模态大语言模型在自动驾驶领域的一项创新技术。它通过融合视觉与语言等多模态信息，无需额外标注数据即可直接理解复杂的交通场景，为自动驾驶提供了全新的解决方案。

发布时间：2025年03月17日

`LLM应用

摘要讨论了多模态大语言模型（MLLMs）在自动驾驶场景理解中的应用，评估了它们的性能并探讨了改进方法，如RAG和集成技术。这些内容属于LLM的应用层面。` `自动驾驶`

> Zero-Shot Scene Understanding with Multimodal Large Language Models for Automated Vehicles

# 摘要

> 场景理解是自动驾驶中众多下游任务的关键，它不仅促进驾驶员与自动驾驶系统之间的沟通，还能增强人们对自动驾驶决策的理解。本文评估了四个多模态大语言模型（MLLMs）在零样本和上下文学习设置下的场景理解能力，包括一些较小的模型。此外，我们还研究了通过多数投票的集成方法组合这些模型是否能提升场景理解性能。实验结果显示，GPT-4o（最大的模型）在场景理解方面表现最佳。然而，GPT-4o与较小模型之间的性能差距并不悬殊，这表明改进上下文学习、检索增强生成（RAG）或微调等高级技术可能进一步优化较小模型的性能。我们还发现集成方法的效果并不一致：某些场景属性的F1分数等性能指标有所提升，而其他属性则有所下降。这些发现凸显了开发更复杂的集成技术以实现所有场景属性性能全面提升的必要性。本研究不仅展现了MLLMs在场景理解方面的潜力，还为优化其在自动驾驶应用中的性能提供了有价值的见解。

> Scene understanding is critical for various downstream tasks in autonomous driving, including facilitating driver-agent communication and enhancing human-centered explainability of autonomous vehicle (AV) decisions. This paper evaluates the capability of four multimodal large language models (MLLMs), including relatively small models, to understand scenes in a zero-shot, in-context learning setting. Additionally, we explore whether combining these models using an ensemble approach with majority voting can enhance scene understanding performance. Our experiments demonstrate that GPT-4o, the largest model, outperforms the others in scene understanding. However, the performance gap between GPT-4o and the smaller models is relatively modest, suggesting that advanced techniques such as improved in-context learning, retrieval-augmented generation (RAG), or fine-tuning could further optimize the smaller models' performance. We also observe mixed results with the ensemble approach: while some scene attributes show improvement in performance metrics such as F1-score, others experience a decline. These findings highlight the need for more sophisticated ensemble techniques to achieve consistent gains across all scene attributes. This study underscores the potential of leveraging MLLMs for scene understanding and provides insights into optimizing their performance for autonomous driving applications.

[Arxiv](https://arxiv.org/abs/2506.12232)