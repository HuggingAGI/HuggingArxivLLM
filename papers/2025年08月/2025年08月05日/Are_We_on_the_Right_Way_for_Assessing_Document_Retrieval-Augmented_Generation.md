# # 问题
我们在正确评估文档检索增强生成的道路上了吗？

发布时间：2025年08月05日

`RAG` `信息检索`

> Are We on the Right Way for Assessing Document Retrieval-Augmented Generation?

# 摘要

> 基于多模态大型语言模型（MLLMs）的检索增强生成（RAG）系统在复杂文档理解领域展现出巨大潜力，但其发展却因现有评估方法的局限性而受到严重制约。当前基准测试往往聚焦于文档RAG系统的特定部分，且依赖不完整真实标签的合成数据，无法真实反映现实场景中的挑战。为突破这一瓶颈，我们推出Double-Bench——一个大规模、多语言、多模态的新型评估系统，能够对文档RAG系统各组件进行细致入微的评估。该系统包含3,276份文档（72,880页）及5,168个单跳和多跳查询，覆盖6种语言和4种文档类型，并支持动态更新以应对数据污染问题。所有查询均基于详尽扫描的证据页面，并经人工专家验证，确保最高质量和完整性。我们的实验涵盖9种先进嵌入模型、4种MLLMs以及4种端到端文档RAG框架，结果显示文本与视觉嵌入模型之间的差距正在缩小，凸显了构建更强大的文档检索模型的必要性。此外，研究还揭示了当前文档RAG框架中“过度自信”的困境——即便缺乏证据支持，系统仍倾向于提供答案。我们希望这一完全开源的Double-Bench能为未来高级文档RAG系统的研究奠定坚实基础，并计划定期更新语料库，每年发布新的基准测试。


> Retrieval-Augmented Generation (RAG) systems using Multimodal Large Language Models (MLLMs) show great promise for complex document understanding, yet their development is critically hampered by inadequate evaluation. Current benchmarks often focus on specific part of document RAG system and use synthetic data with incomplete ground truth and evidence labels, therefore failing to reflect real-world bottlenecks and challenges. To overcome these limitations, we introduce Double-Bench: a new large-scale, multilingual, and multimodal evaluation system that is able to produce fine-grained assessment to each component within document RAG systems. It comprises 3,276 documents (72,880 pages) and 5,168 single- and multi-hop queries across 6 languages and 4 document types with streamlined dynamic update support for potential data contamination issues. Queries are grounded in exhaustively scanned evidence pages and verified by human experts to ensure maximum quality and completeness. Our comprehensive experiments across 9 state-of-the-art embedding models, 4 MLLMs and 4 end-to-end document RAG frameworks demonstrate the gap between text and visual embedding models is narrowing, highlighting the need in building stronger document retrieval models. Our findings also reveal the over-confidence dilemma within current document RAG frameworks that tend to provide answer even without evidence support. We hope our fully open-source Double-Bench provide a rigorous foundation for future research in advanced document RAG systems. We plan to retrieve timely corpus and release new benchmarks on an annual basis.

[Arxiv](https://arxiv.org/abs/2508.03644)