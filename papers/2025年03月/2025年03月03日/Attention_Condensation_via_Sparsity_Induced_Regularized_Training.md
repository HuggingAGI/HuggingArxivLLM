# 稀疏性诱导正则化训练实现注意力浓缩

发布时间：2025年03月03日

`LLM理论` `人工智能`

> Attention Condensation via Sparsity Induced Regularized Training

# 摘要

> 上下文窗口的扩展使得自注意力机制在Transformer模型的推理时间中占据主导地位。因此，如何在尽量减少性能下降的前提下优化注意力计算，对于大型语言模型（LLMs）的高效部署至关重要。本研究扩展了对LLMs中注意力稀疏性的理论框架。我们设计了一个定制化的损失函数，通过限制注意力矩阵中顶部元素的数量来强制实现稀疏性。我们通过GPT-2进行了一系列初步评估，以展示我们稀疏化方法的有效性。采用我们提出的损失函数训练的模型，其注意力矩阵不仅稀疏，而且能够有效捕捉输入的相关依赖关系。目前，我们正在继续研究，以证明我们的方法在更大规模模型和不同架构中的价值。

> As the context window expands, self-attention increasingly dominates the transformer's inference time. Therefore, accelerating attention computation while minimizing performance degradation is essential for the efficient deployment of Large Language Models (LLMs). In this study we extend a theoretical framework of attention sparsity in LLMs. A customized loss function is designed to enforce the sparsity by restricting the number of top elements in the attention matrix. We perform an initial set of evaluations with GPT-2 to show the effectiveness of our sparsification approach. The attention matrices of the models trained with the proposed loss are both sparse and effective in capturing relevant input dependencies. We now continue working to demonstrate the value of our approach on larger models and different architectures.

[Arxiv](https://arxiv.org/abs/2503.01564)