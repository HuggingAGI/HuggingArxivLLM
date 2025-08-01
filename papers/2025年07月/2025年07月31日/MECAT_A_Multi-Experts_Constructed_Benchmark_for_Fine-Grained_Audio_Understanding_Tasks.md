# MECAT：一个多专家共同构建的细粒度音频理解任务基准

发布时间：2025年07月31日

`LLM应用

理由：这篇论文主要讨论了如何通过引入新的基准测试和评估指标来提升大型音频语言模型的性能评估。它详细描述了MECAT基准的构建过程以及DATE评估指标的设计，这些都是大型语言模型在实际应用中的具体应用和优化。因此，这篇论文属于LLM应用类别。` `评估方法`

> MECAT: A Multi-Experts Constructed Benchmark for Fine-Grained Audio Understanding Tasks

# 摘要

> 大型音频语言模型在开放性音频理解方面虽有进步，但仍未达到细腻的人类级理解水平。这一差距主要源于现有基准测试受限于数据标注和评估指标，无法可靠区分模型输出中的通用内容与高度详细内容。为此，本研究引入了MECAT（多专家构建的细粒度音频理解任务基准）。通过整合专业专家模型的分析与链式思维大型语言模型推理的流水线，MECAT提供了多视角、细粒度的标注和开放集问题-答案对。该基准还配备了一种新颖的评估指标：DATE（判别增强的音频文本评估）。DATE通过结合单样本语义相似性和跨样本可区分性，惩罚通用术语并奖励详细描述。此外，本研究还对当前最先进的音频模型进行了全面评估，揭示了它们当前的能力与局限性。数据和代码可在https://github.com/xiaomi-research/mecat获取。

> While large audio-language models have advanced open-ended audio understanding, they still fall short of nuanced human-level comprehension. This gap persists largely because current benchmarks, limited by data annotations and evaluation metrics, fail to reliably distinguish between generic and highly detailed model outputs. To this end, this work introduces MECAT, a Multi-Expert Constructed Benchmark for Fine-Grained Audio Understanding Tasks. Generated via a pipeline that integrates analysis from specialized expert models with Chain-of-Thought large language model reasoning, MECAT provides multi-perspective, fine-grained captions and open-set question-answering pairs. The benchmark is complemented by a novel metric: DATE (Discriminative-Enhanced Audio Text Evaluation). This metric penalizes generic terms and rewards detailed descriptions by combining single-sample semantic similarity with cross-sample discriminability. A comprehensive evaluation of state-of-the-art audio models is also presented, providing new insights into their current capabilities and limitations. The data and code are available at https://github.com/xiaomi-research/mecat

[Arxiv](https://arxiv.org/abs/2507.23511)