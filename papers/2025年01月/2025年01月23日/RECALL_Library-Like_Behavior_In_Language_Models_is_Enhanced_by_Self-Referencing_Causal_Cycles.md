# RECALL: 自引用因果循环增强了语言模型中的类库行为

发布时间：2025年01月23日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在处理顺序数据时的局限性，特别是“逆转诅咒”现象，并提出了自引用因果循环（RECALL）的概念来解决这一问题。论文通过严格的概率形式化和控制实验，深入分析了循环标记如何影响模型再现信息的能力。这些内容属于对LLM内部机制和理论的研究，因此归类为“LLM理论”。` `人工智能`

> RECALL: Library-Like Behavior In Language Models is Enhanced by Self-Referencing Causal Cycles

# 摘要

> 我们提出了自引用因果循环（RECALL）的概念，这是一种让大型语言模型（LLMs）突破单向因果性限制的机制，这种限制正是“逆转诅咒”现象的根源。当LLM处理顺序数据时，往往难以回忆起前面的上下文。例如，当我们要求LLM回忆美国国歌中“O say does that star-spangled banner yet wave”之前的那一行时，它常常无法正确返回“Gave proof through the night that our flag was still there”——这就是逆转诅咒的表现。这种现象源于像ChatGPT和Llama这样的语言模型是基于前面的标记生成文本的，要求事实以一致的标记顺序学习和再现。尽管逆转诅咒常被视为一种限制，但我们提供了另一种视角：它在实践中并非总是障碍。我们发现，RECALL是由循环标记驱动的——这些标记序列连接了训练数据的不同部分，使得模型能够从后续标记中回忆起前面的标记。通过严格的概率形式化和控制实验，我们展示了这些循环如何影响模型再现信息的能力。为了便于复现，我们在https://anonymous.4open.science/r/remember-B0B8/提供了代码和实验细节。

> We introduce the concept of the self-referencing causal cycle (abbreviated RECALL) - a mechanism that enables large language models (LLMs) to bypass the limitations of unidirectional causality, which underlies a phenomenon known as the reversal curse. When an LLM is prompted with sequential data, it often fails to recall preceding context. For example, when we ask an LLM to recall the line preceding "O say does that star-spangled banner yet wave" in the U.S. National Anthem, it often fails to correctly return "Gave proof through the night that our flag was still there" - this is due to the reversal curse. It occurs because language models such as ChatGPT and Llama generate text based on preceding tokens, requiring facts to be learned and reproduced in a consistent token order. While the reversal curse is often viewed as a limitation, we offer evidence of an alternative view: it is not always an obstacle in practice. We find that RECALL is driven by what we designate as cycle tokens - sequences that connect different parts of the training data, enabling recall of preceding tokens from succeeding ones. Through rigorous probabilistic formalization and controlled experiments, we demonstrate how the cycles they induce influence a model's ability to reproduce information. To facilitate reproducibility, we provide our code and experimental details at https://anonymous.4open.science/r/remember-B0B8/.

[Arxiv](https://arxiv.org/abs/2501.13491)