# 低资源语言LLMs的高效持续预训练

发布时间：2024年12月13日

`LLM应用

理由：这篇论文主要讨论了如何通过持续预训练（CPT）和词汇表优化来提升开源大型语言模型（OsLLMs）在低资源语言（LRLs）上的表现。这涉及到对现有LLM的改进和应用，特别是在多语言环境下的优化。因此，这篇论文属于LLM应用类别。` `低资源语言`

> Efficient Continual Pre-training of LLMs for Low-resource Languages

# 摘要

> 开源大型语言模型（OsLLMs）通过灵活调整模型参数，推动了自然语言研究的普及。然而，与专有LLMs类似，OsLLMs在低资源语言（LRLs）上的表现逊色于高资源语言（HRLs），主要原因是训练数据不足和词汇表覆盖不全。另一方面，使用大量特定语言数据进行持续预训练（CPT）在数据获取和计算资源方面成本高昂。我们的目标是大幅降低CPT成本。为此，我们首先开发了一种新算法，从大规模语料库中筛选文本子集，并展示了在极少量CPT数据下的有效性。为进一步提升效果，我们还设计了一种新算法来优化LLM词汇表。我们基于最新的Llama-3模型和九种印度语言（涵盖不同文字和资源水平）进行了实验，并使用IndicGenBench（印度语言生成任务基准数据集）进行评估。通过尝试多种CPT语料库和词汇表扩展方案，我们得出了跨语言家族的深刻见解。

> Open-source Large Language models (OsLLMs) propel the democratization of natural language research by giving the flexibility to augment or update model parameters for performance improvement. Nevertheless, like proprietary LLMs, Os-LLMs offer poorer performance on low-resource languages (LRLs) than high-resource languages (HRLs), owing to smaller amounts of training data and underrepresented vocabulary. On the other hand, continual pre-training (CPT) with large amounts of language-specific data is a costly proposition in terms of data acquisition and computational resources. Our goal is to drastically reduce CPT cost. To that end, we first develop a new algorithm to select a subset of texts from a larger corpus. We show the effectiveness of our technique using very little CPT data. In search of further improvement, we design a new algorithm to select tokens to include in the LLM vocabulary. We experiment with the recent Llama-3 model and nine Indian languages with diverse scripts and extent of resource availability. For evaluation, we use IndicGenBench, a generation task benchmark dataset for Indic languages. We experiment with various CPT corpora and augmented vocabulary size and offer insights across language families.

[Arxiv](https://arxiv.org/abs/2412.10244)