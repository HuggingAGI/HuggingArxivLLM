# 遍历验证在推测性树解码中的应用

发布时间：2025年05月18日

`LLM应用` `大型语言模型`

> Traversal Verification for Speculative Tree Decoding

# 摘要

> Speculative decoding 是加速大型语言模型的有力工具。其核心思想是借助轻量级草稿模型，对多个后续时间步长的输出进行预测，随后并行验证这些预测结果，以决定哪些标记应被保留或舍弃。为了提升接受率，现有框架通常在每个时间步长构建包含多个候选的标记树。然而，基于标记级别的验证机制存在两大关键限制：首先，序列的概率分布与单个标记不同，导致接受长度次优；其次，现有的验证方案从根节点开始，采用自顶向下的分层方式推进，一旦某个父节点被拒绝，其所有子节点都将被丢弃，导致推测候选的利用效率低下。本文提出了一种全新的 Traversal Verification 算法，通过叶到根的遍历从根本上重新定义了验证范式。我们的方法从当前节点到根节点考虑整个标记序列的接受情况，并保留了现有方法会过早丢弃的潜在有效子序列。我们从理论上证明，通过 Traversal Verification 获得的概率分布与目标模型完全一致，既保证了无损推理，又实现了显著的加速效果。在不同大型语言模型和多个任务上的实验结果表明，与现有方法相比，我们的方法在改善接受长度和吞吐量方面表现优异。

> Speculative decoding is a promising approach for accelerating large language models. The primary idea is to use a lightweight draft model to speculate the output of the target model for multiple subsequent timesteps, and then verify them in parallel to determine whether the drafted tokens should be accepted or rejected. To enhance acceptance rates, existing frameworks typically construct token trees containing multiple candidates in each timestep. However, their reliance on token-level verification mechanisms introduces two critical limitations: First, the probability distribution of a sequence differs from that of individual tokens, leading to suboptimal acceptance length. Second, current verification schemes begin from the root node and proceed layer by layer in a top-down manner. Once a parent node is rejected, all its child nodes should be discarded, resulting in inefficient utilization of speculative candidates. This paper introduces Traversal Verification, a novel speculative decoding algorithm that fundamentally rethinks the verification paradigm through leaf-to-root traversal. Our approach considers the acceptance of the entire token sequence from the current node to the root, and preserves potentially valid subsequences that would be prematurely discarded by existing methods. We theoretically prove that the probability distribution obtained through Traversal Verification is identical to that of the target model, guaranteeing lossless inference while achieving substantial acceleration gains. Experimental results across different large language models and multiple tasks show that our method consistently improves acceptance length and throughput over existing methods

[Arxiv](https://arxiv.org/abs/2505.12398)