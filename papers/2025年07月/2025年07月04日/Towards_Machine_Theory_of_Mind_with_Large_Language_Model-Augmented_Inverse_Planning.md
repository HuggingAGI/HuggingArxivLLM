# 迈向机器心智理论：增强逆向规划的大型语言模型

发布时间：2025年07月04日

`LLM应用` `人工智能` `认知科学`

> Towards Machine Theory of Mind with Large Language Model-Augmented Inverse Planning

# 摘要

> 我们提出了一种结合贝叶斯逆向规划模型与大型语言模型（LLMs）的混合方法，用于机器理论心灵（ToM）的研究。该方法利用LLMs生成假设和可能性函数，并通过贝叶斯逆向规划模型计算智能体行为背后的潜在心理状态概率。贝叶斯逆向规划模型在预测人类ToM任务推理方面表现出色，但其扩展性有限，难以处理复杂场景。而基于LLM的方法在解决ToM基准测试中虽有潜力，却常因推理任务的细微变化导致失败。通过融合两者优势，我们的方法在逆向规划启发的任务中达到接近最优的结果，且较之仅使用LLMs或思考链提示的方法，即使采用小型LLMs也能显著提升性能。此外，该模型在开放性任务中预测心理状态的潜力，为ToM模型的未来发展及社会智能生成智能体的创建提供了新的方向。

> We propose a hybrid approach to machine Theory of Mind (ToM) that uses large language models (LLMs) as a mechanism for generating hypotheses and likelihood functions with a Bayesian inverse planning model that computes posterior probabilities for an agent's likely mental states given its actions. Bayesian inverse planning models can accurately predict human reasoning on a variety of ToM tasks, but these models are constrained in their ability to scale these predictions to scenarios with a large number of possible hypotheses and actions. Conversely, LLM-based approaches have recently demonstrated promise in solving ToM benchmarks, but can exhibit brittleness and failures on reasoning tasks even when they pass otherwise structurally identical versions. By combining these two methods, this approach leverages the strengths of each component, closely matching optimal results on a task inspired by prior inverse planning models and improving performance relative to models that utilize LLMs alone or with chain-of-thought prompting, even with smaller LLMs that typically perform poorly on ToM tasks. We also exhibit the model's potential to predict mental states on open-ended tasks, offering a promising direction for future development of ToM models and the creation of socially intelligent generative agents.

[Arxiv](https://arxiv.org/abs/2507.03682)