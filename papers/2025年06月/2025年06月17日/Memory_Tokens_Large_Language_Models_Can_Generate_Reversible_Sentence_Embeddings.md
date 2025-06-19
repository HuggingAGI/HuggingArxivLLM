# # 记忆令牌：大型语言模型能生成可逆句子嵌入

发布时间：2025年06月17日

`LLM理论` `文本处理`

> Memory Tokens: Large Language Models Can Generate Reversible Sentence Embeddings

# 摘要

> 在这项研究中，我们发现了一个有趣的现象：大型语言模型无需修改权重，即可通过生成可逆的句子嵌入精确重建原始文本。这一成果通过引入一个特殊的记忆令牌实现，其嵌入通过固定序列的训练进行优化。当模型被提示使用这个嵌入时，它可以精确地重建该固定序列。我们对这一现象进行了跨语言（英语和西班牙语）的评估，测试了长度可达约240个令牌的序列，以及参数规模从1亿到80亿的不同模型。值得注意的是，Llama 3.1 8B成功地重建了所有测试序列。我们的发现揭示了大型语言模型的一个有趣能力，并为基于记忆的检索、压缩和可控文本生成等潜在应用提供了启示。

> In this work, we observe an interesting phenomenon: it is possible to generate reversible sentence embeddings that allow an LLM to reconstruct the original text exactly, without modifying the model's weights. This is achieved by introducing a special memory token, whose embedding is optimized through training on a fixed sequence. When prompted with this embedding, the model reconstructs the fixed sequence exactly. We evaluate this phenomenon across English and Spanish datasets, sequences of up to approximately 240 tokens, and model scales ranging from 100M to 8B parameters. Notably, Llama 3.1 8B successfully reconstructs all tested sequences. Our findings highlight an interesting capability of LLMs and suggest potential applications in memory-based retrieval, compression, and controlled text generation.

[Arxiv](https://arxiv.org/abs/2506.15001)