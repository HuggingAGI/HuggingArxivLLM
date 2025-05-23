# 借助SMILES解析提升大型语言模型的化学理解力

发布时间：2025年05月22日

`LLM应用` `分子科学` `分子图`

> Improving Chemical Understanding of LLMs via SMILES Parsing

# 摘要

> 大型语言模型（LLMs）在科学发现，尤其是分子科学领域，正日益展现出强大的应用潜力。理解分子结构是这些模型的核心能力之一，而分子结构通常以SMILES表示形式编码。然而，现有的LLMs在解读SMILES时仍面临挑战，甚至在分子环计数等基础任务上表现欠佳。为突破这一限制，我们提出了CLEANMOL——一个创新性框架，通过将SMILES解析转化为一系列清晰、确定性的任务，专为促进基于图的分子理解而设计。这些任务涵盖从子图匹配到全局图匹配的范围，提供与分子结构特性相匹配的结构化监督。我们构建了一个带有自适应难度评分的分子预训练数据集，并在开源LLMs上进行预训练。实验结果表明，CLEANMOL不仅显著提升了模型的结构理解能力，还在Mol-Instructions基准测试中取得了最佳或与基线相当的性能。

> Large language models (LLMs) are increasingly recognized as powerful tools for scientific discovery, particularly in molecular science. A fundamental requirement for these models is the ability to accurately understand molecular structures, commonly encoded in the SMILES representation. However, current LLMs struggle to interpret SMILES, even failing to carry out basic tasks such as counting molecular rings. To address this limitation, we introduce CLEANMOL, a novel framework that formulates SMILES parsing into a suite of clean and deterministic tasks explicitly designed to promote graph-level molecular comprehension. These tasks span from subgraph matching to global graph matching, providing structured supervision aligned with molecular structural properties. We construct a molecular pretraining dataset with adaptive difficulty scoring and pre-train open-source LLMs on these tasks. Our results show that CLEANMOL not only enhances structural comprehension but also achieves the best or competes with the baseline on the Mol-Instructions benchmark.

[Arxiv](https://arxiv.org/abs/2505.16340)