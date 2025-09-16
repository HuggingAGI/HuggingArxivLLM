# RadarLLM：结合偏好感知损失适配预训练大语言模型的船用雷达目标检测

发布时间：2025年09月15日

`LLM应用` `交通运输`

> RadarLLM: Adapting Pretrained Large Language Models for Marine Radar Target Detection with Preference-aware Loss

# 摘要

> 预训练大型语言模型（LLMs）的最新进展展现出其捕捉通用知识的强大能力，这使它们有望成为无线信号处理领域的通用优化求解器。受此启发，我们率先尝试微调预训练LLMs，以有效分析海洋目标检测任务中的雷达信号特征。然而，直接将预训练LLMs应用于海洋目标检测任务的微调往往会出现明显的过拟合问题，尤其在低信杂比（SCR）这类挑战性场景中。这种过拟合主要是因为模型倾向于记忆虚假或嘈杂的特征模式，而非学习具有良好泛化能力的判别性结构，无法很好地适应未见数据。为解决这一难题，我们提出了RadarLLM——一种新颖的微调框架，其核心在于采用有效的偏好感知损失函数。与传统训练策略中统一优化所有特征标记不同，该损失函数会根据各特征块的在线评估学习值进行选择性优化，从而引导模型在训练过程中专注于最具泛化性的模式。我们通过将问题转化为有用特征标记的选择问题，从理论上证明了评估学习值的有效性。在真实海洋雷达数据集上的大量实验结果表明：1) 所提损失函数显著优于原始损失函数，尤其在低SCR场景中增益明显；2) RadarLLM在各类检测场景中均持续超越现有最优基线，且在训练数据有限的情况下优势更为突出。

> Recent advances in pre-trained large language models (LLMs) have demonstrated their capacities to capture universal knowledge, making them promising general-purpose optimization solvers for wireless signal processing. Motivated by these findings, we take the first step towards fine-tuning pre-trained LLMs for the effective analysis of radar signal features in marine target detection tasks. Nevertheless, directly fine-tuning pre-trained LLMs on marine target detection tasks tends to suffer from pronounced overfitting, particularly in challenging low signal-to-clutter ratio (SCR) scenarios. This overfitting primarily stems from the model's tendency to memorize spurious or noisy feature patterns rather than learning discriminative structures that generalize well to unseen data. To address this challenge, we introduce RadarLLM, a novel fine-tuning framework that utilizes an effective preference-aware loss. Unlike conventional training strategies that uniformly optimize all feature tokens, this loss function selectively optimizes different feature patches based on their online evaluated learning values, thus guiding the model to focus on the most generalizable patterns during optimization. We theoretically demonstrate the effectiveness of the evaluated learning values by transforming the problem as selecting useful feature tokens. Extensive experiments on real-world marine radar datasets show that 1) the proposed loss function is much better than the original one, with particularly significant gains in challenging low SCR scenarios and 2) RadarLLM consistently outperforms state-of-the-art baselines across diverse detection scenarios, with particularly notable gains under limited training data conditions.

[Arxiv](https://arxiv.org/abs/2509.12089)