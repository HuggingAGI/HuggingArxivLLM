# 合成评估究竟失去了什么？

发布时间：2025年05月28日

`LLM应用` `数据生成` `评估基准`

> What Has Been Lost with Synthetic Evaluation?

# 摘要

> 大型语言模型（LLMs）在数据生成领域的应用日益广泛，但创建评估基准为这一新兴范式提出了更高要求。这些基准需要精准靶向特定现象，遏制捷径利用，并保持足够的挑战性。通过两个案例研究，我们探索了LLMs是否能够满足这些高标准，具体方法是生成推理超文本基准并与精心众包创建的基准进行对比。我们选取了两个高质量阅读理解数据集进行评估：CondaQA（用于否定推理评估）和DROP（专注于数量推理）。研究发现，通过提示LLMs生成的数据集变体不仅符合注释指南，且成本仅为原始众包努力的一小部分。然而，与人类编写的基准相比，这些LLM生成的数据集对模型的挑战性稍逊一筹。这一发现揭示了使用LLMs生成评估数据可能带来的关键损失，并呼吁对这一日益普遍的基准创建方法进行重新评估。

> Large language models (LLMs) are increasingly used for data generation. However, creating evaluation benchmarks raises the bar for this emerging paradigm. Benchmarks must target specific phenomena, penalize exploiting shortcuts, and be challenging. Through two case studies, we investigate whether LLMs can meet these demands by generating reasoning over-text benchmarks and comparing them to those created through careful crowdsourcing. Specifically, we evaluate both the validity and difficulty of LLM-generated versions of two high-quality reading comprehension datasets: CondaQA, which evaluates reasoning about negation, and DROP, which targets reasoning about quantities. We find that prompting LLMs can produce variants of these datasets that are often valid according to the annotation guidelines, at a fraction of the cost of the original crowdsourcing effort. However, we show that they are less challenging for LLMs than their human-authored counterparts. This finding sheds light on what may have been lost by generating evaluation data with LLMs, and calls for critically reassessing the immediate use of this increasingly prevalent approach to benchmark creation.

[Arxiv](https://arxiv.org/abs/2505.22830)