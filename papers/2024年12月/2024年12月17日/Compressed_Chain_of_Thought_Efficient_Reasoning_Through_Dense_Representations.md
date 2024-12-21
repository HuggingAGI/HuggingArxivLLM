# 压缩思维链：借助密集表示实现高效推理

发布时间：2024年12月17日

`LLM应用` `语言模型`

> Compressed Chain of Thought: Efficient Reasoning Through Dense Representations

# 摘要

> 摘要：思维链（CoT）解码能让语言模型提升推理性能，不过其代价是解码时生成延迟较高。近期的一些提议对沉思令牌的变体进行了探索，这是我们引入的一个术语，指的是在推理中用于允许额外计算的特殊令牌。此前的工作把从离散嵌入集合中抽取的固定长度序列当作沉思令牌。在此，我们提出压缩思维链（CCoT），这是一个生成可变序列长度、有内容且连续的沉思令牌的框架。生成的沉思令牌是显式推理链的压缩表示，我们的方法能够应用于现有的解码器语言模型。通过实验，我们展示了 CCoT 如何借助对密集有内容的表示进行额外推理，从而实现准确性的相应提升。而且，通过控制生成的沉思令牌数量，能够按需自适应地修改推理改进效果。

> 
Abstract:Chain-of-thought (CoT) decoding enables language models to improve reasoning performance at the cost of high generation latency in decoding. Recent proposals have explored variants of contemplation tokens, a term we introduce that refers to special tokens used during inference to allow for extra computation. Prior work has considered fixed-length sequences drawn from a discrete set of embeddings as contemplation tokens. Here we propose Compressed Chain-of-Thought (CCoT), a framework to generate contentful and continuous contemplation tokens of variable sequence length. The generated contemplation tokens are compressed representations of explicit reasoning chains, and our method can be applied to off-the-shelf decoder language models. Through experiments, we illustrate how CCoT enables additional reasoning over dense contentful representations to achieve corresponding improvements in accuracy. Moreover, the reasoning improvements can be adaptively modified on demand by controlling the number of contemplation tokens generated.
    

[Arxiv](https://arxiv.org/pdf/2412.13171)