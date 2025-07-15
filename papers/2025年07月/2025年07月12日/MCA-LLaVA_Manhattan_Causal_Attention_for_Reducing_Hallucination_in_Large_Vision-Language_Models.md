# MCA-LLaVA：降低大型视觉-语言模型幻觉现象的曼哈顿因果注意力机制

发布时间：2025年07月12日

`LLM理论` `人工智能` `多模态模型`

> MCA-LLaVA: Manhattan Causal Attention for Reducing Hallucination in Large Vision-Language Models

# 摘要

> 幻觉在大型视觉语言模型（LVLMs）中构成重大挑战，多模态特征的不一致是关键影响因素。本文揭示了用于 LVLM 位置建模的旋转位置编码（RoPE）长期衰减对多模态对齐的负面影响。具体而言，在长期衰减情况下，指令令牌对二维空间中不同位置的图像令牌表现出不均匀感知：优先感知位于底部右侧的图像令牌，因为在一维序列中，这些令牌在位置上更接近指令令牌。这种有偏感知导致图像-指令交互不足，进而造成次优的多模态对齐。我们称此现象为图像对齐偏差。为了提升指令对不同空间位置图像令牌的感知能力，我们基于曼哈顿距离提出 MCA-LLaVA，将长期衰减扩展为二维、多方向的空间衰减。MCA-LLaVA 结合图像令牌的一维序列顺序和二维空间位置进行位置建模，通过缓解图像对齐偏差来减轻幻觉。实验结果表明，MCA-LLaVA 在各种幻觉和通用基准测试中均表现出色，证明了其有效性和通用性。代码可在 https://github.com/ErikZ719/MCA-LLaVA 获取。

> Hallucinations pose a significant challenge in Large Vision Language Models (LVLMs), with misalignment between multimodal features identified as a key contributing factor. This paper reveals the negative impact of the long-term decay in Rotary Position Encoding (RoPE), used for positional modeling in LVLMs, on multimodal alignment. Concretely, under long-term decay, instruction tokens exhibit uneven perception of image tokens located at different positions within the two-dimensional space: prioritizing image tokens from the bottom-right region since in the one-dimensional sequence, these tokens are positionally closer to the instruction tokens. This biased perception leads to insufficient image-instruction interaction and suboptimal multimodal alignment. We refer to this phenomenon as image alignment bias. To enhance instruction's perception of image tokens at different spatial locations, we propose MCA-LLaVA, based on Manhattan distance, which extends the long-term decay to a two-dimensional, multi-directional spatial decay. MCA-LLaVA integrates the one-dimensional sequence order and two-dimensional spatial position of image tokens for positional modeling, mitigating hallucinations by alleviating image alignment bias. Experimental results of MCA-LLaVA across various hallucination and general benchmarks demonstrate its effectiveness and generality. The code can be accessed in https://github.com/ErikZ719/MCA-LLaVA.

[Arxiv](https://arxiv.org/abs/2507.09184)