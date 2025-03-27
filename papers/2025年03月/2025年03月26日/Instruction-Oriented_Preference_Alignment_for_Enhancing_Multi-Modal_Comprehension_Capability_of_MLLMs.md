# 基于指令导向的偏好对齐提升多语言大语言模型的多模态理解能力

发布时间：2025年03月26日

`LLM应用` `人工智能`

> Instruction-Oriented Preference Alignment for Enhancing Multi-Modal Comprehension Capability of MLLMs

# 摘要

> 偏好对齐作为一种有效策略，在监督微调之后被提出以提升多模态大语言模型（MLLMs）的性能。尽管现有的偏好对齐方法主要针对幻觉因素，但它们忽视了对多模态理解能力至关重要的因素，通常仅限于在幻觉缓解方面进行改进。为了解决这一问题，我们提出了基于指令导向的偏好对齐（IPA），这是一个可扩展的框架，旨在根据指令完成效果自动构建对齐偏好。我们的方法涉及一个自动化的偏好构建过程，结合专门的验证流程，识别基于指令的因素，避免响应表示中的显著变化。此外，IPA还集成了一个渐进式偏好收集管道，通过模型自我进化和参考引导的优化进一步召回具有挑战性的样本。在Qwen2VL-7B上的实验表明，IPA在多个基准测试中表现出有效性，包括幻觉评估、视觉问答和文本理解任务，突显了其增强一般理解能力的能力。

> Preference alignment has emerged as an effective strategy to enhance the performance of Multimodal Large Language Models (MLLMs) following supervised fine-tuning. While existing preference alignment methods predominantly target hallucination factors, they overlook the factors essential for multi-modal comprehension capabilities, often narrowing their improvements on hallucination mitigation. To bridge this gap, we propose Instruction-oriented Preference Alignment (IPA), a scalable framework designed to automatically construct alignment preferences grounded in instruction fulfillment efficacy. Our method involves an automated preference construction coupled with a dedicated verification process that identifies instruction-oriented factors, avoiding significant variability in response representations. Additionally, IPA incorporates a progressive preference collection pipeline, further recalling challenging samples through model self-evolution and reference-guided refinement. Experiments conducted on Qwen2VL-7B demonstrate IPA's effectiveness across multiple benchmarks, including hallucination evaluation, visual question answering, and text understanding tasks, highlighting its capability to enhance general comprehension.

[Arxiv](https://arxiv.org/abs/2503.20309)