# Condor：利用知识驱动的数据合成与精炼提升LLM对齐效果

发布时间：2025年01月21日

`LLM应用

**理由**：这篇论文主要讨论了如何通过合成数据生成框架（Condor）来提升大型语言模型（LLMs）的对话能力，并展示了该方法在微调模型时的有效性。这属于LLM在实际应用中的优化和改进，因此分类为LLM应用。` `机器学习`

> Condor: Enhance LLM Alignment with Knowledge-Driven Data Synthesis and Refinement

# 摘要

> 监督微调（SFT）数据的质量对提升大型语言模型（LLMs）的对话能力至关重要。然而，随着LLMs的不断进步，高质量的人工标注SFT数据变得稀缺，这促使我们更多地依赖合成训练数据。本文提出Condor，一个创新的两阶段合成数据生成框架，结合世界知识树和自我反思精炼，能够大规模生成高质量的SFT数据。实验表明，仅用20K Condor生成的样本微调的基础模型，性能优于其他模型。Condor的精炼阶段还支持LLMs在不同规模（最高72B）上的迭代自我改进，证明了该方法的有效性。此外，我们对合成数据在训练后扩展的研究揭示了性能提升的巨大潜力，为未来研究提供了新的方向。

> The quality of Supervised Fine-Tuning (SFT) data plays a critical role in enhancing the conversational capabilities of Large Language Models (LLMs). However, as LLMs become more advanced, the availability of high-quality human-annotated SFT data has become a significant bottleneck, necessitating a greater reliance on synthetic training data. In this work, we introduce Condor, a novel two-stage synthetic data generation framework that incorporates World Knowledge Tree and Self-Reflection Refinement to produce high-quality SFT data at scale. Our experimental results demonstrate that a base model fine-tuned on only 20K Condor-generated samples achieves superior performance compared to counterparts. The additional refinement stage in Condor further enables iterative self-improvement for LLMs at various scales (up to 72B), validating the effectiveness of our approach. Furthermore, our investigation into the scaling for synthetic data in post-training reveals substantial unexplored potential for performance improvements, opening promising avenues for future research.

[Arxiv](https://arxiv.org/abs/2501.12273)