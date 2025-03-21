# # MKG-Rank：通过知识图谱提升大型语言模型，助力多语言医疗问答

发布时间：2025年03月20日

`LLM应用` `医学问答` `多语言技术`

> MKG-Rank: Enhancing Large Language Models with Knowledge Graph for Multilingual Medical Question Answering

# 摘要

> 大型语言模型（LLMs）在医学问答领域取得了显著进展，但受限于多语言训练数据的不平衡和低资源语言医学资源的匮乏，其应用主要局限于英语。针对这一问题，我们提出了基于多语言知识图谱的检索排序框架（MKG-Rank），通过增强知识图谱，使以英语为中心的LLMs能够实现多语言医学问答。通过词级翻译机制，我们的框架以较低成本将全面的以英语为中心的医学知识图谱高效融入LLMs推理过程，有效缓解跨语言语义失真，实现精准的跨语言医学问答。为了提升效率，我们引入了缓存和多角度排序策略来优化检索过程，显著缩短响应时间并优先呈现相关医学知识。在涵盖中文、日语、韩语和斯瓦希里语的多语言医学问答基准测试中，MKG-Rank始终优于零-shot LLMs，准确率最高提升了33.89%，同时保持了仅0.0009秒的平均检索时间。

> Large Language Models (LLMs) have shown remarkable progress in medical question answering (QA), yet their effectiveness remains predominantly limited to English due to imbalanced multilingual training data and scarce medical resources for low-resource languages. To address this critical language gap in medical QA, we propose Multilingual Knowledge Graph-based Retrieval Ranking (MKG-Rank), a knowledge graph-enhanced framework that enables English-centric LLMs to perform multilingual medical QA. Through a word-level translation mechanism, our framework efficiently integrates comprehensive English-centric medical knowledge graphs into LLM reasoning at a low cost, mitigating cross-lingual semantic distortion and achieving precise medical QA across language barriers. To enhance efficiency, we introduce caching and multi-angle ranking strategies to optimize the retrieval process, significantly reducing response times and prioritizing relevant medical knowledge. Extensive evaluations on multilingual medical QA benchmarks across Chinese, Japanese, Korean, and Swahili demonstrate that MKG-Rank consistently outperforms zero-shot LLMs, achieving maximum 33.89% increase in accuracy, while maintaining an average retrieval time of only 0.0009 seconds.

[Arxiv](https://arxiv.org/abs/2503.16131)