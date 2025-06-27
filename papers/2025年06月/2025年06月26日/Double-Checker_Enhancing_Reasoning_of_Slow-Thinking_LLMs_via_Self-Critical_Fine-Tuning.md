# 双检机制：通过自我批判式微调提升慢思考大语言模型的推理能力

发布时间：2025年06月26日

`LLM理论`

> Double-Checker: Enhancing Reasoning of Slow-Thinking LLMs via Self-Critical Fine-Tuning

# 摘要

> 尽管慢思维大型语言模型（LLMs）展现了类似“顿悟时刻”的反思推理能力，但它们生成有见地的批评并完善先前解决方案的能力仍然有限。本文中，我们介绍了Double-Checker，一个旨在通过培养明确的自我批评和对先前解决方案的迭代完善来增强慢思维LLMs推理能力的系统性框架。通过在我们整理的1,730个自我批判实例上进行微调，Double-Checker使长链推理LLMs能够在推理过程中迭代地批评和优化其输出，直至它们在自我生成的批评下评估其解决方案为正确。我们在全面的推理基准测试中验证了Double-Checker的有效性，证明了迭代自我批评显著增强了长链推理LLMs的推理能力。值得注意的是，与原始的长链推理LLMs相比，我们的Double-Checker将具有挑战性的AIME基准测试中的pass@1性能从4.4%提升至18.2%。这些结果凸显了开发能够进行结构化自我批评、更值得信赖且有效的LLMs的有希望的方向。

> While slow-thinking large language models (LLMs) exhibit reflection-like reasoning, commonly referred to as the "aha moment:, their ability to generate informative critiques and refine prior solutions remains limited. In this paper, we introduce Double-Checker, a principled framework designed to enhance the reasoning capabilities of slow-thinking LLMs by fostering explicit self-critique and iterative refinement of their previous solutions. By fine-tuning on our curated 1,730 self-critical instances, Double-Checker empowers long-CoT LLMs to iteratively critique and refine their outputs during inference until they evaluate their solutions as correct under self-generated critiques. We validate the efficacy of Double-Checker across a comprehensive suite of reasoning benchmarks, demonstrating that iterative self-critique significantly enhances the reasoning capabilities of long-CoT LLMs. Notably, our Double-Checker increases the pass@1 performance on challenging AIME benchmarks from 4.4% to 18.2% compared to the original long-CoT LLMs. These results highlight a promising direction for developing more trustworthy and effective LLMs capable of structured self-critique.

[Arxiv](https://arxiv.org/abs/2506.21285)