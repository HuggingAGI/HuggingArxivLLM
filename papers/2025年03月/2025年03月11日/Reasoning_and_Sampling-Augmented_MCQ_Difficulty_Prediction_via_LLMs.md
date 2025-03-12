# 基于大语言模型的推理与抽样增强选择题难度预测.

发布时间：2025年03月11日

`LLM应用` `人工智能`

> Reasoning and Sampling-Augmented MCQ Difficulty Prediction via LLMs

# 摘要

> 多项选择题（MCQs）的难度是教育评估中的关键因素。预测 MCQ 的难度具有挑战性，因为它不仅需要理解正确选项的复杂性，还需要评估干扰项的可信度。本文提出了一种新颖的两阶段方法来预测 MCQ 的难度。首先，我们利用大型语言模型（LLMs）来增强推理步骤，从而更好地估计每个 MCQ 的复杂性。我们不仅使用 MCQ 本身，还将推理步骤作为输入来预测难度。其次，我们从分布中采样知识水平，以捕捉干扰项的可信度并解释学生回答的差异。这一基于项目反应理论（IRT）的设置，使我们能够估计学生选择每个（正确和错误）选项的可能性。通过基于 Kullback-Leibler（KL）散度的正则化目标，我们将这些预测与其真实值对齐，并利用估计的可能性来预测 MCQ 的难度。我们在两个真实世界的数学 MCQ 和响应数据集上评估了我们的方法，这些数据集使用 IRT 估计了真实难度值。实验结果表明，我们的方法优于所有基线，均方误差减少了高达 28.3%，决定系数提高了 34.6%。我们还从定性角度讨论了我们的新方法如何提高对 MCQ 难度预测的准确性。

> The difficulty of multiple-choice questions (MCQs) is a crucial factor for educational assessments. Predicting MCQ difficulty is challenging since it requires understanding both the complexity of reaching the correct option and the plausibility of distractors, i.e., incorrect options. In this paper, we propose a novel, two-stage method to predict the difficulty of MCQs. First, to better estimate the complexity of each MCQ, we use large language models (LLMs) to augment the reasoning steps required to reach each option. We use not just the MCQ itself but also these reasoning steps as input to predict the difficulty. Second, to capture the plausibility of distractors, we sample knowledge levels from a distribution to account for variation among students responding to the MCQ. This setup, inspired by item response theory (IRT), enable us to estimate the likelihood of students selecting each (both correct and incorrect) option. We align these predictions with their ground truth values, using a Kullback-Leibler (KL) divergence-based regularization objective, and use estimated likelihoods to predict MCQ difficulty. We evaluate our method on two real-world \emph{math} MCQ and response datasets with ground truth difficulty values estimated using IRT. Experimental results show that our method outperforms all baselines, up to a 28.3\% reduction in mean squared error and a 34.6\% improvement in the coefficient of determination. We also qualitatively discuss how our novel method results in higher accuracy in predicting MCQ difficulty.

[Arxiv](https://arxiv.org/abs/2503.08551)