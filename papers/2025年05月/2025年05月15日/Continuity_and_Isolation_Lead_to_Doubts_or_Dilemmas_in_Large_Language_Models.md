# 连续性与孤立性问题引发大型语言模型中的疑惑与两难困境

发布时间：2025年05月15日

`LLM理论` `机器学习`

> Continuity and Isolation Lead to Doubts or Dilemmas in Large Language Models

# 摘要

> 理解 Transformer 的工作原理及其信息处理机制，是推动这些模型理论与实践发展的关键。本研究揭示了 Transformer 中的两个重要现象：隔离与连续性。这两个现象共同阻碍了 Transformer 对简单模式序列的学习能力。其中，隔离现象表明，任何可学习的序列都需与其他可学习序列保持独立，导致单个 Transformer 无法同时掌握所有序列。而连续性现象则意味着，学习到的序列周围会形成一个吸引子 basin，使落入其中的任何序列都趋向于该已学习序列。通过数学证明，我们发现这些现象普遍存在于所有采用紧致位置编码的 Transformer 中，并通过严格实验验证了这些理论限制在实际应用中的存在性。

> Understanding how Transformers work and how they process information is key to the theoretical and empirical advancement of these machines. In this work, we demonstrate the existence of two phenomena in Transformers, namely isolation and continuity. Both of these phenomena hinder Transformers to learn even simple pattern sequences. Isolation expresses that any learnable sequence must be isolated from another learnable sequence, and hence some sequences cannot be learned by a single Transformer at the same time. Continuity entails that an attractor basin forms around a learned sequence, such that any sequence falling in that basin will collapse towards the learned sequence. Here, we mathematically prove these phenomena emerge in all Transformers that use compact positional encoding, and design rigorous experiments, demonstrating that the theoretical limitations we shed light on occur on the practical scale.

[Arxiv](https://arxiv.org/abs/2505.10606)