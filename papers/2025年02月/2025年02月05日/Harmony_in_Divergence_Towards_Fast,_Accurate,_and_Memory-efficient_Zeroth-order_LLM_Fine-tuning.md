# 分歧中的和谐：实现快速、准确且内存高效的零阶LLM微调

发布时间：2025年02月05日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）的优化方法，特别是零阶（ZO）优化与一阶（FO）优化的比较，并提出了一种新的优化方法（DiZO）。这些内容属于对LLM训练和优化方法的理论研究，旨在提高LLM的训练效率和性能。因此，这篇论文应归类为LLM理论。` `机器学习` `优化算法`

> Harmony in Divergence: Towards Fast, Accurate, and Memory-efficient Zeroth-order LLM Fine-tuning

# 摘要

> 大型语言模型（LLMs）虽在多任务中表现出色，但标准一阶（FO）微调对内存需求巨大，限制了实际应用。零阶（ZO）优化作为一种内存高效训练方法，仅需前向传播即可估计梯度，适合资源受限场景。然而，ZO在收敛速度和精度上远不及FO。为此，我们提出了一种逐层差异分析，揭示了FO与ZO的更新模式差异，并基于此设计了	extbf{Di}vergence-driven 	extbf{Z}eroth-	extbf{O}rder (	extbf{DiZO})优化方法。DiZO通过差异驱动的层适应，结合ZO更新投影，生成精确按需调整的更新幅度。实验表明，DiZO在不影响吞吐量的前提下，显著减少了收敛所需迭代，训练GPU时间最多减少48\%。此外，DiZO在微调RoBERTa-large、OPT系列和Llama系列时，不仅超越了ZO基线，有时甚至优于内存密集型的FO微调。

> Large language models (LLMs) excel across various tasks, but standard first-order (FO) fine-tuning demands considerable memory, significantly limiting real-world deployment. Recently, zeroth-order (ZO) optimization stood out as a promising memory-efficient training paradigm, avoiding backward passes and relying solely on forward passes for gradient estimation, making it attractive for resource-constrained scenarios. However, ZO method lags far behind FO method in both convergence speed and accuracy. To bridge the gap, we introduce a novel layer-wise divergence analysis that uncovers the distinct update pattern of FO and ZO optimization. Aiming to resemble the learning capacity of FO method from the findings, we propose \textbf{Di}vergence-driven \textbf{Z}eroth-\textbf{O}rder (\textbf{DiZO}) optimization. DiZO conducts divergence-driven layer adaptation by incorporating projections to ZO updates, generating diverse-magnitude updates precisely scaled to layer-wise individual optimization needs. Our results demonstrate that DiZO significantly reduces the needed iterations for convergence without sacrificing throughput, cutting training GPU hours by up to 48\% on various datasets. Moreover, DiZO consistently outperforms the representative ZO baselines in fine-tuning RoBERTa-large, OPT-series, and Llama-series on downstream tasks and, in some cases, even surpasses memory-intensive FO fine-tuning.

[Arxiv](https://arxiv.org/abs/2502.03304)