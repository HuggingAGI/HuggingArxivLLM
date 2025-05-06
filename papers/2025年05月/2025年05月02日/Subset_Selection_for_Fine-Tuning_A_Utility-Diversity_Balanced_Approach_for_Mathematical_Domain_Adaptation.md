# 微调中的子集选择：数学领域适应的效用-多样性平衡方法

发布时间：2025年05月02日

`LLM理论` `人工智能`

> Subset Selection for Fine-Tuning: A Utility-Diversity Balanced Approach for Mathematical Domain Adaptation

# 摘要

> 我们提出了一种优化方法，通过预算子集选择方法，高效地在特定领域（如数学领域）对大型语言模型（LLMs）进行微调。方法结合效用和多样性指标，选择最具信息量和代表性的训练样本。目标是通过精心挑选数据点，达到接近完整数据集的性能，同时大幅减少计算成本和训练时间。效用指标综合考虑困惑度和思维链（CoT）损失，识别对模型学习贡献最大的挑战性示例；多样性指标确保在数学子领域中获得广泛覆盖。我们在LLaMA-3 8B和Phi-3模型上评估了方法，并与随机选择、基于多样性的采样及现有最先进的子集选择技术进行了对比。

> We propose a refined approach to efficiently fine-tune large language models (LLMs) on specific domains like the mathematical domain by employing a budgeted subset selection method. Our approach combines utility and diversity metrics to select the most informative and representative training examples. The final goal is to achieve near-full dataset performance with meticulously selected data points from the entire dataset while significantly reducing computational cost and training time and achieving competitive performance as the full dataset. The utility metric incorporates both perplexity and Chain-of-Thought (CoT) loss to identify challenging examples that contribute most to model learning, while the diversity metric ensures broad coverage across mathematical subdomains. We evaluate our method on LLaMA-3 8B and Phi-3 models, comparing against several baseline approaches, including random selection, diversity-based sampling, and existing state-of-the-art subset selection techniques.

[Arxiv](https://arxiv.org/abs/2505.01523)