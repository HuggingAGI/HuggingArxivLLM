# 通过对比学习个人偏好，实现个性化LLM解码

发布时间：2025年06月13日

`LLM应用` `人工智能`

> Personalized LLM Decoding via Contrasting Personal Preference

# 摘要

> 随着大型语言模型（LLMs）在实际应用中的逐步推广，个性化需求日益凸显。尽管基于提示词和训练的方法等个性化方案已被广泛探索，但解码时算法的研发仍被忽视，尽管其潜力显著。本文提出了一种创新方法CoPe（对比个人偏好），该方法在用户特定数据的参数高效微调（PEFT）后应用。我们的核心思路是通过最大化用户的隐式奖励信号，利用奖励引导解码实现个性化。我们在五个开放式的个性化文本生成任务中对CoPe进行了评估，结果显示其表现出色，使个性化在ROUGE-L指标上平均提升了10.57%，且无需外部奖励模型或额外训练流程。

> As large language models (LLMs) are progressively deployed in various real-world applications, personalization of LLMs has become increasingly important. While various approaches to LLM personalization such as prompt-based and training-based methods have been actively explored, the development of effective decoding-time algorithms remains largely overlooked, despite their demonstrated potential. In this paper, we propose CoPe (Contrasting Personal Preference), a novel decoding-time approach applied after performing parameter-efficient fine-tuning (PEFT) on user-specific data. Our core idea is to leverage reward-guided decoding specifically for personalization by maximizing each user's implicit reward signal. We evaluate CoPe across five open-ended personalized text generation tasks. Our empirical results demonstrate that CoPe achieves strong performance, improving personalization by an average of 10.57% in ROUGE-L, without relying on external reward models or additional training procedures.

[Arxiv](https://arxiv.org/abs/2506.12109)