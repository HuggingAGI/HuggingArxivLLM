# 超越奖励黑客：因果奖励助力大型语言模型对齐

发布时间：2025年01月16日

`LLM理论

理由：这篇论文主要讨论了如何通过因果推断来改进大型语言模型（LLMs）的奖励建模，以消除虚假相关性并提高模型与人类偏好的对齐。这涉及到对LLM训练和微调的理论改进，属于对LLM理论的研究。` `人工智能` `因果推断`

> Beyond Reward Hacking: Causal Rewards for Large Language Model Alignment

# 摘要

> # 摘要
最近大型语言模型（LLMs）的进展在执行复杂任务方面取得了显著突破。尽管基于人类反馈的强化学习（RLHF）在使LLMs与人类偏好对齐方面表现出色，但它容易受到奖励建模中虚假相关性的干扰，导致模型引入诸如长度偏见、谄媚、概念偏见和歧视等问题，阻碍了模型捕捉真实因果关系的能力。为此，我们提出了一种全新的因果奖励建模方法，通过整合因果推断来消除这些虚假相关性。该方法通过强制反事实不变性，确保在无关变量变化时奖励预测保持一致。我们在合成和真实数据集上的实验表明，该方法有效减轻了多种虚假相关性，使LLMs与人类偏好的对齐更加可靠和公平。作为对现有RLHF工作流程的直接增强，因果奖励建模为提升LLM微调的可信度和公平性提供了一种实用途径。

> Recent advances in large language models (LLMs) have demonstrated significant progress in performing complex tasks. While Reinforcement Learning from Human Feedback (RLHF) has been effective in aligning LLMs with human preferences, it is susceptible to spurious correlations in reward modeling. Consequently, it often introduces biases-such as length bias, sycophancy, conceptual bias, and discrimination that hinder the model's ability to capture true causal relationships. To address this, we propose a novel causal reward modeling approach that integrates causal inference to mitigate these spurious correlations. Our method enforces counterfactual invariance, ensuring reward predictions remain consistent when irrelevant variables are altered. Through experiments on both synthetic and real-world datasets, we show that our approach mitigates various types of spurious correlations effectively, resulting in more reliable and fair alignment of LLMs with human preferences. As a drop-in enhancement to the existing RLHF workflow, our causal reward modeling provides a practical way to improve the trustworthiness and fairness of LLM finetuning.

[Arxiv](https://arxiv.org/abs/2501.09620)