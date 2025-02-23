# PLPHP：逐层逐头视觉标记剪枝，打造高效大型视觉-语言模型

发布时间：2025年02月20日

`LLM应用` `视觉语言模型` `多模态任务`

> PLPHP: Per-Layer Per-Head Vision Token Pruning for Efficient Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）在多模态任务中表现出色，但其推理效率受限于解码过程中的大量视觉令牌处理。为解决这一问题，我们提出了一种两层细粒度剪枝方法——逐层逐头剪枝方法（PLPHP），包含层级保留率分配和头部级视觉令牌剪枝。基于解码器各层中视觉令牌再注意力现象，我们动态调整各层的令牌保留率：视觉注意力强的层保留更多视觉令牌，而注意力较弱的层则被激进剪枝。此外，PLPHP在注意力头级别应用剪枝，使同一层内的不同头可独立保留关键上下文。实验结果显示，PLPHP实现了18%的更快解码速度，将键值缓存（KV缓存）大小缩减50%以上，仅以平均性能下降0.46%为代价，同时显著提升了多图像任务的性能。这表明细粒度令牌剪枝的有效性，为提升LVLMs的效率和扩展性做出了贡献。我们的源代码即将公开发布。

> Large Vision-Language Models (LVLMs) have demonstrated remarkable capabilities across a range of multimodal tasks. However, their inference efficiency is constrained by the large number of visual tokens processed during decoding. To address this challenge, we propose Per-Layer Per-Head Vision Token Pruning (PLPHP), a two-level fine-grained pruning method including Layer-Level Retention Rate Allocation and Head-Level Vision Token Pruning. Motivated by the Vision Token Re-attention phenomenon across decoder layers, we dynamically adjust token retention rates layer by layer. Layers that exhibit stronger attention to visual information preserve more vision tokens, while layers with lower vision attention are aggressively pruned. Furthermore, PLPHP applies pruning at the attention head level, enabling different heads within the same layer to independently retain critical context. Experiments on multiple benchmarks demonstrate that PLPHP delivers an 18% faster decoding speed and reduces the Key-Value Cache (KV Cache) size by over 50%, all at the cost of 0.46% average performance drop, while also achieving notable performance improvements in multi-image tasks. These results highlight the effectiveness of fine-grained token pruning and contribute to advancing the efficiency and scalability of LVLMs. Our source code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2502.14504)