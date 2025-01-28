# 大型语言模型的相变与$O(N)$模型

发布时间：2025年01月27日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）中的相变现象，并将其与物理学中的相变、临界现象和场论联系起来。研究通过将Transformer架构重新表述为$O(N)$模型，发现了与文本生成中的温度和模型参数规模相关的两个不同的相变。这些发现属于对LLMs的理论研究，旨在深入理解LLMs的内部机制和行为，因此应归类为“LLM理论”。` `物理学` `机器学习`

> Phase Transitions in Large Language Models and the $O(N)$ Model

# 摘要

> 大型语言模型（LLMs）展现出前所未有的扩展行为。在物理学中，扩展行为与相变、临界现象和场论紧密相关。为了探索LLMs中的相变现象，我们将Transformer架构重新表述为$O(N)$模型。研究发现，存在两个不同的相变，分别与文本生成中的温度和模型参数规模相关。第一个相变帮助我们估算模型的内部维度，而第二个相变则属于	extit{更高深度}，预示着新能力的涌现。作为应用，$O(N)$模型的能量可用于评估LLM的参数是否足以学习训练数据。

> Large language models (LLMs) exhibit unprecedentedly rich scaling behaviors. In physics, scaling behavior is closely related to phase transitions, critical phenomena, and field theory. To investigate the phase transition phenomena in LLMs, we reformulated the Transformer architecture as an $O(N)$ model. Our study reveals two distinct phase transitions corresponding to the temperature used in text generation and the model's parameter size, respectively. The first phase transition enables us to estimate the internal dimension of the model, while the second phase transition is of \textit{higher-depth} and signals the emergence of new capabilities. As an application, the energy of the $O(N)$ model can be used to evaluate whether an LLM's parameters are sufficient to learn the training data.

[Arxiv](https://arxiv.org/abs/2501.16241)