# HiFi-KPI：用于从收益报告中提取分层 KPI 的数据集

发布时间：2025年02月21日

`LLM应用` `财务分析`

> HiFi-KPI: A Dataset for Hierarchical KPI Extraction from Earnings Filings

# 摘要

> 美国证券交易委员会 (SEC) 规定，上市公司需在财务报告中使用机器可读的内联可扩展商业报告语言 (iXBRL) 对数字进行标注。然而，iXBRL 的高度复杂性和粒度划分限制了标签在跨领域的应用。为此，我们推出了分层财务关键绩效指标 (HiFi-KPI) 数据集，旨在从非结构化财务文本中提取不同粒度级别的数值型 KPI。我们的方法通过基于分类法的分组方式，构建了一个包含 218,126 个标签的层级结构，并研究了不同分类层的结构意义。HiFi-KPI 包含约 180 万个段落和 500 万个实体，每个实体均与 iXBRL 的特定计算和呈现分类法相关联。我们提供了基于编码器的方法以及使用大语言模型 (LLMs) 进行结构化提取的基线方案。为了简化 LLM 的推理与评估流程，我们还发布了 HiFi-KPI Lite，这是一个由专家映射的四个标签的手动整理子集。所有相关资源均已公开发布。

> The U.S. Securities and Exchange Commission (SEC) requires that public companies file financial reports tagging numbers with the machine readable inline eXtensible Business Reporting Language (iXBRL) standard. However, the highly complex and highly granular taxonomy defined by iXBRL limits label transferability across domains. In this paper, we introduce the Hierarchical Financial Key Performance Indicator (HiFi-KPI) dataset, designed to facilitate numerical KPI extraction at specified levels of granularity from unstructured financial text. Our approach organizes a 218,126-label hierarchy using a taxonomy based grouping method, investigating which taxonomy layer provides the most meaningful structure. HiFi-KPI comprises ~1.8M paragraphs and ~5M entities, each linked to a label in the iXBRL-specific calculation and presentation taxonomies. We provide baselines using encoder-based approaches and structured extraction using Large Language Models (LLMs). To simplify LLM inference and evaluation, we additionally release HiFi-KPI Lite, a manually curated subset with four expert-mapped labels. We publicly release all artifacts

[Arxiv](https://arxiv.org/abs/2502.15411)