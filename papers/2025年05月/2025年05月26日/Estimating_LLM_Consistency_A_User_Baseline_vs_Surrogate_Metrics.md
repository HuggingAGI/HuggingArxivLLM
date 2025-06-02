# 评估 LLM 一致性：用户基准与替代指标对比

发布时间：2025年05月26日

`LLM理论` `用户体验`

> Estimating LLM Consistency: A User Baseline vs Surrogate Metrics

# 摘要

> 大型语言模型 (LLMs) 容易产生幻觉且对提示微扰敏感，常导致生成文本不一致或不可靠。为缓解这些问题，研究人员提出了多种方法，其中一种是测量 LLM 响应的一致性。然而，现有方法在多大程度上能准确反映人类对 LLM 响应一致性的感知尚不明确。我们进行了一项用户研究（n=2,976），发现当前方法在近似用户对 LLM 一致性的感知方面表现不佳。为此，我们提出了一种基于 logits 的集成方法来估计 LLM 的一致性。实验表明，该方法在估计人类对 LLM 一致性的评分方面与现有最佳指标相当。我们的研究结果表明，不依赖人工评估的 LLM 一致性估计方法存在诸多不足，因此建议更广泛地采用包含人工输入的评估方法。

> Large language models (LLMs) are prone to hallucinations and sensitive to prompt perturbations, often resulting in inconsistent or unreliable generated text. Different methods have been proposed to mitigate such hallucinations and fragility -- one of them being measuring the consistency (the model's confidence in the response, or likelihood of generating a similar response when resampled) of LLM responses. In previous work, measuring consistency often relied on the probability of a response appearing within a pool of resampled responses, or internal states or logits of responses. However, it is not yet clear how well these approaches approximate how humans perceive the consistency of LLM responses. We performed a user study (n=2,976) and found current methods typically do not approximate users' perceptions of LLM consistency very well. We propose a logit-based ensemble method for estimating LLM consistency, and we show that this method matches the performance of the best-performing existing metric in estimating human ratings of LLM consistency. Our results suggest that methods of estimating LLM consistency without human evaluation are sufficiently imperfect that we suggest evaluation with human input be more broadly used.

[Arxiv](https://arxiv.org/abs/2505.23799)