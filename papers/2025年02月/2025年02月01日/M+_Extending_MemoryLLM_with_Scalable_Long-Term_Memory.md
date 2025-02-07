# M+: 为 MemoryLLM 扩展可扩展的长期记忆

发布时间：2025年02月01日

`LLM理论

理由：这篇论文主要讨论了如何通过改进大型语言模型（LLMs）的记忆机制来提升其长期信息保留能力。具体来说，它提出了一种新的记忆增强模型M+，该模型结合了长期记忆机制和检索器，以动态检索相关信息。这种研究属于对LLM内部机制和理论框架的改进，因此应归类为LLM理论。` `人工智能`

> M+: Extending MemoryLLM with Scalable Long-Term Memory

# 摘要

> 为大型语言模型（LLMs）配备潜在空间记忆已成为研究热点，因其能扩展现有模型的上下文窗口。然而，如何保留遥远过去的信息仍是一大挑战。以MemoryLLM（Wang et al., 2024a）为例，它通过将过去信息压缩到所有层的隐藏状态中，构建了一个10亿参数的内存池。虽然对16k标记以内的序列效果显著，但在超过20k标记时，知识保留能力明显下降。为此，我们提出了M+，一种基于MemoryLLM的记忆增强模型，显著提升了长期信息保留能力。M+结合了长期记忆机制和共同训练的检索器，能在文本生成时动态检索相关信息。我们在多个基准上测试了M+，包括长上下文理解和知识保留任务。实验结果显示，M+在保持相似GPU内存开销的同时，将知识保留能力从不到20k标记提升至超过160k标记，显著优于MemoryLLM及其他强基线。

> Equipping large language models (LLMs) with latent-space memory has attracted increasing attention as they can extend the context window of existing language models. However, retaining information from the distant past remains a challenge. For example, MemoryLLM (Wang et al., 2024a), as a representative work with latent-space memory, compresses past information into hidden states across all layers, forming a memory pool of 1B parameters. While effective for sequence lengths up to 16k tokens, it struggles to retain knowledge beyond 20k tokens. In this work, we address this limitation by introducing M+, a memory-augmented model based on MemoryLLM that significantly enhances long-term information retention. M+ integrates a long-term memory mechanism with a co-trained retriever, dynamically retrieving relevant information during text generation. We evaluate M+ on diverse benchmarks, including long-context understanding and knowledge retention tasks. Experimental results show that M+ significantly outperforms MemoryLLM and recent strong baselines, extending knowledge retention from under 20k to over 160k tokens with similar GPU memory overhead.

[Arxiv](https://arxiv.org/abs/2502.00592)