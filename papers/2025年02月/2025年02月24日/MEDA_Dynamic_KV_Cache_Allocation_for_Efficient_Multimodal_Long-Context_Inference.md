# MEDA：高效多模态长上下文推理的动态 KV 缓存分配方案

发布时间：2025年02月24日

`LLM理论` `多模态处理` `计算效率`

> MEDA: Dynamic KV Cache Allocation for Efficient Multimodal Long-Context Inference

# 摘要

> 长上下文多模态大型语言模型（MLLMs），在处理长文本-图像和文本-视频模态时，由于多模态键值（KV）缓存需求随输入长度增长而增加，推理效率面临挑战。现有KV缓存压缩方法，无论是针对文本还是多模态LLMs，都未考虑不同层间注意力密度的差异，通常采用统一或递减策略进行逐层缓存分配。本研究提出MEDA，一种动态逐层KV缓存分配方法，旨在提升多模态长上下文推理效率。MEDA的核心是通过跨模态注意力熵确定MLLMs各层的KV缓存大小。基于动态分配的KV缓存大小，MEDA采用KV对选择方案，识别需选择的KV对，并通过合并策略将选定与未选定的KV对整合，以保留完整上下文信息。实验结果显示，MEDA实现高达72%的KV缓存内存减少，解码速度提升2.82倍，且在长上下文多模态任务中保持或提升性能，包括多图像和长视频场景。我们的代码已开源，地址为https://github.com/AIoT-MLSys-Lab/MEDA。

> Long-context Multimodal Large Language Models (MLLMs) that incorporate long text-image and text-video modalities, demand substantial resources as their multimodal Key-Value (KV) caches grow with increasing input lengths, challenging inference efficiency. Existing methods for KV cache compression, in both text-only and multimodal LLMs, have neglected attention density variations across layers, thus often adopting uniform or progressive reduction strategies for layer-wise cache allocation. In this work, we propose MEDA, a dynamic layer-wise KV cache allocation method for efficient multimodal long-context inference. As its core, MEDA utilizes cross-modal attention entropy to determine the KV cache size at each MLLMs layer. Given the dynamically allocated KV cache size at each layer, MEDA also employs a KV pair selection scheme to identify which KV pairs to select and a KV pair merging strategy that merges the selected and non-selected ones to preserve information from the entire context. MEDA achieves up to 72% KV cache memory reduction and 2.82 times faster decoding speed, while maintaining or enhancing performance on various multimodal tasks in long-context settings, including multi-images and long-video scenarios. Our code is released at https://github.com/AIoT-MLSys-Lab/MEDA.

[Arxiv](https://arxiv.org/abs/2502.17599)