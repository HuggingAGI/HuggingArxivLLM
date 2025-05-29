# EnsemW2S：利用大型语言模型集合提升弱到强的泛化能力

发布时间：2025年05月28日

`LLM理论` `人工智能` `机器学习`

> EnsemW2S: Enhancing Weak-to-Strong Generalization with Large Language Model Ensembles

# 摘要

> 大型语言模型（LLMs）正快速逼近甚至超越人类水平的表现，开发能够利用仅接触人类水平数据的小规模模型来监督和增强这些强大模型的方法变得至关重要。我们提出了一种名为	extbf{EnsemW2S}的新方法，旨在解决从弱到强（W2S）的泛化挑战。该方法通过迭代结合多个弱专家模型，采用基于标记的集成策略，系统性地优化模型性能。我们全面评估了弱专家模型集成和强学生模型在分布内（ID）和分布外（OOD）数据集上的表现，尤其在OOD场景中引入了问题难度作为额外维度。实验结果显示，我们的方法在ID数据集上实现了4%和3.2%的性能提升，在OOD数据集上分别达到了6%和2.28%的提升，充分证明了其在推进W2S泛化方面的有效性。

> With Large Language Models (LLMs) rapidly approaching and potentially surpassing human-level performance, it has become imperative to develop approaches capable of effectively supervising and enhancing these powerful models using smaller, human-level models exposed to only human-level data. We address this critical weak-to-strong (W2S) generalization challenge by proposing a novel method aimed at improving weak experts, by training on the same limited human-level data, enabling them to generalize to complex, super-human-level tasks. Our approach, called \textbf{EnsemW2S}, employs a token-level ensemble strategy that iteratively combines multiple weak experts, systematically addressing the shortcomings identified in preceding iterations. By continuously refining these weak models, we significantly enhance their collective ability to supervise stronger student models. We extensively evaluate the generalization performance of both the ensemble of weak experts and the subsequent strong student model across in-distribution (ID) and out-of-distribution (OOD) datasets. For OOD, we specifically introduce question difficulty as an additional dimension for defining distributional shifts. Our empirical results demonstrate notable improvements, achieving 4\%, and 3.2\% improvements on ID datasets and, upto 6\% and 2.28\% on OOD datasets for experts and student models respectively, underscoring the effectiveness of our proposed method in advancing W2S generalization.

[Arxiv](https://arxiv.org/abs/2505.21959)