# SLMEval: 基于熵的校准方法，用于对大型语言模型进行符合人类认知的评估

发布时间：2025年05月21日

`LLM理论` `评估方法`

> SLMEval: Entropy-Based Calibration for Human-Aligned Evaluation of Large Language Models

# 摘要

> LLM-as-a-Judge范式为语言模型评估提供了一种可扩展且无需参考的方案。尽管已有多种校准技术被提出，以使评估器更好地与人类判断保持一致，但现有研究主要聚焦于狭窄且结构良好的基准测试。因此，这些校准方法是否能推广到现实世界中开放性的任务仍不明朗。

在本研究中，我们发现SOTA校准评估器在这些场景下常常表现不佳，甚至与人类判断呈现出较弱或负相关。为解决这一问题，我们提出了一种基于熵最大化的新颖且高效的校准方法SLMEval，该方法仅需少量的人类偏好数据。通过估计模型质量的潜在分布并相应地调整评估器分数，SLMEval在两个实际生产应用场景和公共基准测试中均实现了与人类评估的强相关性。例如，在某项任务中，SLMEval与人类判断的Spearman相关系数达到0.57，而G-Eval则表现为负相关。此外，与基于GPT-4的校准评估器（如G-Eval）相比，SLMEval将评估成本降低了5-30倍。

> The LLM-as-a-Judge paradigm offers a scalable, reference-free approach for evaluating language models. Although several calibration techniques have been proposed to better align these evaluators with human judgment, prior studies focus primarily on narrow, well-structured benchmarks. As a result, it remains unclear whether such calibrations generalize to real-world, open-ended tasks.
  In this work, we show that SOTA calibrated evaluators often fail in these settings, exhibiting weak or even negative correlation with human judgments. To address this, we propose SLMEval, a novel and efficient calibration method based on entropy maximization over a small amount of human preference data. By estimating a latent distribution over model quality and reweighting evaluator scores accordingly, SLMEval achieves strong correlation with human evaluations across two real-world production use cases and the public benchmark. For example, on one such task, SLMEval achieves a Spearman correlation of 0.57 with human judgments, while G-Eval yields a negative correlation. In addition, SLMEval reduces evaluation costs by 5-30x compared to GPT-4-based calibrated evaluators such as G-eval.

[Arxiv](https://arxiv.org/abs/2505.16003)