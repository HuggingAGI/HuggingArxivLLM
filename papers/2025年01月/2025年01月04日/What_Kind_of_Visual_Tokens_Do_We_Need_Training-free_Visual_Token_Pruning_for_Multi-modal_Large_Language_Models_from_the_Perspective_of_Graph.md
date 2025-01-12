# 我们需要什么样的视觉标记？基于图视角的多模态大型语言模型无训练视觉标记剪枝

发布时间：2025年01月04日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）中的视觉标记剪枝方法，旨在降低计算成本并保持模型性能。虽然涉及到了模型的优化和改进，但其核心仍然是针对大型语言模型的应用场景，特别是多模态任务中的视觉处理。因此，将其归类为LLM应用是合适的。` `计算机视觉`

> What Kind of Visual Tokens Do We Need? Training-free Visual Token Pruning for Multi-modal Large Language Models from the Perspective of Graph

# 摘要

> # 摘要
最近的多模态大型语言模型（MLLMs）常常依赖大量视觉标记来弥补视觉缺陷，但这带来了高计算成本和明显的视觉冗余。本文探讨了MLLMs所需的视觉标记类型，发现前景和背景标记在不同难度的任务中都至关重要。基于这一发现，我们提出了一种基于图的无需训练的视觉标记剪枝方法——G-Prune。G-Prune将视觉标记视为节点，通过语义相似性构建连接，并通过加权链接传播信息流，最终保留最重要的标记（无论是前景还是背景）。我们将G-Prune应用于最新的MLLM模型LLaVA-NeXT，并在多个基准上进行了广泛实验。结果表明，G-Prune能显著降低计算开销，同时在粗粒度和细粒度任务上保持高性能。例如，在VQA2.0和TextVQA任务中，G-Prune分别减少了63.57%的FLOPs，而准确率仅下降0.95%和2.34%。

> Recent Multimodal Large Language Models(MLLMs) often use a large number of visual tokens to compensate their visual shortcoming, leading to excessive computation and obvious visual redundancy. In this paper, we investigate what kind of visual tokens are needed for MLLMs, and reveal that both foreground and background tokens are critical for MLLMs given the varying difficulties of examples. Based on this observation, we propose a graph-based method towards training-free visual token pruning, termed G-Prune.In particular, G-Prune regards visual tokens as nodes, and construct their connections based on their semantic similarities. Afterwards, the information flow is propagated via weighted links, and the most important tokens after iterations are kept for MLLMs, which can be front or background.To validate G-Prune, we apply it to a recent MLLM called LLaVA-NeXT, and conduct extensive experiments on a set of benchmarks.The experiment results show that G-Prune can greatly reduce computation overhead while retaining high performance on both coarse- and fine-grained tasks. For instance, G-Prune can reduce 63.57\% FLOPs of LLaVA-NeXT on VQA2.0 and TextVQA with only 0.95\% and 2.34\% accuracy drops, respectively.

[Arxiv](https://arxiv.org/abs/2501.02268)