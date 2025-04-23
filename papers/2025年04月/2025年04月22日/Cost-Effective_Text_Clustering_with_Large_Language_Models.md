# 利用大型语言模型实现高效文本聚类

发布时间：2025年04月22日

`LLM应用` `文本聚类`

> Cost-Effective Text Clustering with Large Language Models

# 摘要

> 为应对上述挑战，我们提出了 TECL，一个成本效益显著的框架，它通过巧妙利用 LLMs 的反馈，在有限的 LLM 查询预算内实现精准的文本聚类。TECL 框架的核心在于使用我们的 EdgeLLM 或 TriangleLLM 来构建文本对的 must-link/cannot-link 约束，并将这些约束作为监督信号输入到我们的加权约束聚类方法中，从而生成最终的聚类结果。特别值得一提的是，EdgeLLM（ resp. TriangleLLM）通过精心设计的贪心算法和精准的提示工程技术，能够有效识别出具有信息价值的文本对（ resp. 三元组），并准确提取出成对的约束条件。我们的实验结果表明，在相同的 LLM 查询成本下，TECL 在无监督文本聚类任务中始终显著优于现有解决方案。

> Text clustering aims to automatically partition a collection of text documents into distinct clusters based on linguistic features. In the literature, this task is usually framed as metric clustering based on text embeddings from pre-trained encoders or a graph clustering problem upon pairwise similarities from an oracle, e.g., a large ML model. Recently, large language models (LLMs) bring significant advancement in this field by offering contextualized text embeddings and highly accurate similarity scores, but meanwhile, present grand challenges to cope with substantial computational and/or financial overhead caused by numerous API-based queries or inference calls to the models.
  In response, this paper proposes TECL, a cost-effective framework that taps into the feedback from LLMs for accurate text clustering within a limited budget of queries to LLMs. Under the hood, TECL adopts our EdgeLLM or TriangleLLM to construct must-link/cannot-link constraints for text pairs, and further leverages such constraints as supervision signals input to our weighted constrained clustering approach to generate clusters. Particularly, EdgeLLM (resp. TriangleLLM) enables the identification of informative text pairs (resp. triplets) for querying LLMs via well-thought-out greedy algorithms and accurate extraction of pairwise constraints through carefully-crafted prompting techniques. Our experiments on multiple benchmark datasets exhibit that TECL consistently and considerably outperforms existing solutions in unsupervised text clustering under the same query cost for LLMs.

[Arxiv](https://arxiv.org/abs/2504.15640)