# OmniAlign-V：提升MLLM与人类偏好对齐的研究探索

发布时间：2025年02月25日

`LLM应用` `人工智能` `机器学习`

> OmniAlign-V: Towards Enhanced Alignment of MLLMs with Human Preference

# 摘要

> 开源多模态大语言模型（MLLMs）的最新进展主要集中在基础能力的提升上，但在与人类偏好对齐方面仍存在显著差距。本研究推出OmniAlign-V，一个包含20万高质量训练样本的综合性数据集，囊括多样化图像、复杂问题和多样的响应格式，旨在增强MLLMs与人类偏好的对齐能力。同时，我们开发了MM-AlignBench，一个专为评估MLLMs与人类价值观对齐程度设计的人工标注基准。实验结果表明，通过OmniAlign-V对MLLMs进行监督式微调（SFT）或直接偏好优化（DPO）微调，能显著提升模型与人类偏好的对齐效果，同时保持或提升其在标准VQA基准上的性能，确保基础能力不受影响。我们的数据集、基准、代码和检查点已开放获取，详情请访问https://github.com/PhoenixZ810/OmniAlign-V。

> Recent advancements in open-source multi-modal large language models (MLLMs) have primarily focused on enhancing foundational capabilities, leaving a significant gap in human preference alignment. This paper introduces OmniAlign-V, a comprehensive dataset of 200K high-quality training samples featuring diverse images, complex questions, and varied response formats to improve MLLMs' alignment with human preferences. We also present MM-AlignBench, a human-annotated benchmark specifically designed to evaluate MLLMs' alignment with human values. Experimental results show that finetuning MLLMs with OmniAlign-V, using Supervised Fine-Tuning (SFT) or Direct Preference Optimization (DPO), significantly enhances human preference alignment while maintaining or enhancing performance on standard VQA benchmarks, preserving their fundamental capabilities. Our datasets, benchmark, code and checkpoints have been released at https://github.com/PhoenixZ810/OmniAlign-V.

[Arxiv](https://arxiv.org/abs/2502.18411)