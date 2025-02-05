# 基于深思熟虑用户偏好对齐的推荐系统大型语言模型

发布时间：2025年02月04日

`LLM应用

理由：该论文摘要讨论了在推荐任务中使用大型语言模型（LLMs）的挑战，并提出了一种新的深思熟虑推荐任务框架，旨在通过增强推理能力来改进用户偏好对齐。这涉及到LLMs在实际应用中的改进和优化，因此属于“LLM应用”类别。` `推荐系统` `用户行为分析`

> Large Language Models for Recommendation with Deliberative User Preference Alignment

# 摘要

> 尽管LLMs在推荐任务中的对齐进展显著，但在复杂场景中仍面临挑战。现有方法主要依赖LLMs直接生成用户反馈，缺乏深思熟虑。为此，我们提出了一种新的深思熟虑推荐任务，将用户偏好推理作为额外对齐目标，并设计了深思熟虑用户偏好对齐框架。该框架通过逐步利用口头反馈增强推理能力，采用协作专家和定制训练策略。实验结果表明，该框架在提升预测准确性和推理质量方面表现卓越。

> While recent advancements in aligning Large Language Models (LLMs) with recommendation tasks have shown great potential and promising performance overall, these aligned recommendation LLMs still face challenges in complex scenarios. This is primarily due to the current alignment approach focusing on optimizing LLMs to generate user feedback directly, without incorporating deliberation. To overcome this limitation and develop more reliable LLMs for recommendations, we propose a new Deliberative Recommendation task, which incorporates explicit reasoning about user preferences as an additional alignment goal. We then introduce the Deliberative User Preference Alignment framework, designed to enhance reasoning capabilities by utilizing verbalized user feedback in a step-wise manner to tackle this task. The framework employs collaborative step-wise experts and tailored training strategies for each expert. Experimental results across three real-world datasets demonstrate the rationality of the deliberative task formulation and the superior performance of the proposed framework in improving both prediction accuracy and reasoning quality.

[Arxiv](https://arxiv.org/abs/2502.02061)