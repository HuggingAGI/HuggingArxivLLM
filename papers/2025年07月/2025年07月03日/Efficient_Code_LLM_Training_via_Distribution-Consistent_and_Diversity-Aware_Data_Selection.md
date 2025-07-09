# 通过分布一致且多样性感知的数据选择进行高效代码LLM训练

发布时间：2025年07月03日

`LLM应用` `软件工程` `代码生成`

> Efficient Code LLM Training via Distribution-Consistent and Diversity-Aware Data Selection

# 摘要

> 近期，大型语言模型（LLMs）在代码生成与程序理解领域取得了显著突破，推动了软件工程的快速发展。然而，现有方法过分依赖数据量的堆积，忽视了数据质量的重要性，导致训练效率低下。为解决这一问题，我们提出了一种基于参数化模型的代码数据选择方法，旨在同时提升训练效率与模型性能。通过优化参数化模型，我们确保了所选数据子集的分布一致性和多样性，从而保证了数据质量。实验结果表明，仅使用10K样本，我们的方法在HumanEval和MBPP任务上分别比92K全样本基线提升了2.4%和2.3%。与其它采样方法相比，我们的方法在性能和效率上均表现更优。这充分证明，我们的方法不仅有效提升了模型性能，还大幅降低了计算成本。

> Recent advancements in large language models (LLMs) have significantly improved code generation and program comprehension, accelerating the evolution of software engineering. Current methods primarily enhance model performance by leveraging vast amounts of data, focusing on data quantity while often overlooking data quality, thereby reducing training efficiency. To address this, we introduce an approach that utilizes a parametric model for code data selection, aimed at improving both training efficiency and model performance. Our method optimizes the parametric model to ensure distribution consistency and diversity within the selected subset, guaranteeing high-quality data. Experimental results demonstrate that using only 10K samples, our method achieves gains of 2.4% (HumanEval) and 2.3% (MBPP) over 92K full-sampled baseline, outperforming other sampling approaches in both performance and efficiency. This underscores that our method effectively boosts model performance while significantly reducing computational costs.

[Arxiv](https://arxiv.org/abs/2507.02378)