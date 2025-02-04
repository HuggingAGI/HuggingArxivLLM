# 高效推理与隐性思维

发布时间：2025年01月31日

`LLM应用

理由：这篇论文主要讨论了一种新的推理框架（Heima），旨在提高多模态大型语言模型（MLLMs）的推理效率。该框架通过压缩中间推理步骤（Chain-of-Thought, CoT）来减少冗长性，并提升生成效率。虽然涉及到了推理过程的优化，但其核心仍然是针对大型语言模型的应用场景，特别是如何在实际应用中提高模型的效率和性能。因此，这篇论文应归类为LLM应用。` `多模态学习`

> Efficient Reasoning with Hidden Thinking

# 摘要

> # 摘要
Chain-of-Thought (CoT) 推理框架显著提升了多模态大型语言模型（MLLMs）的复杂问题解决能力，但其文本推理的冗长性导致效率低下。为此，我们提出了 $	extbf{Heima}$（隐藏的 llama），一种高效的推理框架，利用隐藏潜在空间中的 CoTs 进行推理。Heima 编码器通过单个思考标记将中间 CoT 压缩为紧凑的高级隐藏表示，大幅减少了推理过程中的冗长性和标记数量。同时，我们设计了与传统 LLMs 兼容的 Heima 解码器，自适应地将隐藏表示转化为可变长度的文本序列，重建与原始 CoTs 高度一致的推理过程。实验表明，Heima 模型在保持甚至提升零-shot 任务准确性的同时，显著提高了生成效率。此外，Heima 解码器成功重建多模态推理过程，验证了方法的鲁棒性和可解释性。

> Chain-of-Thought (CoT) reasoning has become a powerful framework for improving complex problem-solving capabilities in Multimodal Large Language Models (MLLMs). However, the verbose nature of textual reasoning introduces significant inefficiencies. In this work, we propose $\textbf{Heima}$ (as hidden llama), an efficient reasoning framework that leverages reasoning CoTs at hidden latent space. We design the Heima Encoder to condense each intermediate CoT into a compact, higher-level hidden representation using a single thinking token, effectively minimizing verbosity and reducing the overall number of tokens required during the reasoning process. Meanwhile, we design corresponding Heima Decoder with traditional Large Language Models (LLMs) to adaptively interpret the hidden representations into variable-length textual sequence, reconstructing reasoning processes that closely resemble the original CoTs. Experimental results across diverse reasoning MLLM benchmarks demonstrate that Heima model achieves higher generation efficiency while maintaining or even better zero-shot task accuracy. Moreover, the effective reconstruction of multimodal reasoning processes with Heima Decoder validates both the robustness and interpretability of our approach.

[Arxiv](https://arxiv.org/abs/2501.19201)