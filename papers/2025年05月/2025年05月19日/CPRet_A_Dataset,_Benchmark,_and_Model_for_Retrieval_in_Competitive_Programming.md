# CPRet：竞技编程领域内用于检索任务的数据集、基准与模型方案

发布时间：2025年05月19日

`LLM应用

理由：这篇论文探讨了竞争性编程基准中的相似问题检索问题，并提出了CPRet基准套件以及相关的检索器，属于大型语言模型在特定任务中的应用和评估。` `编程竞赛` `模型评估`

> CPRet: A Dataset, Benchmark, and Model for Retrieval in Competitive Programming

# 摘要

> 竞争性编程基准在编程竞赛和大型语言模型评估中广泛应用，但重复或高度相似的问题日益增多，不仅引发公平性担忧，还让人质疑其作为评估基准的有效性。本文提出相似问题检索这一新问题，并为此引入CPRet——一个面向竞争性编程的检索基准套件。CPRet涵盖四个任务：文本到代码、代码到代码、题目到重复题目和简化到完整题目，基于自动爬取和人工标注的数据构建。我们提供了高质量训练数据和时间分离测试集，确保评估可靠。此外，我们开发了CPRetriever-Code和CPRetriever-Prob两款检索器：前者通过新型Group-InfoNCE损失函数优化问题-代码对齐，后者专为识别问题相似性微调。两款模型表现优异，已开源供本地使用。分析表明，高度相似问题会虚高模型通过率并降低区分度，凸显未来评估中需引入相似性感知机制。代码和数据可在GitHub获取：https://github.com/coldchair/CPRet

> Competitive programming benchmarks are widely used in scenarios such as programming contests and large language model assessments. However, the growing presence of duplicate or highly similar problems raises concerns not only about competition fairness, but also about the validity of competitive programming as a benchmark for model evaluation. In this paper, we propose a new problem -- similar question retrieval -- to address this issue. Due to the lack of both data and models, solving this problem is challenging. To this end, we introduce CPRet, a retrieval-oriented benchmark suite for competitive programming, covering four retrieval tasks: two code-centric (i.e., Text-to-Code and Code-to-Code) and two newly proposed problem-centric tasks (i.e., Problem-to-Duplicate and Simplified-to-Full), built from a combination of automatically crawled problem-solution data and manually curated annotations. Our contribution includes both high-quality training data and temporally separated test sets for reliable evaluation. In addition, we develop two task-specialized retrievers based on this dataset: CPRetriever-Code, trained with a novel Group-InfoNCE loss for problem-code alignment, and CPRetriever-Prob, fine-tuned for identifying problem-level similarity. Both models achieve strong results and are open-sourced for local use. Finally, we analyze LiveCodeBench and find that high-similarity problems inflate model pass rates and reduce differentiation, underscoring the need for similarity-aware evaluation in future benchmarks.
  Code and data are available at: https://github.com/coldchair/CPRet

[Arxiv](https://arxiv.org/abs/2505.12925)