# 恢复对齐大型语言模型的校准：一种校准感知的微调方法

发布时间：2025年05月04日

`LLM理论` `人工智能`

> Restoring Calibration for Aligned Large Language Models: A Calibration-Aware Fine-Tuning Approach

# 摘要

> 偏好对齐是大型语言模型（LLMs）成功的核心技术之一，但其显著副作用是较差的校准效果。虽然预训练模型通常具有良好校准，但LLMs在与人类偏好对齐后往往会变得校准不良。本文探讨了偏好对齐如何影响校准，并提出了解决方案。我们发现，偏好坍塌问题在对齐过程中会不 desirable地泛化到校准场景，导致LLMs过度自信和校准不良。为此，我们强调使用领域特定知识进行微调的重要性，以缓解过度自信问题。为了分析这对模型性能的影响，我们将模型分为可校准和不可校准两类，分别由预期校准误差（ECE）的上下限定义。在可校准范围内，我们提出了一种感知校准的微调方法，确保LLMs性能不受影响的同时实现适当校准。然而，随着模型进一步微调以提升性能，它们进入不可校准范围。针对这种情况，我们开发了一种基于EM算法的ECE正则化方法，用于微调损失函数，以保持较低的校准误差。实验结果验证了所提出方法的有效性。

> One of the key technologies for the success of Large Language Models (LLMs) is preference alignment. However, a notable side effect of preference alignment is poor calibration: while the pre-trained models are typically well-calibrated, LLMs tend to become poorly calibrated after alignment with human preferences. In this paper, we investigate why preference alignment affects calibration and how to address this issue. For the first question, we observe that the preference collapse issue in alignment undesirably generalizes to the calibration scenario, causing LLMs to exhibit overconfidence and poor calibration. To address this, we demonstrate the importance of fine-tuning with domain-specific knowledge to alleviate the overconfidence issue. To further analyze whether this affects the model's performance, we categorize models into two regimes: calibratable and non-calibratable, defined by bounds of Expected Calibration Error (ECE). In the calibratable regime, we propose a calibration-aware fine-tuning approach to achieve proper calibration without compromising LLMs' performance. However, as models are further fine-tuned for better performance, they enter the non-calibratable regime. For this case, we develop an EM-algorithm-based ECE regularization for the fine-tuning loss to maintain low calibration error. Extensive experiments validate the effectiveness of the proposed methods.

[Arxiv](https://arxiv.org/abs/2505.01997)