# 长短期对齐：LLMs中有效长上下文建模的方法

发布时间：2025年06月13日

`LLM理论` `人工智能`

> Long-Short Alignment for Effective Long-Context Modeling in LLMs

# 摘要

> 大型语言模型（LLMs）不仅性能出色，还展现了许多令人惊喜的特性。然而，受限于transformer架构中固定的上下文窗口，其在长上下文建模方面仍存在挑战。其中，长度泛化——即模型在处理比训练中见过的更长序列时的泛化能力——是一个关键且基础性的问题。在本研究中，我们提出了一个全新的视角，不再局限于传统的输入特征（如位置编码或数据结构），而是关注模型的输出分布。通过在合成任务上的案例研究，我们发现	extbf{长-短对齐}——不同长度序列上输出分布的一致性——至关重要。将这一发现应用于自然语言任务，我们提出了一种名为长-短错配的指标来量化这一现象，并发现该指标与长度泛化性能密切相关。基于此，我们开发了一种正则化项，以在训练过程中促进长-短对齐。大量实验验证了我们的方法的有效性，为实现LLMs中更高效的长上下文建模提供了新思路。代码可在https://github.com/PKU-ML/LongShortAlignment获取。

> Large language models (LLMs) have exhibited impressive performance and surprising emergent properties. However, their effectiveness remains limited by the fixed context window of the transformer architecture, posing challenges for long-context modeling. Among these challenges, length generalization -- the ability to generalize to sequences longer than those seen during training -- is a classical and fundamental problem. In this work, we propose a fresh perspective on length generalization, shifting the focus from the conventional emphasis on input features such as positional encodings or data structures to the output distribution of the model. Specifically, through case studies on synthetic tasks, we highlight the critical role of \textbf{long-short alignment} -- the consistency of output distributions across sequences of varying lengths. Extending this insight to natural language tasks, we propose a metric called Long-Short Misalignment to quantify this phenomenon, uncovering a strong correlation between the metric and length generalization performance. Building on these findings, we develop a regularization term that promotes long-short alignment during training. Extensive experiments validate the effectiveness of our approach, offering new insights for achieving more effective long-context modeling in LLMs. Code is available at https://github.com/PKU-ML/LongShortAlignment.

[Arxiv](https://arxiv.org/abs/2506.11769)