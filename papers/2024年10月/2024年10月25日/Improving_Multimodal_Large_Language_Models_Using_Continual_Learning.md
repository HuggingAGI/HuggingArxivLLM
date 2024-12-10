# 利用持续学习提升多模态大型语言模型

发布时间：2024年10月25日

`LLM应用` `多模态学习`

> Improving Multimodal Large Language Models Using Continual Learning

# 摘要

> 生成式大型语言模型（LLMs）具备出色的能力，将预训练的视觉模型融入原始 LLM 从而创建多模态 LLM（MLLM），其能力还能进一步提升。但与原始 LLM 相比，这种集成往往会大幅降低自然语言理解和生成任务的性能。本研究借助 LLaVA MLLM 对这一问题展开探究，将集成视作持续学习问题。我们评估了五种持续学习方法以减轻遗忘，并找到了一种既能增强视觉理解又能将语言性能损失降至最低的技术。我们的方法相比 LLaVA 方案，语言性能下降幅度最多减少 15%，同时保持了较高的多模态准确率。我们还通过在一系列视觉语言任务上进行持续学习，展示了我们方法的稳健性，能在获取新的多模态能力的同时，有效地保留语言技能。

> Generative large language models (LLMs) exhibit impressive capabilities, which can be further augmented by integrating a pre-trained vision model into the original LLM to create a multimodal LLM (MLLM). However, this integration often significantly decreases performance on natural language understanding and generation tasks, compared to the original LLM. This study investigates this issue using the LLaVA MLLM, treating the integration as a continual learning problem. We evaluate five continual learning methods to mitigate forgetting and identify a technique that enhances visual understanding while minimizing linguistic performance loss. Our approach reduces linguistic performance degradation by up to 15\% over the LLaVA recipe, while maintaining high multimodal accuracy. We also demonstrate the robustness of our method through continual learning on a sequence of vision-language tasks, effectively preserving linguistic skills while acquiring new multimodal capabilities.

[Arxiv](https://arxiv.org/abs/2410.19925)