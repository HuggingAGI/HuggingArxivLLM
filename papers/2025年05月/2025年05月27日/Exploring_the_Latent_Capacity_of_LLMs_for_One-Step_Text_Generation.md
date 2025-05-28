# # 探索大型语言模型一次性文本生成的潜在能力
研究大型语言模型（LLMs）在一次性文本生成任务中的潜在能力。

发布时间：2025年05月27日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在生成文本时的内在机制，特别是其无需自回归生成多token的能力。研究深入分析了嵌入的行为及其编码的信息类型，属于对LLMs理论层面的研究，因此归类为LLM理论。`

> Exploring the Latent Capacity of LLMs for One-Step Text Generation

# 摘要

> 最近研究表明，大型语言模型（LLMs）仅凭一个专门训练的输入嵌入，就能通过自回归生成重构出长达数千个token的文本。本研究探讨了在没有自回归的情况下是否能够实现这种重构。我们发现，当仅提供两个学习到的嵌入时，冻结的LLMs可以在一次前向传递中生成数百个准确的token。这揭示了LLMs一个令人惊喜且尚未充分探索的能力：无需迭代解码的多token生成。我们研究了这些嵌入的行为，并深入探讨了它们所编码的信息类型。实证结果表明，尽管这些表示对于给定的文本并非唯一，但它们在嵌入空间中形成了相连且局部的区域——这一特性表明了学习一个专用编码器进入该空间的潜力。

> A recent study showed that large language models (LLMs) can reconstruct surprisingly long texts - up to thousands of tokens - via autoregressive generation from just one specially trained input embedding. In this work, we explore whether such reconstruction is possible without autoregression. We show that frozen LLMs can generate hundreds of accurate tokens in just one forward pass, when provided with only two learned embeddings. This reveals a surprising and underexplored capability of LLMs - multi-token generation without iterative decoding. We investigate the behaviour of these embeddings and provide insight into the type of information they encode. We also empirically show that although these representations are not unique for a given text, they form connected and local regions in embedding space - a property that suggests the potential of learning a dedicated encoder into that space.

[Arxiv](https://arxiv.org/abs/2505.21189)