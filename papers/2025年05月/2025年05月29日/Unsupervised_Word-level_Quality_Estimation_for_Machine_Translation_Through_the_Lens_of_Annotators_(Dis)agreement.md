# 无监督词级机器翻译质量评估：从标注者（不）一致性的视角出发

发布时间：2025年05月29日

`LLM应用` `机器翻译`

> Unsupervised Word-level Quality Estimation for Machine Translation Through the Lens of Annotators (Dis)agreement

# 摘要

> 词级质量估计（WQE）致力于自动识别机器翻译输出中的细粒度错误片段，并在多个领域中得到广泛应用，特别是在后编辑过程中为译员提供支持。然而，现代WQE技术通常成本高昂，涉及对大型语言模型的提示或在大量人工标注数据上进行专门训练。本研究探索了语言模型可解释性和不确定性量化方面的最新进展，通过分析翻译模型的内部工作原理来识别翻译错误。在涵盖12种翻译方向的14项指标的评估中，我们通过使用多组人工标注数据，量化了人工标签变化对指标性能的影响。我们的研究结果揭示了无监督指标的潜力尚未被充分挖掘，监督方法在面对标签不确定性时的局限性，以及单注释者评估实践中存在的脆性问题。

> Word-level quality estimation (WQE) aims to automatically identify fine-grained error spans in machine-translated outputs and has found many uses, including assisting translators during post-editing. Modern WQE techniques are often expensive, involving prompting of large language models or ad-hoc training on large amounts of human-labeled data. In this work, we investigate efficient alternatives exploiting recent advances in language model interpretability and uncertainty quantification to identify translation errors from the inner workings of translation models. In our evaluation spanning 14 metrics across 12 translation directions, we quantify the impact of human label variation on metric performance by using multiple sets of human labels. Our results highlight the untapped potential of unsupervised metrics, the shortcomings of supervised methods when faced with label uncertainty, and the brittleness of single-annotator evaluation practices.

[Arxiv](https://arxiv.org/abs/2505.23183)