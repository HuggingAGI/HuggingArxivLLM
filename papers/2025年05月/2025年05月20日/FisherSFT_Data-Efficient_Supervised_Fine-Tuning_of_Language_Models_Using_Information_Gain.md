# FisherSFT：利用信息增益实现语言模型的数据高效监督微调

发布时间：2025年05月20日

`LLM理论` `机器学习`

> FisherSFT: Data-Efficient Supervised Fine-Tuning of Language Models Using Information Gain

# 摘要

> 监督微调（SFT）是将大型语言模型（LLMs）适应新领域的重要方法。本研究通过优化训练样本的选择，显著提升了监督微调的统计效率。具体而言，我们针对固定数量的训练样本（决定微调的计算成本），提出了一种高效的信息最大化选择策略。我们的方法核心思想是选择能最大化信息增益的样本，通过测量LLM对数似然的Hessian矩阵来衡量信息增益。我们采用多项式逻辑回归模型对LLM的最后一层进行线性化，从而高效地近似计算这一过程。我们的方法具有计算高效、可分析性强的特点，并在实验中表现出色。我们通过多个问题的验证以及定量结果和LLM评估，充分证明了方法的有效性。

> Supervised fine-tuning (SFT) is a standard approach to adapting large language models (LLMs) to new domains. In this work, we improve the statistical efficiency of SFT by selecting an informative subset of training examples. Specifically, for a fixed budget of training examples, which determines the computational cost of fine-tuning, we determine the most informative ones. The key idea in our method is to select examples that maximize information gain, measured by the Hessian of the log-likelihood of the LLM. We approximate it efficiently by linearizing the LLM at the last layer using multinomial logistic regression models. Our approach is computationally efficient, analyzable, and performs well empirically. We demonstrate this on several problems, and back our claims with both quantitative results and an LLM evaluation.

[Arxiv](https://arxiv.org/abs/2505.14826)