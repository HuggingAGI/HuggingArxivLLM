# 基于低秩适应的上下文引导Transformer模型

发布时间：2025年06月05日

`LLM理论` `上下文处理`

> Contextually Guided Transformers via Low-Rank Adaptation

# 摘要

> 基于Transformer的大型语言模型（LLMs）在文本处理方面表现出色，但依赖显式提示实现特定行为会带来计算开销。我们提出了一种改进的Transformer架构，通过学习将上下文编码到模型权重中，从而消除对显式提示的需求。我们的上下文引导变换器（CGT）模型在每个序列位置维护一个上下文摘要，使其能够根据之前上下文实时更新权重。这一方法使模型能够自我专业化，有效创建一个针对给定前缀信息处理的定制模型。我们在合成的上下文学习任务和语言建模基准测试中展示了方法的有效性。此外，我们引入了增强学习上下文表示可解释性的技术，将其与变分自编码器联系起来，促进了更平滑一致的上下文编码。这项工作通过将上下文直接整合到模型架构中，为高效且适应性强的语言建模提供了一个新颖的方向。

> Large Language Models (LLMs) based on Transformers excel at text processing, but their reliance on prompts for specialized behavior introduces computational overhead. We propose a modification to a Transformer architecture that eliminates the need for explicit prompts by learning to encode context into the model's weights. Our Contextually Guided Transformer (CGT) model maintains a contextual summary at each sequence position, allowing it to update the weights on the fly based on the preceding context. This approach enables the model to self-specialize, effectively creating a tailored model for processing information following a given prefix. We demonstrate the effectiveness of our method on synthetic in-context learning tasks and language modeling benchmarks. Furthermore, we introduce techniques for enhancing the interpretability of the learned contextual representations, drawing connections to Variational Autoencoders and promoting smoother, more consistent context encoding. This work offers a novel direction for efficient and adaptable language modeling by integrating context directly into the model's architecture.

[Arxiv](https://arxiv.org/abs/2506.05672)