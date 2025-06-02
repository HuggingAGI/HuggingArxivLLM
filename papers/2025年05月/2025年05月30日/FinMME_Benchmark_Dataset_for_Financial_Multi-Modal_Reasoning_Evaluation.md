# FinMME：金融多模态推理评估基准测试数据集

发布时间：2025年05月30日

`LLM应用

这篇论文主要讨论了多模态大型语言模型（MLLMs）在金融领域的应用，并介绍了他们开发的金融多模态评估数据集FinMME和评估系统FinScore。这些工作属于LLM在特定领域的应用和评估，因此归类为LLM应用。` `金融研究`

> FinMME: Benchmark Dataset for Financial Multi-Modal Reasoning Evaluation

# 摘要

> 多模态大型语言模型（MLLMs）近年来发展迅猛，但在金融领域，有效的专用多模态评估数据集却明显匮乏。为了推动MLLMs在金融领域的进展，我们推出了FinMME，该数据集涵盖18个金融领域和6种资产类别，包含11,000多个高质量的金融研究样本，囊括10种主要图表类型和21种子类型。我们通过20名标注者和精心设计的验证机制确保数据质量。此外，我们开发了FinScore评估系统，该系统结合了幻觉惩罚和多维能力评估，以提供无偏见的评估。广泛的实验结果表明，即使是像GPT-4o这样最先进的模型，在FinMME上的表现也令人失望，凸显了其挑战性。该基准测试展现了高度的稳健性，不同提示下的预测变化率低于1%，相较于现有数据集，展现出更卓越的可靠性。我们的数据集和评估协议可在https://huggingface.co/datasets/luojunyu/FinMME和https://github.com/luo-junyu/FinMME获取。

> Multimodal Large Language Models (MLLMs) have experienced rapid development in recent years. However, in the financial domain, there is a notable lack of effective and specialized multimodal evaluation datasets. To advance the development of MLLMs in the finance domain, we introduce FinMME, encompassing more than 11,000 high-quality financial research samples across 18 financial domains and 6 asset classes, featuring 10 major chart types and 21 subtypes. We ensure data quality through 20 annotators and carefully designed validation mechanisms. Additionally, we develop FinScore, an evaluation system incorporating hallucination penalties and multi-dimensional capability assessment to provide an unbiased evaluation. Extensive experimental results demonstrate that even state-of-the-art models like GPT-4o exhibit unsatisfactory performance on FinMME, highlighting its challenging nature. The benchmark exhibits high robustness with prediction variations under different prompts remaining below 1%, demonstrating superior reliability compared to existing datasets. Our dataset and evaluation protocol are available at https://huggingface.co/datasets/luojunyu/FinMME and https://github.com/luo-junyu/FinMME.

[Arxiv](https://arxiv.org/abs/2505.24714)