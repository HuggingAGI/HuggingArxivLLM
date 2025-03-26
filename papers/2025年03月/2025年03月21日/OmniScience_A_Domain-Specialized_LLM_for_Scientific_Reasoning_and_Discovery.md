# OmniScience：专为科学推理与发现打造的领域专用大型语言模型

发布时间：2025年03月21日

`LLM应用

理由：这篇论文主要介绍了OmniScience模型在科学推理任务中的应用，展示了其在电池评估中的具体使用案例，并通过实验验证了其在特定领域的有效性。这属于将大型语言模型应用于特定科学任务的范畴，因此归类为LLM应用。`

> OmniScience: A Domain-Specialized LLM for Scientific Reasoning and Discovery

# 摘要

> 大型语言模型（LLMs）在推动科学进步和解决复杂挑战方面展现出巨大潜力。本研究推出OmniScience——专为通用科学设计的大型推理模型，其开发基于三大关键组件：(1) 在精选科学文献语料库上进行领域自适应预训练，(2) 在专业数据集上进行指令微调以完成特定任务，(3) 通过基于推理的知识蒸馏优化，显著提升生成上下文相关且逻辑严谨回答的能力。我们通过开发一个高效电池代理展示了OmniScience的多功能性，该代理能有效评估分子作为潜在电解液溶剂或添加剂的潜力。全面评估显示，OmniScience在GPQA钻石基准和特定领域电池基准上与最先进大型推理模型相媲美，同时超越了所有具有相似参数量的公共推理和非推理模型。消融实验进一步证明，领域自适应预训练和基于推理的知识蒸馏是实现其高性能的关键，这一结论在各项基准测试中均得到验证。

> Large Language Models (LLMs) have demonstrated remarkable potential in advancing scientific knowledge and addressing complex challenges. In this work, we introduce OmniScience, a specialized large reasoning model for general science, developed through three key components: (1) domain adaptive pretraining on a carefully curated corpus of scientific literature, (2) instruction tuning on a specialized dataset to guide the model in following domain-specific tasks, and (3) reasoning-based knowledge distillation through fine-tuning to significantly enhance its ability to generate contextually relevant and logically sound responses. We demonstrate the versatility of OmniScience by developing a battery agent that efficiently ranks molecules as potential electrolyte solvents or additives. Comprehensive evaluations reveal that OmniScience is competitive with state-of-the-art large reasoning models on the GPQA Diamond and domain-specific battery benchmarks, while outperforming all public reasoning and non-reasoning models with similar parameter counts. We further demonstrate via ablation experiments that domain adaptive pretraining and reasoning-based knowledge distillation are critical to attain our performance levels, across benchmarks.

[Arxiv](https://arxiv.org/abs/2503.17604)