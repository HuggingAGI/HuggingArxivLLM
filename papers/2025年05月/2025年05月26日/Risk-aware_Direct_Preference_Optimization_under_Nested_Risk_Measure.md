# 基于嵌套风险度量的直接偏好优化研究

发布时间：2025年05月26日

`LLM理论

摘要讨论了优化大型语言模型（LLM）的对齐性能和风险控制，提出了一种新的优化方法Ra-DPO，属于理论层面的创新。` `人工智能伦理`

> Risk-aware Direct Preference Optimization under Nested Risk Measure

# 摘要

> 在对预训练大型语言模型 (LLMs) 进行微调以匹配人类价值观时，最大化估计奖励虽能提升性能，却可能因偏离参考模型行为而带来风险。现有方法通常采用 KL 散度控制偏差，但在严格风险控制场景下效果有限。本文提出风险感知的直接偏好优化 (Ra-DPO)，通过嵌套风险度量引入风险意识。该方法将问题转化为带约束的风险感知优势函数最大化，并将 Bradley-Terry 模型转化为 token 级表示。通过序列风险比率，目标函数在最大化策略似然的同时抑制模型偏差，提升风险感知能力。在 IMDb、Anthropic HH 和 AlpacaEval 数据集上的实验表明，Ra-DPO 在平衡对齐性能与模型漂移方面表现优异。代码已开源，地址为 https://github.com/zlj123-max/Ra-DPO。


> When fine-tuning pre-trained Large Language Models (LLMs) to align with human values and intentions, maximizing the estimated reward can lead to superior performance, but it also introduces potential risks due to deviations from the reference model's intended behavior. Most existing methods typically introduce KL divergence to constrain deviations between the trained model and the reference model; however, this may not be sufficient in certain applications that require tight risk control. In this paper, we introduce Risk-aware Direct Preference Optimization (Ra-DPO), a novel approach that incorporates risk-awareness by employing a class of nested risk measures. This approach formulates a constrained risk-aware advantage function maximization problem and then converts the Bradley-Terry model into a token-level representation. The objective function maximizes the likelihood of the policy while suppressing the deviation between a trained model and the reference model using a sequential risk ratio, thereby enhancing the model's risk-awareness. Experimental results across three open-source datasets: IMDb Dataset, Anthropic HH Dataset, and AlpacaEval, demonstrate the proposed method's superior performance in balancing alignment performance and model drift. Our code is opensourced at https://github.com/zlj123-max/Ra-DPO.

[Arxiv](https://arxiv.org/abs/2505.20359)