# # 思考、剪枝、训练、提升：在不扩大模型规模的情况下提升推理能力

发布时间：2025年04月25日

`LLM理论` `数学推理`

> Think, Prune, Train, Improve: Scaling Reasoning without Scaling Models

# 摘要

> 大型语言模型（LLMs）在编程和数学推理方面表现出色，但受限于高质量训练数据的不足。合成数据可助力提升微调效果，但模型规模、合成数据量、剪枝策略和微调轮数等因素会影响这一过程。我们深入探讨了这些影响因素，研究了哪些条件能让模型实现自我改进。我们提出了名为Think, Prune, Train的流程，这是一个可扩展的框架，通过迭代地在模型自身的推理轨迹上进行微调，并采用基于真实数据的剪枝策略来确保训练数据的质量。这一方法显著提升了性能：在GSM8K数据集上，Gemma2-2B的Pass@1指标从41.9%提升至57.6%，Gemma2-9B达到82%，与LLaMA-3.1-70B持平，而LLaMA-3.1-70B更是达到91%，甚至超越了GPT-4o，证明了通过自生成推理和系统化数据选择来提升LLM能力的有效性。

> Large language models (LLMs) have demonstrated strong capabilities in programming and mathematical reasoning tasks, but are constrained by limited high-quality training data. Synthetic data can be leveraged to enhance fine-tuning outcomes, but several factors influence this process, including model size, synthetic data volume, pruning strategy, and number of fine-tuning rounds. We explore these axes and investigate which conditions enable model self-improvement. We introduce the Think, Prune, Train process, a scalable framework that iteratively fine-tunes models on their own reasoning traces, using ground-truth pruning to ensure high-quality training data. This approach yields improved performance: on GSM8K, Gemma2-2B achieves a Pass@1 of 57.6% (from 41.9%), Gemma2-9B reaches 82%, matching LLaMA-3.1-70B, and LLaMA-3.1-70B attains 91%, even surpassing GPT-4o, demonstrating the effectiveness of self-generated reasoning and systematic data selection for improving LLM capabilities.

[Arxiv](https://arxiv.org/abs/2504.18116)