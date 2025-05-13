# # 门控注意力机制在大型语言模型中的研究：非线性、稀疏性与无注意力陷阱

发布时间：2025年05月10日

`LLM理论`

> Gated Attention for Large Language Models: Non-linearity, Sparsity, and Attention-Sink-Free

# 摘要

> 门控机制在从早期的LSTM和Highway Networks到近期的状态空间模型、线性注意力机制以及softmax注意力机制中被广泛应用。然而，现有文献对其具体效果的研究较少。本研究通过全面实验，系统性地考察了增强型softmax注意力机制的变体。我们对基于3.5万亿标记数据集训练的150亿参数量的专家混合模型（MoE）和17亿参数量的密集模型的30种变体进行了全面比较。研究发现，一个简单的修改——在缩放点积注意力（SDPA）后应用特定于头部的sigmoid门控——显著提升了模型性能。这一修改不仅增强了训练稳定性，还使模型能够容忍更大的学习率并改善扩展特性。通过比较不同门控位置和计算变体，我们发现其有效性主要源于两点：(1) 在softmax注意力的低秩映射中引入非线性，以及(2) 通过依赖于查询的稀疏门控分数来调节SDPA的输出。值得注意的是，这种稀疏门控机制能够有效缓解“注意力陷阱”问题，并显著提升长上下文外推性能。此外，我们还发布了相关的$\href{https://github.com/qiuzh20/gated_attention}{代码}$和$\href{https://huggingface.co/QwQZh/gated_attention}{模型}$，以支持未来研究。

> Gating mechanisms have been widely utilized, from early models like LSTMs and Highway Networks to recent state space models, linear attention, and also softmax attention. Yet, existing literature rarely examines the specific effects of gating. In this work, we conduct comprehensive experiments to systematically investigate gating-augmented softmax attention variants. Specifically, we perform a comprehensive comparison over 30 variants of 15B Mixture-of-Experts (MoE) models and 1.7B dense models trained on a 3.5 trillion token dataset. Our central finding is that a simple modification-applying a head-specific sigmoid gate after the Scaled Dot-Product Attention (SDPA)-consistently improves performance. This modification also enhances training stability, tolerates larger learning rates, and improves scaling properties. By comparing various gating positions and computational variants, we attribute this effectiveness to two key factors: (1) introducing non-linearity upon the low-rank mapping in the softmax attention, and (2) applying query-dependent sparse gating scores to modulate the SDPA output. Notably, we find this sparse gating mechanism mitigates 'attention sink' and enhances long-context extrapolation performance, and we also release related $\href{https://github.com/qiuzh20/gated_attention}{codes}$ and $\href{https://huggingface.co/QwQZh/gated_attention}{models}$ to facilitate future research.

[Arxiv](https://arxiv.org/abs/2505.06708)