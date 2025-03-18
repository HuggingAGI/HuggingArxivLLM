# # 深入解析大型语言模型位置泛化的计算机制

发布时间：2025年03月17日

`LLM理论

论文摘要：大多数书面自然语言由单词和句子的序列构成。与人类类似，大型语言模型（LLMs）在处理文本位置时展现出灵活性，我们称其为位置泛化。它们不仅能够理解包含位置扰动的文本，还能通过最新技术处理比训练时更长的文本。这些现象表明，LLMs对位置信息的处理具有较高的容忍度，但关于LLMs如何在计算上处理位置相关性的问题，仍然 largely unexplored. 本研究将这一语言现象与LLMs的计算机制相结合。我们展示了LLMs如何通过特定的计算机制实现对位置扰动的容忍。尽管自注意力机制的设计复杂，但本研究揭示了LLMs学习到一种反直觉的注意力logits解耦方式。其值与位置相关性和语义重要性的算术和近似值之间呈现0.959的线性相关性。此外，我们在中间特征中发现了一种普遍模式，并通过理论证明了这种模式如何实现上述效果。这种模式与随机初始化参数的行为不同，表明它是一种通过学习获得的行为，而非模型架构的自然结果。基于这些发现，我们为LLMs的位置灵活性提供了计算解释和标准。本研究在将位置泛化与现代LLMs的内部机制联系方面迈出了开创性的一步。

LLM理论` `人工智能`

> Computation Mechanism Behind LLM Position Generalization

# 摘要

> 大多数书面自然语言由单词和句子的序列构成。与人类类似，大型语言模型（LLMs）在处理文本位置时展现出灵活性，我们称其为位置泛化。它们不仅能够理解包含位置扰动的文本，还能通过最新技术处理比训练时更长的文本。这些现象表明，LLMs对位置信息的处理具有较高的容忍度，但关于LLMs如何在计算上处理位置相关性的问题，仍然 largely unexplored. 本研究将这一语言现象与LLMs的计算机制相结合。我们展示了LLMs如何通过特定的计算机制实现对位置扰动的容忍。尽管自注意力机制的设计复杂，但本研究揭示了LLMs学习到一种反直觉的注意力logits解耦方式。其值与位置相关性和语义重要性的算术和近似值之间呈现0.959的线性相关性。此外，我们在中间特征中发现了一种普遍模式，并通过理论证明了这种模式如何实现上述效果。这种模式与随机初始化参数的行为不同，表明它是一种通过学习获得的行为，而非模型架构的自然结果。基于这些发现，我们为LLMs的位置灵活性提供了计算解释和标准。本研究在将位置泛化与现代LLMs的内部机制联系方面迈出了开创性的一步。

> Most written natural languages are composed of sequences of words and sentences. Similar to humans, large language models (LLMs) exhibit flexibility in handling textual positions - a phenomenon we term position generalization. They can understand texts with position perturbations and generalize to longer texts than those encountered during training with the latest techniques. These phenomena suggest that LLMs handle positions tolerantly, but how LLMs computationally process positional relevance remains largely unexplored. This work connects the linguistic phenomenon with LLMs' computational mechanisms. We show how LLMs enforce certain computational mechanisms for the aforementioned tolerance in position perturbations. Despite the complex design of the self-attention mechanism, this work reveals that LLMs learn a counterintuitive disentanglement of attention logits. Their values show a 0.959 linear correlation with an approximation of the arithmetic sum of positional relevance and semantic importance. Furthermore, we identify a prevalent pattern in intermediate features, which we prove theoretically enables this effect. The pattern, which is different from how randomly initialized parameters would behave, suggests that it is a learned behavior rather than a natural result of the model architecture. Based on these findings, we provide computational explanations and criteria for LLMs' position flexibilities. This work takes a pioneering step in linking position generalization with modern LLMs' internal mechanisms.

[Arxiv](https://arxiv.org/abs/2503.13305)