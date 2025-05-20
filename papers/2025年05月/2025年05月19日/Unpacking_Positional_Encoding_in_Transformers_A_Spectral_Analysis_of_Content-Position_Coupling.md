# 深入解析 Transformer 位置编码：从频谱视角看内容与位置的耦合关系

发布时间：2025年05月19日

`LLM理论` `位置编码`

> Unpacking Positional Encoding in Transformers: A Spectral Analysis of Content-Position Coupling

# 摘要

> 位置编码（PE）是Transformer建模序列结构的关键。然而，不同PE方案如何结合token内容与位置信息，以及这些机制如何影响模型动态，仍待深入研究。本研究提出了一种统一框架，通过分析注意力logits所推导的Toeplitz矩阵及其相关矩阵的频谱属性来研究PE。我们发现，乘法内容-位置耦合——例如通过与Toeplitz矩阵进行Hadamard积实现的旋转位置编码（RoPE）——会引发频谱收缩，从而提高优化稳定性和效率。基于此理论，我们构建了对比内容-位置相关和内容-位置无关设置的合成任务，并评估了多种PE方法。实验结果与理论高度一致：RoPE在位置敏感任务中表现最佳，并在早期层中引发“单头沉积”模式，表明局部位置处理。进一步分析表明，修改PE结合方式（如Deepseek-V3中的MLA）可以有效缓解这种集中。这些结果将明确的内容相关混合与相对位置Toeplitz信号确立为有效PE设计的关键原则，并为Transformer架构中位置结构的整合提供了新见解。


> Positional encoding (PE) is essential for enabling Transformers to model sequential structure. However, the mechanisms by which different PE schemes couple token content and positional information-and how these mechanisms influence model dynamics-remain theoretically underexplored. In this work, we present a unified framework that analyzes PE through the spectral properties of Toeplitz and related matrices derived from attention logits. We show that multiplicative content-position coupling-exemplified by Rotary Positional Encoding (RoPE) via a Hadamard product with a Toeplitz matrix-induces spectral contraction, which theoretically improves optimization stability and efficiency. Guided by this theory, we construct synthetic tasks that contrast content-position dependent and content-position independent settings, and evaluate a range of PE methods. Our experiments reveal strong alignment with theory: RoPE consistently outperforms other methods on position-sensitive tasks and induces "single-head deposit" patterns in early layers, indicating localized positional processing. Further analyses show that modifying the method and timing of PE coupling, such as MLA in Deepseek-V3, can effectively mitigate this concentration. These results establish explicit content-relative mixing with relative-position Toeplitz signals as a key principle for effective PE design and provide new insight into how positional structure is integrated in Transformer architectures.

[Arxiv](https://arxiv.org/abs/2505.13027)