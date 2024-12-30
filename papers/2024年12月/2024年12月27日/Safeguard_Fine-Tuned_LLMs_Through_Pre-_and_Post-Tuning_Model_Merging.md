# 通过预调和后调模型的合并来守护微调后的大型语言模型（LLMs）

发布时间：2024年12月27日

`LLM应用` `语言模型` `下游任务`

> Safeguard Fine-Tuned LLMs Through Pre- and Post-Tuning Model Merging

# 摘要

> 微调大型语言模型（LLMs）用于下游任务是常见做法，然而这常致使安全对齐的 LLMs 安全性降低。当下，众多解决方案借助纳入额外的安全数据来应对此问题，但很多时候这不太可行。本文中，我们提出这样一个疑问：不依赖额外安全数据，如何在 LLMs 中提升下游任务性能的同时保障安全性？我们给出了一个简便且有效的办法，即在提升下游任务性能的同时维持 LLMs 固有的安全性：融合预微调及微调后安全对齐模型的权重。在各类下游任务、模型和融合方法中的实验结果显示，该方法有效缓解了安全性下降的情况，同时提高了下游任务性能，为适配安全对齐的 LLMs 提供了实用的解决方案。

> Fine-tuning large language models (LLMs) for downstream tasks is a widely adopted approach, but it often leads to safety degradation in safety-aligned LLMs. Currently, many solutions address this issue by incorporating additional safety data, which can be impractical in many cases. In this paper, we address the question: How can we improve downstream task performance while preserving safety in LLMs without relying on additional safety data? We propose a simple and effective method that maintains the inherent safety of LLMs while enhancing their downstream task performance: merging the weights of pre- and post-fine-tuned safety-aligned models. Experimental results across various downstream tasks, models, and merging methods demonstrate that this approach effectively mitigates safety degradation while improving downstream task performance, offering a practical solution for adapting safety-aligned LLMs.

[Arxiv](https://arxiv.org/abs/2412.19512)