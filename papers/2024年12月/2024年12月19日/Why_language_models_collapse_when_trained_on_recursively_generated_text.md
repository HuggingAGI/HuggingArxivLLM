# 为何语言模型在以递归生成的文本训练时会崩溃

发布时间：2024年12月19日

`LLM理论` `互联网`

> Why language models collapse when trained on recursively generated text

# 摘要

> 语言模型（LMs）在互联网上已被广泛用于生成文本，所生成的文本常被纳入下一代 LMs 的训练语料库。先前的研究通过实验发现，在递归生成的文本上训练时，LMs 会崩溃。本文从两方面丰富了现有认知。我们给出了 LM 崩溃的理论证明，该证明揭示了其崩溃原因，且证实所有自回归 LMs 必然崩溃。我们还有新发现：在递归生成的文本上训练时，LMs 的性能会逐步下降，直至不如随机初始化的 LM。训练后的 LMs 会产生大量重复文本，在众多自然语言任务中表现欠佳。上述证明和新发现加深了对 LM 崩溃的理解，提供了宝贵见解，或许能启发新的训练技术以减轻这一威胁。

> Language models (LMs) have been widely used to generate text on the Internet. The generated text is often collected into the training corpus of the next generations of LMs. Previous work has experimentally found that LMs collapse when trained on recursively generated text. This paper contributes to existing knowledge from two aspects. We present a theoretical proof of LM collapse. Our proof reveals the cause of LM collapse and proves that all auto-regressive LMs will definitely collapse. We present a new finding: the performance of LMs gradually declines when trained on recursively generated text until they perform no better than a randomly initialized LM. The trained LMs produce large amounts of repetitive text and perform poorly across a wide range of natural language tasks. The above proof and new findings deepen our understanding of LM collapse and offer valuable insights that may inspire new training techniques to mitigate this threat.

[Arxiv](https://arxiv.org/abs/2412.14872)