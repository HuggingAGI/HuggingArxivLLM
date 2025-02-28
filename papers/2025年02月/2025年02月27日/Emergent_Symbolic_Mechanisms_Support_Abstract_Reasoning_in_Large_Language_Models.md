# 涌现的符号机制助力大型语言模型实现抽象推理

发布时间：2025年02月27日

`LLM理论` `人工智能` `认知科学`

> Emergent Symbolic Mechanisms Support Abstract Reasoning in Large Language Models

# 摘要

> 近期研究表明，大型语言模型具备推理能力，但关于这些能力的稳健性及其对结构化推理机制的依赖程度仍存争议。为探讨这些问题，我们深入研究了开源语言模型（Llama3-70B）中支持抽象规则归纳的内部机制，发现了一种新兴的符号架构。该架构通过三步计算实现抽象推理：早期层的符号抽象头将输入标记转换为抽象变量；中间层的符号归纳头对这些变量进行序列归纳；后期层的检索头通过检索与预测变量相关联的值预测下一个标记。这些发现为符号方法与神经网络方法的长期争论提供了新视角，表明神经网络中的推理能力依赖于符号机制的涌现。

> Many recent studies have found evidence for emergent reasoning capabilities in large language models, but debate persists concerning the robustness of these capabilities, and the extent to which they depend on structured reasoning mechanisms. To shed light on these issues, we perform a comprehensive study of the internal mechanisms that support abstract rule induction in an open-source language model (Llama3-70B). We identify an emergent symbolic architecture that implements abstract reasoning via a series of three computations. In early layers, symbol abstraction heads convert input tokens to abstract variables based on the relations between those tokens. In intermediate layers, symbolic induction heads perform sequence induction over these abstract variables. Finally, in later layers, retrieval heads predict the next token by retrieving the value associated with the predicted abstract variable. These results point toward a resolution of the longstanding debate between symbolic and neural network approaches, suggesting that emergent reasoning in neural networks depends on the emergence of symbolic mechanisms.

[Arxiv](https://arxiv.org/abs/2502.20332)