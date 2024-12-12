# 两个优于一个：采用多粒度自注入的上下文窗口拓展

发布时间：2024年10月25日

`LLM应用` `模型压缩`

> Two are better than one: Context window extension with multi-grained self-injection

# 摘要

> 当代大型语言模型（LLMs）有限的上下文窗口，成为其在各领域广泛应用的巨大阻碍。虽然在长上下文数据上持续预训练是个直接有效的办法，但会在数据获取和计算资源上耗费大量成本。为解决此问题，我们提出了 SharedLLM，这是一种基于多粒度上下文压缩和查询感知信息检索设计理念的新方法。SharedLLM 由两个短上下文的 LLMs 组成，比如 LLaMA-2，分别称为上层模型和下层模型。下层模型充当压缩器，上层模型则是解码器。上层模型从下层模型接收压缩的多粒度上下文信息，并对运行文本进行上下文感知建模。压缩器与解码器之间的信息传输仅在最低层进行，以避免下层模型中的长前向路径和上层模型中的冗余交叉注意力模块。基于此架构，我们引入了一种专门的树状数据结构，能高效地对文本块的多粒度上下文信息进行编码、存储和检索。此结构与搜索算法相结合，可依据输入查询从树的各级快速编码和检索相关信息。在整个过程中，发送方和接收方均来自同一 LLM 层，这被称为自注入。

> The limited context window of contemporary large language models (LLMs) remains a huge barrier to their broader application across various domains. While continual pre-training on long-context data is a straightforward and effective solution, it incurs substantial costs in terms of data acquisition and computational resources. To alleviate this issue, we propose SharedLLM, a novel approach grounded in the design philosophy of multi-grained context compression and query-aware information retrieval. SharedLLM is composed of two short-context LLMs such as LLaMA-2, termed upper model and lower model. The lower model functions as a compressor while the upper model acts as a decoder. The upper model receives compressed, multi-grained context information from the lower model and performs context-aware modeling on the running text. Information transfer between the compressor and decoder occurs only at the lowest layers to refrain from long forward paths in the lower model and redundant cross-attention modules in the upper model. Based on this architecture, we introduce a specialized tree-style data structure to efficiently encode, store and retrieve multi-grained contextual information for text chunks. This structure, combined with a search algorithm, enables rapid encoding and retrieval of relevant information from various levels of the tree based on the input query. This entire process, wherein the sender and receiver are derived from the same LLM layer, is referred to as self-injection.

[Arxiv](https://arxiv.org/abs/2410.19318)