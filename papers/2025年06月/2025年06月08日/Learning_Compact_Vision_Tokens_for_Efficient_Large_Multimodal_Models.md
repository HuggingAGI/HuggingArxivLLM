# 学习紧凑视觉令牌，构建高效大型多模态模型

发布时间：2025年06月08日

`LLM应用` `视觉-语言` `人工智能`

> Learning Compact Vision Tokens for Efficient Large Multimodal Models

# 摘要

> 大型多模态模型（LMMs）在计算上面临两大挑战：大型语言模型（LLMs）的高成本以及处理长视觉令牌序列的二次复杂度。本文提出了一种创新方法，通过探索视觉令牌的空间冗余来缩短视觉令牌序列，从而加速推理过程。具体而言，我们提出了空间令牌融合（STF）方法，将空间相邻的令牌融合为一个，从而学习出更紧凑的视觉令牌序列。此外，针对权重固定的视觉编码器在适应广泛下游视觉-语言任务时的不足，我们引入了多块令牌融合（MBTF）模块，为减少的令牌序列补充多粒度特征。通过将STF与MBTF模块相结合，我们在平衡令牌减少和信息保留的同时，显著提升了推理效率，且未牺牲多模态推理能力。实验结果表明，我们基于LLaVA-1.5的方法在仅使用基准25%视觉令牌的情况下，在8个流行视觉-语言基准测试中实现了与基准相当甚至更优的性能。源代码和训练权重可在https://github.com/visresearch/LLaVA-STF获得。

> Large multimodal models (LMMs) suffer significant computational challenges due to the high cost of Large Language Models (LLMs) and the quadratic complexity of processing long vision token sequences. In this paper, we explore the spatial redundancy among vision tokens and shorten the length of vision token sequences for inference acceleration. Specifically, we propose a Spatial Token Fusion (STF) method to learn compact vision tokens for short vision token sequence, where spatial-adjacent tokens are fused into one. Meanwhile, weight-frozen vision encoder can not well adapt to the demand of extensive downstream vision-language tasks. To this end, we further introduce a Multi-Block Token Fusion (MBTF) module to supplement multi-granularity features for the reduced token sequence. Overall, we combine STF and MBTF module to balance token reduction and information preservation, thereby improving inference efficiency without sacrificing multimodal reasoning capabilities. Experimental results demonstrate that our method based on LLaVA-1.5 achieves comparable or even superior performance to the baseline on 8 popular vision-language benchmarks with only $25\%$ vision tokens of baseline. The source code and trained weights are available at https://github.com/visresearch/LLaVA-STF.

[Arxiv](https://arxiv.org/abs/2506.07138)