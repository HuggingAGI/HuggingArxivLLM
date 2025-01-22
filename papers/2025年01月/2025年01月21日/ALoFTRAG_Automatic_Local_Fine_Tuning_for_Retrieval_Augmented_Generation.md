# ALoFTRAG: 自动局部微调助力检索增强生成

发布时间：2025年01月21日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）系统的改进，特别是通过自动本地微调检索增强生成模型（ALoFTRAG）框架来提升RAG系统在特定领域的表现。论文的核心内容围绕RAG系统的优化和应用，因此应归类为RAG。`

> ALoFTRAG: Automatic Local Fine Tuning for Retrieval Augmented Generation

# 摘要

> 检索增强生成（RAG）系统能显著提升大型语言模型（LLM）的输出准确性，但在新数据领域表现欠佳。
我们推出了自动本地微调检索增强生成模型（ALoFTRAG）框架，旨在无需人工标注数据或依赖大型教师模型，即可提升RAG系统在特定领域的表现。
通过生成并筛选合成训练数据，结合LoRA微调技术，ALoFTRAG在26种语言的20个数据集中，平均将引用和答案的准确性分别提升了8.3%和3.0%。
研究证明，ALoFTRAG为提升RAG准确性提供了一种实用、经济且数据安全的解决方案，尤其适用于医疗和金融等敏感领域。

> Retrieval Augmented Generation (RAG) systems have been shown to improve the accuracy of Large Language Model (LLM) outputs. However, these models can often achieve low accuracy when applied to new data domains.
  We introduce the Automatic Local Fine Tuning of Retrieval Augmented Generation models (ALoFTRAG) framework, designed to improve the accuracy of RAG systems on a given domain by training LLMs without manually labeled data or using larger teacher models.
  By generating and filtering synthetic training data and performing LoRA fine-tuning, ALoFTRAG improves citation and answer accuracy across 20 datasets in 26 languages by, on average, 8.3% and 3.0% respectively.
  Our results demonstrate that ALoFTRAG offers a practical, cost-effective, and data-secure solution for improving RAG accuracy, making it particularly applicable to sensitive domains such as healthcare and finance.

[Arxiv](https://arxiv.org/abs/2501.11929)