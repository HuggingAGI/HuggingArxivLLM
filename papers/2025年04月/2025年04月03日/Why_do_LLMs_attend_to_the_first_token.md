# 为什么大型语言模型总是关注第一个标记？

发布时间：2025年04月03日

`LLM理论` `机器学习`

> Why do LLMs attend to the first token?

# 摘要

> 大型语言模型（LLMs）往往过度关注序列中的第一个标记，形成了所谓的“注意力陷阱”。许多研究对此现象进行了深入探讨，提出了多种利用或缓解的方法。注意力陷阱与量化困难、安全问题和流式注意力相关。然而，尽管许多研究提供了它们出现或不出现的条件，但一个关键问题仍未得到充分解答：为什么LLMs会学习这样的模式，以及它们是如何被利用的？

在本研究中，我们从理论和实证两个角度论证，这种机制为LLMs提供了一种避免过度混合的方法，并将其与现有研究联系起来，这些研究从数学上探讨了信息在Transformer中的传播方式。我们进行了实验来验证我们的理论直觉，并展示了上下文长度、深度和数据打包等因素如何影响注意力陷阱的行为。我们希望这项研究为理解为什么注意力陷阱在LLMs中是有用的提供了新的实践视角，从而更好地理解训练过程中形成的注意力模式。

> Large Language Models (LLMs) tend to attend heavily to the first token in the sequence -- creating a so-called attention sink. Many works have studied this phenomenon in detail, proposing various ways to either leverage or alleviate it. Attention sinks have been connected to quantisation difficulties, security issues, and streaming attention. Yet, while many works have provided conditions in which they occur or not, a critical question remains shallowly answered: Why do LLMs learn such patterns and how are they being used? In this work, we argue theoretically and empirically that this mechanism provides a method for LLMs to avoid over-mixing, connecting this to existing lines of work that study mathematically how information propagates in Transformers. We conduct experiments to validate our theoretical intuitions and show how choices such as context length, depth, and data packing influence the sink behaviour. We hope that this study provides a new practical perspective on why attention sinks are useful in LLMs, leading to a better understanding of the attention patterns that form during training.

[Arxiv](https://arxiv.org/abs/2504.02732)