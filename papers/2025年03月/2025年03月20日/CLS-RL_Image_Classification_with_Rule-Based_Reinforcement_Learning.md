# CLS-RL：通过基于规则的强化学习实现图像分类

发布时间：2025年03月20日

`LLM应用` `计算机视觉` `图像分类`

> CLS-RL: Image Classification with Rule-Based Reinforcement Learning

# 摘要

> # 分类
分类是机器学习的核心任务。研究表明，尽管多模态大语言模型（MLLMs）在图像分类任务中最初表现不佳，但通过充足的数据进行微调，可以显著提升其性能，使其达到与最先进（SOTA）分类模型相当的水平。然而，获取大规模标注数据成本高昂。本文研究了少样本 MLLM 分类微调。我们发现，标准微调（SFT）可能导致严重过拟合问题，甚至可能使性能劣于零样本方法。为解决这一挑战，受近期基于规则的强化学习成功案例启发，我们提出 CLS-RL，利用可验证信号作为奖励对 MLLMs 进行微调。我们发现，CLS-RL 在大多数数据集上优于 SFT，并且在基线到新任务和少样本学习设置下平均准确率显著更高。此外，我们观察到 CLS-RL 的免费午餐现象；当模型在特定数据集上进行微调时，即使这些数据集在分布和类别名称上存在差异，其在其他独立数据集上的性能也可能优于零样本模型。这表明，基于强化学习的方法能够有效教会模型分类的基本原理。最后，受近期关于推理时间思考的研究启发，我们重新审视了强化学习方法中微调过程中的 `思考过程'，特别是在视觉分类背景下。我们质疑此类任务是否需要在微调过程中进行大量思考，提出这可能实际上会损害性能。基于这一假设，我们引入了 No-Thinking-CLS-RL 方法，通过设置等式准确度奖励，在训练过程中尽量减少思考过程。我们的研究发现表明，No-Thinking-CLS-RL 方法在大幅减少微调时间的情况下，实现了优于 CLS-RL 的领域内性能和泛化能力。


> Classification is a core task in machine learning. Recent research has shown that although Multimodal Large Language Models (MLLMs) are initially poor at image classification, fine-tuning them with an adequate amount of data can significantly enhance their performance, making them comparable to SOTA classification models. However, acquiring large-scale labeled data is expensive. In this paper, we explore few-shot MLLM classification fine-tuning. We found that SFT can cause severe overfitting issues and may even degrade performance over the zero-shot approach. To address this challenge, inspired by the recent successes in rule-based reinforcement learning, we propose CLS-RL, which uses verifiable signals as reward to fine-tune MLLMs. We discovered that CLS-RL outperforms SFT in most datasets and has a much higher average accuracy on both base-to-new and few-shot learning setting. Moreover, we observed a free-lunch phenomenon for CLS-RL; when models are fine-tuned on a particular dataset, their performance on other distinct datasets may also improve over zero-shot models, even if those datasets differ in distribution and class names. This suggests that RL-based methods effectively teach models the fundamentals of classification. Lastly, inspired by recent works in inference time thinking, we re-examine the `thinking process' during fine-tuning, a critical aspect of RL-based methods, in the context of visual classification. We question whether such tasks require extensive thinking process during fine-tuning, proposing that this may actually detract from performance. Based on this premise, we introduce the No-Thinking-CLS-RL method, which minimizes thinking processes during training by setting an equality accuracy reward. Our findings indicate that, with much less fine-tuning time, No-Thinking-CLS-RL method achieves superior in-domain performance and generalization capabilities than CLS-RL.

[Arxiv](https://arxiv.org/abs/2503.16188)