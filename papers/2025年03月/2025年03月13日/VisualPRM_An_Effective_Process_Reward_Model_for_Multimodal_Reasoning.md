# VisualPRM：一种用于多模态推理的有效过程奖励模型

发布时间：2025年03月13日

`LLM应用` `多模态大型语言模型` `数据集与基准测试`

> VisualPRM: An Effective Process Reward Model for Multimodal Reasoning

# 摘要

> 我们很高兴推出VisualPRM——一款拥有80亿参数的先进多模态过程奖励模型（PRM）。它通过最佳-of-N（BoN）评估策略，显著提升了现有多种规模和家族的多模态大型语言模型（MLLMs）的推理能力。具体来说，我们的模型在三种不同类型的MLLMs和四个不同规模的模型上均实现了推理性能的提升。即使应用于强大的InternVL2.5-78B，它在七个多模态推理基准测试中也取得了5.9分的显著提升。实验结果表明，在最佳-of-N（BoN）评估中，我们的模型相较于结果奖励模型和自我一致性方法表现更优。为了推动多模态PRMs的训练，我们通过自动化数据管道构建了一个包含40万条数据的多模态过程监督数据集——VisualPRM400K。在评估多模态PRMs方面，我们提出了VisualProcessBench，这是一个带有逐步正确性标签的数据集，用于衡量PRMs在多模态推理任务中检测错误步骤的能力。我们希望这项工作能够激发未来的研究，并为多模态大型语言模型的发展做出贡献。我们的模型、数据集和基准测试已发布在https://internvl.github.io/blog/2025-03-13-VisualPRM/。

> We introduce VisualPRM, an advanced multimodal Process Reward Model (PRM) with 8B parameters, which improves the reasoning abilities of existing Multimodal Large Language Models (MLLMs) across different model scales and families with Best-of-N (BoN) evaluation strategies. Specifically, our model improves the reasoning performance of three types of MLLMs and four different model scales. Even when applied to the highly capable InternVL2.5-78B, it achieves a 5.9-point improvement across seven multimodal reasoning benchmarks. Experimental results show that our model exhibits superior performance compared to Outcome Reward Models and Self-Consistency during BoN evaluation. To facilitate the training of multimodal PRMs, we construct a multimodal process supervision dataset VisualPRM400K using an automated data pipeline. For the evaluation of multimodal PRMs, we propose VisualProcessBench, a benchmark with human-annotated step-wise correctness labels, to measure the abilities of PRMs to detect erroneous steps in multimodal reasoning tasks. We hope that our work can inspire more future research and contribute to the development of MLLMs. Our model, data, and benchmark are released in https://internvl.github.io/blog/2025-03-13-VisualPRM/.

[Arxiv](https://arxiv.org/abs/2503.10291)