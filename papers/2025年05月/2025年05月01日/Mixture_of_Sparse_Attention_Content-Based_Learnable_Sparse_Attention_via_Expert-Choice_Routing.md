# 稀疏注意力机制的混合：基于内容的可学习稀疏注意力，通过专家选择路由实现

发布时间：2025年05月01日

`LLM理论

摘要讨论了大型语言模型中的自注意力机制，并提出了一种新的稀疏注意力方法（MoSA），以提高计算效率和模型性能。这属于对语言模型内部机制的理论研究和优化，因此归类为LLM理论。` `人工智能`

> Mixture of Sparse Attention: Content-Based Learnable Sparse Attention via Expert-Choice Routing

# 摘要

> 大型语言模型的最新进展突显出自注意力机制的过高二次成本。尽管投入了大量研究努力，次二次注意力方法在实践中仍然表现不佳。我们假设动态的、基于内容的稀疏性可以通过学习实现更高效的注意力机制。我们提出了稀疏注意力混合（MoSA），这是一种受专家混合（MoE）和专家选择路由启发的新方法。MoSA为每个注意力头动态选择token，允许任意稀疏注意力模式。通过从长度为T的序列中选择k个token，MoSA将每个注意力头的计算复杂度从O(T²)降低到O(k² + T)。这使得在相同的计算预算内可以使用更多注意力头，从而实现更高的专业化。我们发现，在所有测试的稀疏注意力变体中，只有MoSA能够超越密集基线，有时在相同的计算预算下，困惑度（perplexity）提升高达27%。与密集自注意力相比，MoSA还可以减少资源使用。尽管使用了未经优化内核的torch实现，但在与密集基线模型匹配困惑度的同时，MoSA模型在实际运行时间上更快，训练所需的内存更少，并且大幅减少了KV缓存的大小。

> Recent advances in large language models highlighted the excessive quadratic cost of self-attention. Despite the significant research efforts, subquadratic attention methods still suffer from inferior performance in practice. We hypothesize that dynamic, learned content-based sparsity can lead to more efficient attention mechanisms. We present Mixture of Sparse Attention (MoSA), a novel approach inspired by Mixture of Experts (MoE) with expert choice routing. MoSA dynamically selects tokens for each attention head, allowing arbitrary sparse attention patterns. By selecting $k$ tokens from a sequence of length $T$, MoSA reduces the computational complexity of each attention head from $O(T^2)$ to $O(k^2 + T)$. This enables using more heads within the same computational budget, allowing higher specialization. We show that among the tested sparse attention variants, MoSA is the only one that can outperform the dense baseline, sometimes with up to 27% better perplexity for an identical compute budget. MoSA can also reduce the resource usage compared to dense self-attention. Despite using torch implementation without an optimized kernel, perplexity-matched MoSA models are simultaneously faster in wall-clock time, require less memory for training, and drastically reduce the size of the KV-cache compared to the dense transformer baselines.

[Arxiv](https://arxiv.org/abs/2505.00315)