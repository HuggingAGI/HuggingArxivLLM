# # POLYRAG: 将多重视图整合到检索增强生成中用于医疗应用

发布时间：2025年04月21日

`RAG` `医疗政策`

> POLYRAG: Integrating Polyviews into Retrieval-Augmented Generation for Medical Applications

# 摘要

> 大型语言模型 (LLMs) 正在以颠覆性力量重塑行业格局，为自然语言处理与逻辑推理等领域带来前所未有的突破。然而，在医疗场景中，知识更新与幻觉问题的挑战限制了 LLMs 的应用，而检索增强生成 (RAG) 则为此提供了重要解决方案。现有检索后阅读方法通常忽视了检索结果的时效性、权威性和普遍性，我们发现这些方法在现实场景中可能效果欠佳。为此，我们提出了 PolyRAG，它通过多角度整合信息，最终将多重视图融入医疗场景的检索增强生成。鉴于缺乏现实世界基准用于评估，我们构建了 PolyEVAL 基准，包含来自真实医疗场景（如医疗政策、医院及医生咨询和医疗保健）的查询和文档，并标注了多维度信息（如时效性、权威性）。在 PolyEVAL 上的实验结果充分证明了 PolyRAG 的优越性。

> Large language models (LLMs) have become a disruptive force in the industry, introducing unprecedented capabilities in natural language processing, logical reasoning and so on. However, the challenges of knowledge updates and hallucination issues have limited the application of LLMs in medical scenarios, where retrieval-augmented generation (RAG) can offer significant assistance. Nevertheless, existing retrieve-then-read approaches generally digest the retrieved documents, without considering the timeliness, authoritativeness and commonality of retrieval. We argue that these approaches can be suboptimal, especially in real-world applications where information from different sources might conflict with each other and even information from the same source in different time scale might be different, and totally relying on this would deteriorate the performance of RAG approaches. We propose PolyRAG that carefully incorporate judges from different perspectives and finally integrate the polyviews for retrieval augmented generation in medical applications. Due to the scarcity of real-world benchmarks for evaluation, to bridge the gap we propose PolyEVAL, a benchmark consists of queries and documents collected from real-world medical scenarios (including medical policy, hospital & doctor inquiry and healthcare) with multiple tagging (e.g., timeliness, authoritativeness) on them. Extensive experiments and analysis on PolyEVAL have demonstrated the superiority of PolyRAG.

[Arxiv](https://arxiv.org/abs/2504.14917)