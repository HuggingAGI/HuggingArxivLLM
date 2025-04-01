# 大语言模型服务中的键值缓存压缩技术新思路

发布时间：2025年03月31日

`LLM应用

LLM应用` `大数据` `云计算`

> Rethinking Key-Value Cache Compression Techniques for Large Language Model Serving

# 摘要

> 键值缓存压缩技术作为一种有前景的方法出现，旨在优化大型语言模型（LLM）的服务性能。它主要通过降低键值缓存的内存占用来减少计算成本。尽管在算法开发方面取得了进展，但它们在生产环境中的应用仍不普及。本文从实践角度重新审视主流的键值缓存压缩解决方案。我们的贡献有三个方面。首先，我们全面回顾了现有键值缓存压缩算法的设计和基准测试研究，并识别出性能评估中存在的一些缺失部分，这些缺失可能阻碍其在实际应用中的采用。其次，我们对具有代表性的键值缓存压缩方法进行了实证评估，揭示了影响计算效率的两个关键问题：（1）虽然压缩键值缓存可以减少内存消耗，但目前的实现（例如FlashAttention、PagedAttention）并未针对生产级别的LLM服务进行优化，导致吞吐量性能不佳；（2）压缩键值缓存可能导致输出变长，从而增加端到端延迟。我们进一步调查了单个样本的准确性表现，而非整体性能，揭示了在处理特定LLM任务时键值缓存压缩的内在局限性。第三，我们提供了工具来为未来的键值缓存压缩研究提供见解，并促进其在生产环境中的实际部署。这些工具在GitHub上开源，链接为：https://github.com/LLMkvsys/rethink-kv-compression。


> Key-Value cache (\texttt{KV} \texttt{cache}) compression has emerged as a promising technique to optimize Large Language Model (LLM) serving. It primarily decreases the memory consumption of \texttt{KV} \texttt{cache} to reduce the computation cost. Despite the development of many compression algorithms, their applications in production environments are still not prevalent. In this paper, we revisit mainstream \texttt{KV} \texttt{cache} compression solutions from a practical perspective. Our contributions are three-fold. First, we comprehensively review existing algorithmic designs and benchmark studies for \texttt{KV} \texttt{cache} compression and identify missing pieces in their performance measurement, which could hinder their adoption in practice. Second, we empirically evaluate representative \texttt{KV} \texttt{cache} compression methods to uncover two key issues that affect the computational efficiency: (1) while compressing \texttt{KV} \texttt{cache} can reduce memory consumption, current implementations (e.g., FlashAttention, PagedAttention) do not optimize for production-level LLM serving, resulting in suboptimal throughput performance; (2) compressing \texttt{KV} \texttt{cache} may lead to longer outputs, resulting in increased end-to-end latency. We further investigate the accuracy performance of individual samples rather than the overall performance, revealing the intrinsic limitations in \texttt{KV} \texttt{cache} compression when handling specific LLM tasks. Third, we provide tools to shed light on future \texttt{KV} \texttt{cache} compression studies and facilitate their practical deployment in production. They are open-sourced in \href{https://github.com/LLMkvsys/rethink-kv-compression}{https://github.com/LLMkvsys/rethink-kv-compression}.

[Arxiv](https://arxiv.org/abs/2503.24000)