# Delta Decompression for MoE-based LLMs Compression
基于专家混合的大语言模型增量解压缩方法

发布时间：2025年02月24日

`LLM理论` `模型压缩`

> Delta Decompression for MoE-based LLMs Compression

# 摘要

> 混合专家（MoE）架构在大型语言模型（LLMs）中表现出色，但存储和内存需求却高不可攀。为了解决这一难题，我们提出了$D^2$-MoE，这是一种新型增量解压缩压缩器，旨在大幅减少MoE LLMs的参数规模。基于对专家多样性的观察，我们将它们的权重分解为共享的基础权重和独特的增量权重。具体来说，我们的方法首先利用费舍尔信息矩阵，将每个专家的权重合并到基础权重中，以捕捉共享组件。然后，我们通过奇异值分解（SVD）压缩增量权重，利用其低秩特性。最后，我们引入了一种半动态结构化剪枝策略，用于基础权重，结合静态和动态冗余分析，在保持输入自适应性的同时实现进一步的参数减少。通过这种方式，我们的$D^2$-MoE成功地将MoE LLMs压缩到高压缩率，而无需额外训练。大量实验结果表明，我们的方法在40$\sim$60%的压缩率下，对Mixtral|Phi-3.5|DeepSeek|Qwen2 MoE LLMs的性能提升了超过13%，显著优于其他压缩器。代码可在https://github.com/lliai/D2MoE获取。

> Mixture-of-Experts (MoE) architectures in large language models (LLMs) achieve exceptional performance, but face prohibitive storage and memory requirements. To address these challenges, we present $D^2$-MoE, a new delta decompression compressor for reducing the parameters of MoE LLMs. Based on observations of expert diversity, we decompose their weights into a shared base weight and unique delta weights. Specifically, our method first merges each expert's weight into the base weight using the Fisher information matrix to capture shared components. Then, we compress delta weights through Singular Value Decomposition (SVD) by exploiting their low-rank properties. Finally, we introduce a semi-dynamical structured pruning strategy for the base weights, combining static and dynamic redundancy analysis to achieve further parameter reduction while maintaining input adaptivity. In this way, our $D^2$-MoE successfully compact MoE LLMs to high compression ratios without additional training. Extensive experiments highlight the superiority of our approach, with over 13% performance gains than other compressors on Mixtral|Phi-3.5|DeepSeek|Qwen2 MoE LLMs at 40$\sim$60% compression rates. Codes are available in https://github.com/lliai/D2MoE.

[Arxiv](https://arxiv.org/abs/2502.17298)