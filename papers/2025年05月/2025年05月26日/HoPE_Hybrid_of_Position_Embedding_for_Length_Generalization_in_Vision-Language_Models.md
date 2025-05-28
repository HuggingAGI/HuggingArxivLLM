# HoPE：视觉-语言模型中用于长度泛化的混合位置嵌入方法

发布时间：2025年05月26日

`LLM理论

理由：这篇论文主要探讨了视觉语言模型（VLMs）在处理长上下文场景时的性能问题，并提出了一种新的混合位置编码方法（HoPE），以提升模型的长上下文处理能力。研究深入分析了现有方法的不足，并提出了理论支持的新方法，属于模型理论的改进和优化，因此归类为LLM理论。` `计算机视觉` `视频处理`

> HoPE: Hybrid of Position Embedding for Length Generalization in Vision-Language Models

# 摘要

> 视觉语言模型（VLMs）在多模态任务中取得了重大突破，但其在处理长视频等长上下文场景时仍面临性能瓶颈。尽管旋转位置编码（RoPE）已被广泛应用于提升大型语言模型（LLMs）的长度泛化能力，但如何有效捕捉视频中的复杂时空依赖关系仍是待解决的难题。现有方法主要通过在RoPE中分配不同频率来编码三维位置信息，但这些策略多依赖启发式方法，缺乏理论支持。我们深入研究了不同分配策略对VLMs长上下文能力的影响，发现现有方法难以在长上下文中稳定捕捉语义相似性。为此，我们提出了一种混合位置编码方法——HoPE，旨在显著提升VLMs的长上下文处理能力。HoPE通过混合频率分配策略和动态时间缩放机制，在任意长度的上下文中实现了可靠的语义建模和灵活推理。在四个视频基准数据集上的大量实验表明，HoPE在长视频理解和检索任务中表现优异，证明了其有效性。代码已开源，地址为https://github.com/hrlics/HoPE。

> Vision-Language Models (VLMs) have made significant progress in multimodal tasks. However, their performance often deteriorates in long-context scenarios, particularly long videos. While Rotary Position Embedding (RoPE) has been widely adopted for length generalization in Large Language Models (LLMs), extending vanilla RoPE to capture the intricate spatial-temporal dependencies in videos remains an unsolved challenge. Existing methods typically allocate different frequencies within RoPE to encode 3D positional information. However, these allocation strategies mainly rely on heuristics, lacking in-depth theoretical analysis. In this paper, we first study how different allocation strategies impact the long-context capabilities of VLMs. Our analysis reveals that current multimodal RoPEs fail to reliably capture semantic similarities over extended contexts. To address this issue, we propose HoPE, a Hybrid of Position Embedding designed to improve the long-context capabilities of VLMs. HoPE introduces a hybrid frequency allocation strategy for reliable semantic modeling over arbitrarily long context, and a dynamic temporal scaling mechanism to facilitate robust learning and flexible inference across diverse context lengths. Extensive experiments across four video benchmarks on long video understanding and retrieval tasks demonstrate that HoPE consistently outperforms existing methods, confirming its effectiveness. Code is available at https://github.com/hrlics/HoPE.

[Arxiv](https://arxiv.org/abs/2505.20444)