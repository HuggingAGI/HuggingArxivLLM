# SampleLLM: 推荐系统中表格数据合成的优化

发布时间：2025年01月27日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）来提升推荐系统中的表格数据合成质量。论文提出了一个名为SampleLLM的两阶段框架，通过LLMs生成与目标数据集分布高度一致的数据，并优化特征关系。这属于LLM在实际应用中的具体使用，因此归类为LLM应用。` `推荐系统` `机器学习`

> SampleLLM: Optimizing Tabular Data Synthesis in Recommendations

# 摘要

> # 摘要
表格数据合成在机器学习中至关重要，但现有方法——主要基于统计或深度学习模型——在推荐系统中表现不佳。这些方法难以从稀疏数据中捕捉复杂分布和特征关系，也无法理解语义特征。最近，大型语言模型（LLMs）通过少样本学习和语义理解展示了生成合成数据的潜力，但由于与目标数据集的分布差异，常出现分布不一致和多样性不足的问题。为此，我们提出了SampleLLM，一个两阶段框架，旨在提升推荐任务中的表格数据合成质量。第一阶段，SampleLLM利用思维链提示和多样化示例的LLMs生成与目标数据集分布高度一致的数据，即使输入样本有限。第二阶段，采用基于特征归因的重要性采样方法优化合成数据中的特征关系，减少LLM引入的分布偏差。实验结果表明，SampleLLM在推荐任务中显著优于现有方法，并在更广泛的表格数据场景中展现出潜力。

> Tabular data synthesis is crucial in machine learning, yet existing general methods-primarily based on statistical or deep learning models-are highly data-dependent and often fall short in recommender systems. This limitation arises from their difficulty in capturing complex distributions and understanding feature relationships from sparse and limited data, along with their inability to grasp semantic feature relations. Recently, Large Language Models (LLMs) have shown potential in generating synthetic data samples through few-shot learning and semantic understanding. However, they often suffer from inconsistent distribution and lack of diversity due to their inherent distribution disparity with the target dataset. To address these challenges and enhance tabular data synthesis for recommendation tasks, we propose a novel two-stage framework named SampleLLM to improve the quality of LLM-based tabular data synthesis for recommendations by ensuring better distribution alignment. In the first stage, SampleLLM employs LLMs with Chain-of-Thought prompts and diverse exemplars to generate data that closely aligns with the target dataset distribution, even when input samples are limited. The second stage uses an advanced feature attribution-based importance sampling method to refine feature relationships within the synthesized data, reducing any distribution biases introduced by the LLM. Experimental results on three recommendation datasets, two general datasets, and online deployment illustrate that SampleLLM significantly surpasses existing methods for recommendation tasks and holds promise for a broader range of tabular data scenarios.

[Arxiv](https://arxiv.org/abs/2501.16125)