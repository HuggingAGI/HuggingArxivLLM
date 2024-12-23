# PruneVid：针对高效视频大型语言模型的视觉标记修剪

发布时间：2024年12月20日

`LLM应用` `多模态`

> PruneVid: Visual Token Pruning for Efficient Video Large Language Models

# 摘要

> 在本文中，我们推出了 PruneVid，这是一种用于提升多模态视频理解效率的视觉标记修剪法。大型语言模型（LLMs）凭借其在理解视觉模态上的拓展能力，于视频任务中展现出良好的性能。但视频数据存在大量冗余，给 LLMs 带来巨大的计算难题。为应对此问题，我们引入了一种免训练的方法，其一是通过合并时空标记来降低视频冗余，其二是借助 LLMs 的推理能力，有针对性地修剪与问题标记相关的视觉特征，从而提高模型效率。我们在多个视频基准上对该方法进行了验证，结果表明 PruneVid 能够修剪超过 80%的标记，且在与不同模型网络结合时仍能保持出色的性能。这凸显出它相较于现有修剪方法，具有更出色的有效性和效率。代码：https://github.com/Visual-AI/PruneVid。

> In this paper, we introduce PruneVid, a visual token pruning method designed to enhance the efficiency of multi-modal video understanding. Large Language Models (LLMs) have shown promising performance in video tasks due to their extended capabilities in comprehending visual modalities. However, the substantial redundancy in video data presents significant computational challenges for LLMs. To address this issue, we introduce a training-free method that 1) minimizes video redundancy by merging spatial-temporal tokens, and 2) leverages LLMs' reasoning capabilities to selectively prune visual features relevant to question tokens, enhancing model efficiency. We validate our method across multiple video benchmarks, which demonstrate that PruneVid can prune over 80% of tokens while maintaining competitive performance combined with different model networks. This highlights its superior effectiveness and efficiency compared to existing pruning methods. Code: https://github.com/Visual-AI/PruneVid.

[Arxiv](https://arxiv.org/abs/2412.16117)