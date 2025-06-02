# # LGAR: 零样本 LLM 引导神经排序用于系统文献综述中的摘要筛选

发布时间：2025年05月30日

`LLM应用` `学术研究`

> LGAR: Zero-Shot LLM-Guided Neural Ranking for Abstract Screening in Systematic Literature Reviews

# 摘要

> 科学文献的快速增长让追踪前沿进展变得日益困难。系统性文献综述（SLRs）的目标是识别并评估某一主题下的所有相关论文。在检索到候选论文后，摘要筛选阶段将决定论文的初步相关性。目前，基于大型语言模型（LLMs）的摘要筛选方法主要聚焦于二元分类场景，而现有的基于问答（QA）的排序方法则面临错误传播的挑战。尽管LLMs为评估SLR的纳入与排除标准提供了独特的机会，现有的基准测试却未能全面涵盖这些标准。我们从57个SLR中手动提取了相关标准及研究问题，主要集中在医学领域，从而实现了方法间的原则性对比。此外，我们提出了一种零样本LLM引导的摘要排名系统——LGAR，它由基于LLM的分级相关性评分器和密集重排器组成。通过广泛的实验，我们发现与现有的基于QA的方法相比，LGAR在平均精度方面提升了5-10个百分点。我们的代码和数据已公开发布。


> The scientific literature is growing rapidly, making it hard to keep track of the state-of-the-art. Systematic literature reviews (SLRs) aim to identify and evaluate all relevant papers on a topic. After retrieving a set of candidate papers, the abstract screening phase determines initial relevance. To date, abstract screening methods using large language models (LLMs) focus on binary classification settings; existing question answering (QA) based ranking approaches suffer from error propagation. LLMs offer a unique opportunity to evaluate the SLR's inclusion and exclusion criteria, yet, existing benchmarks do not provide them exhaustively. We manually extract these criteria as well as research questions for 57 SLRs, mostly in the medical domain, enabling principled comparisons between approaches. Moreover, we propose LGAR, a zero-shot LLM Guided Abstract Ranker composed of an LLM based graded relevance scorer and a dense re-ranker. Our extensive experiments show that LGAR outperforms existing QA-based methods by 5-10 pp. in mean average precision. Our code and data is publicly available.

[Arxiv](https://arxiv.org/abs/2505.24757)