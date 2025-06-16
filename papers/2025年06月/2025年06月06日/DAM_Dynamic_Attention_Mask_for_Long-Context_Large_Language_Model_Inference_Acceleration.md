# DAM：用于长上下文大型语言模型推理加速的动态注意力掩码

发布时间：2025年06月06日

`LLM理论

这篇论文主要探讨了如何改进大型语言模型（LLMs）中的注意力机制，以更高效地处理长序列数据。研究提出了动态稀疏注意力机制，优化了模型的计算效率和性能，属于模型理论和结构改进的范畴。` `问答系统`

> DAM: Dynamic Attention Mask for Long-Context Large Language Model Inference Acceleration

# 摘要

> 长上下文理解对许多NLP应用至关重要，然而transformers在处理长序列时效率低下。稀疏注意力方法虽然缓解了这一问题，但通常采用静态预定义掩码，无法捕捉异质注意力模式。这导致了次优的token交互，限制了长序列任务的适应性和检索准确性。本研究提出了一种动态稀疏注意力机制，在注意力图层面自适应分配掩码，跨层跨头保留异质模式。与现有方法不同，我们的方法无需微调或预定义掩码结构，同时保持计算效率。通过学习上下文感知的注意力结构，它与全注意力模型高度对齐，确保性能下降最小化的同时降低内存和计算开销。这种方法为全注意力提供了一种可扩展的替代方案，使大规模大型语言模型（LLMs）的实际部署成为可能，而不会牺牲检索性能。DAM可在以下链接获取：https://github.com/HanzhiZhang-Ulrica/DAM。


> Long-context understanding is crucial for many NLP applications, yet transformers struggle with efficiency due to the quadratic complexity of self-attention. Sparse attention methods alleviate this cost but often impose static, predefined masks, failing to capture heterogeneous attention patterns. This results in suboptimal token interactions, limiting adaptability and retrieval accuracy in long-sequence tasks. This work introduces a dynamic sparse attention mechanism that assigns adaptive masks at the attention-map level, preserving heterogeneous patterns across layers and heads. Unlike existing approaches, our method eliminates the need for fine-tuning and predefined mask structures while maintaining computational efficiency. By learning context-aware attention structures, it achieves high alignment with full-attention models, ensuring minimal performance degradation while reducing memory and compute overhead. This approach provides a scalable alternative to full attention, enabling the practical deployment of large-scale Large Language Models (LLMs) without sacrificing retrieval performance. DAM is available at: https://github.com/HanzhiZhang-Ulrica/DAM.

[Arxiv](https://arxiv.org/abs/2506.11104)