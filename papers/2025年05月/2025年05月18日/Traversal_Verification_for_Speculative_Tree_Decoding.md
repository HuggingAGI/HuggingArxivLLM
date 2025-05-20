# 遍历验证在推测树解码中的应用

发布时间：2025年05月18日

`LLM应用` `大型语言模型`

> Traversal Verification for Speculative Tree Decoding

# 摘要

> Speculative Decoding 是加速大型语言模型的有力工具。其核心理念是借助轻量级草稿模型，提前预测目标模型在多个后续时间步的输出，并通过并行验证确定哪些草稿标记值得采纳。现有框架通常在每个时间步构建包含多个候选的标记树以提高接受率。然而，这种基于标记级别的验证机制存在两大局限：首先，序列的概率分布与单个标记不同，导致接受长度难以优化；其次，现有验证方案从根节点开始，以自顶向下方式逐层验证，一旦某父节点被拒绝，其所有子节点都将被舍弃，造成推测候选的浪费。本文提出了一种全新的 Traversal Verification 算法，通过从叶子到根的遍历重新定义验证范式。该方法不仅考虑从当前节点到根节点的整个标记序列的接受情况，还能保留现有方法会过早舍弃的潜在有效子序列。我们证明 Traversal Verification 获得的概率分布与目标模型完全一致，确保无损推理的同时实现显著加速。实验结果表明，该方法在不同大型语言模型和多个任务上均优于现有方法，显著提升了接受长度和吞吐量。

> Speculative decoding is a promising approach for accelerating large language models. The primary idea is to use a lightweight draft model to speculate the output of the target model for multiple subsequent timesteps, and then verify them in parallel to determine whether the drafted tokens should be accepted or rejected. To enhance acceptance rates, existing frameworks typically construct token trees containing multiple candidates in each timestep. However, their reliance on token-level verification mechanisms introduces two critical limitations: First, the probability distribution of a sequence differs from that of individual tokens, leading to suboptimal acceptance length. Second, current verification schemes begin from the root node and proceed layer by layer in a top-down manner. Once a parent node is rejected, all its child nodes should be discarded, resulting in inefficient utilization of speculative candidates. This paper introduces Traversal Verification, a novel speculative decoding algorithm that fundamentally rethinks the verification paradigm through leaf-to-root traversal. Our approach considers the acceptance of the entire token sequence from the current node to the root, and preserves potentially valid subsequences that would be prematurely discarded by existing methods. We theoretically prove that the probability distribution obtained through Traversal Verification is identical to that of the target model, guaranteeing lossless inference while achieving substantial acceleration gains. Experimental results across different large language models and multiple tasks show that our method consistently improves acceptance length and throughput over existing methods

[Arxiv](https://arxiv.org/abs/2505.12398)