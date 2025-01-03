# 早期退出LLMs中的动态词汇剪枝

发布时间：2024年10月24日

`LLM理论

理由：这篇论文主要讨论了如何通过动态词汇修剪和早期退出策略来提升大型语言模型（LLM）的推理效率，同时保持性能。这涉及到对LLM内部机制和推理过程的优化，属于对LLM理论的研究和改进，因此应归类为LLM理论。` `机器学习`

> Dynamic Vocabulary Pruning in Early-Exit LLMs

# 摘要

> 扩大LLMs的规模能提升性能，但也会导致推理速度变慢、成本增加。早期退出通过在中间层预测下一个令牌，有望提升LLM推理效率。然而，现代LLMs庞大的词汇量使得退出决策所需的置信度估计计算成本高昂，削弱了效率提升。为此，我们提出在测试时动态修剪每个令牌的词汇表：在初始层修剪词汇表，并在后续推理中使用较小的词汇表。实验表明，这种动态词汇修剪在保持性能的同时，显著提升了早期退出LLMs的置信度估计效率。

> Increasing the size of large language models (LLMs) has been shown to lead to better performance. However, this comes at the cost of slower and more expensive inference. Early-exiting is a promising approach for improving the efficiency of LLM inference by enabling next token prediction at intermediate layers. Yet, the large vocabulary size in modern LLMs makes the confidence estimation required for exit decisions computationally expensive, diminishing the efficiency gains. To address this, we propose dynamically pruning the vocabulary at test time for each token. Specifically, the vocabulary is pruned at one of the initial layers, and the smaller vocabulary is then used throughout the rest of the forward pass. Our experiments demonstrate that such post-hoc dynamic vocabulary pruning improves the efficiency of confidence estimation in early-exit LLMs while maintaining competitive performance.

[Arxiv](https://arxiv.org/abs/2410.18952)