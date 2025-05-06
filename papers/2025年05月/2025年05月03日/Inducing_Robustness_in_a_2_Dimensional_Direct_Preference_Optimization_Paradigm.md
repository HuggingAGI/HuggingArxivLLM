# 在二维直接偏好优化范式中培养鲁棒性

发布时间：2025年05月03日

`LLM理论` `人工智能` `偏好对齐`

> Inducing Robustness in a 2 Dimensional Direct Preference Optimization Paradigm

# 摘要

> 直接偏好优化（DPO）作为一种强大的方法，使大型语言模型（LLMs）与人类偏好对齐，提供了一种比通过人类反馈进行强化学习更稳定和高效的替代方案。在本研究中，我们利用开源的偏好数据集来评估DPO的表现。然而，DPO的主要缺点是没有精细的评分机制，而是对所有响应段落一视同仁。实际上，人类偏好并非如此，因为即使是“好”的响应也可能存在某些段落不被标注者所偏好。为了解决这一问题，我们提出了一个名为2D-DPO的二维评分方法，用于DPO对齐。我们通过比较胜率来探索2D-DPO对齐范式及其相较于标准DPO的优势。观察发现，尽管这些方法有效，但它们对标签/评分噪声不够鲁棒。为了应对这一问题，我们提出了一种将段落级别评分噪声鲁棒性融入2D-DPO算法的方法。除了理论支持外，我们还提供了实证验证来支持该算法，并引入了其他可能存在的噪声模型。

> Direct Preference Optimisation (DPO) has emerged as a powerful method for aligning Large Language Models (LLMs) with human preferences, offering a stable and efficient alternative to approaches that use Reinforcement learning via Human Feedback. In this work, we investigate the performance of DPO using open-source preference datasets. One of the major drawbacks of DPO is that it doesn't induce granular scoring and treats all the segments of the responses with equal propensity. However, this is not practically true for human preferences since even "good" responses have segments that may not be preferred by the annotator. To resolve this, a 2-dimensional scoring for DPO alignment called 2D-DPO was proposed. We explore the 2D-DPO alignment paradigm and the advantages it provides over the standard DPO by comparing their win rates. It is observed that these methods, even though effective, are not robust to label/score noise. To counter this, we propose an approach of incorporating segment-level score noise robustness to the 2D-DPO algorithm. Along with theoretical backing, we also provide empirical verification in favour of the algorithm and introduce other noise models that can be present.

[Arxiv](https://arxiv.org/abs/2505.01706)