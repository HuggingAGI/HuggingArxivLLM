# # 超越演示：从潜在表示构建动态向量
本研究提出了一种创新方法，通过从潜在表示中动态构建向量，超越了传统的演示方法。

发布时间：2025年05月23日

`LLM应用`

> Beyond Demonstrations: Dynamic Vector Construction from Latent Representations

# 摘要

> 上下文衍生向量（ICV）方法从大型语言模型（LLMs）中提取与任务相关的表示，并在推理过程中重新注入这些表示，从而无需重复演示处理，即可实现与少样本上下文学习（ICL）相当的效果。然而，现有的ICV方法仍然对上下文学习特有的因素敏感，通常使用粗略或语义碎片化的表示作为向量来源，并依赖基于启发式的注入位置，这限制了它们的应用范围。

为了解决这些问题，我们提出了动态向量（DyVec），该方法采用全面查询旋转（EQR）策略，通过缓解上下文学习引入的方差，提取出稳健的语义聚合潜在表示。随后，它利用动态潜在分割与注入技术，根据任务复杂度自适应地划分表示，并借助基于REINFORCE的优化方法，为每个段落学习最优的注入位置。

实验结果表明，DyVec在性能上超越了少样本上下文学习、LoRA以及先前的ICV基线方法。进一步的分析突显了动态分割和注入语义聚合潜在表示的有效性。DyVec为推理时的任务适应提供了一种轻量级且数据高效的解决方案。


> In-Context derived Vector (ICV) methods extract task-relevant representations from large language models (LLMs) and reinject them during inference, achieving comparable performance to few-shot In-Context Learning (ICL) without repeated demonstration processing. However, existing ICV methods remain sensitive to ICL-specific factors, often use coarse or semantically fragmented representations as the source of the vector, and rely on heuristic-based injection positions, limiting their applicability.
  To address these issues, we propose Dynamic Vector (DyVec), which incorporates an Exhaustive Query Rotation (EQR) strategy to extract robust semantically aggregated latent representations by mitigating variance introduced by ICL. It then applies Dynamic Latent Segmentation and Injection to adaptively partition representations based on task complexity and leverages REINFORCE-based optimization to learn optimal injection positions for each segment.
  Experiments results show that DyVec outperforms few-shot ICL, LoRA, and prior ICV baselines. Further analysis highlights the effectiveness of dynamically segmenting and injecting semantically aggregated latent representations. DyVec provides a lightweight and data-efficient solution for inference-time task adaptation.

[Arxiv](https://arxiv.org/abs/2505.20318)