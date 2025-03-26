# KVShare：语义感知键值缓存共享实现高效大语言模型推理

发布时间：2025年03月17日

`LLM应用`

> KVShare: Semantic-Aware Key-Value Cache Sharing for Efficient Large Language Model Inference

# 摘要

> 本文提出了一种基于语义相似性的多用户键值（KV）缓存共享技术KVShare，旨在提升大型语言模型（LLMs）和多模态大型语言模型（MLLMs）的推理效率。针对现有前缀缓存（严格的文本前缀匹配）和语义缓存（响应多样性丢失）的局限性，KVShare通过语义对齐算法和差异编辑操作实现了细粒度的KV缓存复用。实验证明，在真实用户对话数据集上，KVShare将KV缓存命中率提升了60%以上，同时保持了与全计算相当的输出质量（BLEU和Rouge-L指标无显著下降）。该方法有效降低了GPU资源消耗，适用于具有重复查询的场景，如医疗和教育领域。

> This paper presents KVShare, a multi-user Key-Value (KV) Cache sharing technology based on semantic similarity, designed to enhance the inference efficiency of Large Language Models (LLMs) and Multimodal Large Language Models (MLLMs). Addressing the limitations of existing prefix caching (strict text prefix matching) and semantic caching (loss of response diversity), KVShare achieves fine-grained KV cache reuse through semantic alignment algorithms and differential editing operations. Experiments on real-world user conversation datasets demonstrate that KVShare improves KV cache hit rates by over 60%, while maintaining output quality comparable to full computation (no significant degradation in BLEU and Rouge-L metrics). This approach effectively reduces GPU resource consumption and is applicable to scenarios with repetitive queries, such as healthcare and education.

[Arxiv](https://arxiv.org/abs/2503.16525)