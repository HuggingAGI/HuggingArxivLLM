# Hyper-RAG：利用超图驱动的检索增强生成技术，有效对抗大型语言模型的幻觉问题

发布时间：2025年03月30日

`RAG` `医疗诊断`

> Hyper-RAG: Combating LLM Hallucinations using Hypergraph-Driven Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLMs）正在改变教育、金融和医疗等多个领域，通过提升内容生成和决策能力推动行业发展。然而，由于幻觉现象（即生成内容与事实准确性偏离，可能带来不良后果），LLMs在医疗领域的应用仍需谨慎。为解决这一问题，我们提出了一种名为Hyper-RAG的基于超图的增强式检索生成方法，能够全面捕捉特定领域知识中的成对及更复杂关系，从而有效缓解幻觉现象。在NeurologyCrop数据集上，使用六种主流LLMs进行的实验表明，与直接使用LLMs相比，Hyper-RAG的准确率平均提高了12.3%，并且比Graph RAG和Light RAG分别高出6.3%和6.0%。此外，随着查询复杂度的增加，Hyper-RAG保持了稳定的性能表现，而现有方法则出现了性能下降。在九个多样化数据集上的进一步验证显示，基于选择的评估方法下，Hyper-RAG相较于Light RAG性能提升了35.5%。轻量化版本Hyper-RAG-Lite在检索速度上是Light RAG的两倍，并且性能提升了3.3%。这些结果证实了Hyper-RAG在提升LLM可靠性、减少幻觉方面的有效性，使其成为医疗诊断等高风险应用的理想解决方案。

> Large language models (LLMs) have transformed various sectors, including education, finance, and medicine, by enhancing content generation and decision-making processes. However, their integration into the medical field is cautious due to hallucinations, instances where generated content deviates from factual accuracy, potentially leading to adverse outcomes. To address this, we introduce Hyper-RAG, a hypergraph-driven Retrieval-Augmented Generation method that comprehensively captures both pairwise and beyond-pairwise correlations in domain-specific knowledge, thereby mitigating hallucinations. Experiments on the NeurologyCrop dataset with six prominent LLMs demonstrated that Hyper-RAG improves accuracy by an average of 12.3% over direct LLM use and outperforms Graph RAG and Light RAG by 6.3% and 6.0%, respectively. Additionally, Hyper-RAG maintained stable performance with increasing query complexity, unlike existing methods which declined. Further validation across nine diverse datasets showed a 35.5% performance improvement over Light RAG using a selection-based assessment. The lightweight variant, Hyper-RAG-Lite, achieved twice the retrieval speed and a 3.3% performance boost compared with Light RAG. These results confirm Hyper-RAG's effectiveness in enhancing LLM reliability and reducing hallucinations, making it a robust solution for high-stakes applications like medical diagnostics.

[Arxiv](https://arxiv.org/abs/2504.08758)