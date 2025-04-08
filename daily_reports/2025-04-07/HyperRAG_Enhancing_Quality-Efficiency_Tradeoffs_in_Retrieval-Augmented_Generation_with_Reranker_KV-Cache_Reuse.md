# HyperRAG：利用重排器KV缓存复用优化检索增强生成的质量与效率权衡
发布时间：2025年04月03日

`RAG`
> HyperRAG: Enhancing Quality-Efficiency Tradeoffs in Retrieval-Augmented Generation with Reranker KV-Cache Reuse
>
> 检索增强生成（RAG）作为一种强大的范式，通过将外部知识整合到生成过程中，显著提升了大型语言模型（LLMs）的性能。RAG流水线的关键在于重排序器，它从检索到的候选文档池中筛选出最相关的文档，从而大幅提高了生成响应的质量。然而，尽管重排序器在RAG流水线中优化了检索文档的选择，但也带来了计算挑战，阻碍了高吞吐量和低延迟的实现。为了解决这一问题，我们提出了HyperRAG系统，该系统通过利用KV缓存复用优化了RAG流水线中质量和效率之间的平衡，实现高效重排序推理。通过复用文档侧KV缓存，HyperRAG在保证高质量生成的同时，也实现了系统级的高效性。为了充分发挥KV缓存复用的优势，HyperRAG集成了多种系统级优化策略，旨在进一步提升效率和扩展性。实验结果表明，与传统RAG服务相比，HyperRAG在仅使用解码器端重排序器的情况下，实现了2-3倍的吞吐量提升，并且在下游任务中也表现出更优的性能。
>
> https://arxiv.org/abs/2504.02921

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.02921](https://arxiv.org/abs/2504.02921)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)