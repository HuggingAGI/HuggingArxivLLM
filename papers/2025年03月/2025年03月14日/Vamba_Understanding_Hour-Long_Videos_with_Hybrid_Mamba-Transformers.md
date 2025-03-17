# Vamba：探索长达一小时视频的深层含义，混合Mamba-Transformer的创新应用

发布时间：2025年03月14日

`其他

理由：这篇论文主要探讨的是大型多模态模型（LMMs）在处理长视频输入时的计算挑战，并提出了一种新的混合Mamba-Transformer模型（VAMBA）。虽然它涉及到Transformer架构，但其重点在于视频处理和模型效率的提升，而非专注于LLM的应用或理论。因此，它更适合归类到“其他”类别。` `视频处理` `视频理解`

> Vamba: Understanding Hour-Long Videos with Hybrid Mamba-Transformers

# 摘要

> 目前，基于Transformer的大型多模态模型（LMMs）在处理长达一小时的视频输入时面临巨大挑战，主要源于因果自注意力机制的二次复杂度导致的高昂计算成本。现有基于令牌压缩的方法虽能减少视频令牌数量，却往往带来信息损失，且在处理极长序列时仍效率不足。本文提出了一种全新的方法，构建了混合Mamba-Transformer模型（VAMBA），采用Mamba-2块以线性复杂度高效编码视频令牌。无需减少任何令牌，VAMBA即可在单个GPU上处理超过1024帧（640×360）的视频，而传统Transformer模型仅能处理256帧。在长视频输入下，VAMBA的训练和推理GPU内存使用量减少至少50%，且训练速度较传统LMM提升近一倍。实验结果表明，VAMBA在挑战性极高的LVBench一小时视频理解基准上，较前一代高效视频LMM准确率提升4.3%，并在各类长短视频理解任务中表现优异。

> State-of-the-art transformer-based large multimodal models (LMMs) struggle to handle hour-long video inputs due to the quadratic complexity of the causal self-attention operations, leading to high computational costs during training and inference. Existing token compression-based methods reduce the number of video tokens but often incur information loss and remain inefficient for extremely long sequences. In this paper, we explore an orthogonal direction to build a hybrid Mamba-Transformer model (VAMBA) that employs Mamba-2 blocks to encode video tokens with linear complexity. Without any token reduction, VAMBA can encode more than 1024 frames (640$\times$360) on a single GPU, while transformer-based models can only encode 256 frames. On long video input, VAMBA achieves at least 50% reduction in GPU memory usage during training and inference, and nearly doubles the speed per training step compared to transformer-based LMMs. Our experimental results demonstrate that VAMBA improves accuracy by 4.3% on the challenging hour-long video understanding benchmark LVBench over prior efficient video LMMs, and maintains strong performance on a broad spectrum of long and short video understanding tasks.

[Arxiv](https://arxiv.org/abs/2503.11579)