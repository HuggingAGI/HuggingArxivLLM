# CoPL：个性化大型语言模型的协同偏好学习

发布时间：2025年03月03日

`LLM应用` `个性化` `用户反馈`

> CoPL: Collaborative Preference Learning for Personalizing LLMs

# 摘要

> 个性化大型语言模型（LLMs）对于满足多样化的用户需求至关重要，但现有方法在灵活性和泛化能力上存在局限。为此，我们提出了CoPL（协作偏好学习），这是一种基于图的协作过滤框架，通过建模用户响应关系来增强偏好估计，尤其在稀疏标注场景下表现突出。通过整合LoRA专家的混合，CoPL能够高效微调LLMs，同时动态平衡共享偏好与用户特定偏好。此外，CoPL还提供了一种无需优化的自适应策略，使其无需微调即可泛化到未见用户。在UltraFeedback-P上的实验表明，CoPL超越了现有的个性化奖励模型，能够有效捕捉常见和有争议的偏好，为个性化LLM对齐提供了一个可扩展的解决方案。

> Personalizing large language models (LLMs) is important for aligning outputs with diverse user preferences, yet existing methods struggle with flexibility and generalization. We propose CoPL (Collaborative Preference Learning), a graph-based collaborative filtering framework that models user-response relationships to enhance preference estimation, particularly in sparse annotation settings. By integrating a mixture of LoRA experts, CoPL efficiently fine-tunes LLMs while dynamically balancing shared and user-specific preferences. Additionally, an optimization-free adaptation strategy enables generalization to unseen users without fine-tuning. Experiments on UltraFeedback-P demonstrate that CoPL outperforms existing personalized reward models, effectively capturing both common and controversial preferences, making it a scalable solution for personalized LLM alignment.

[Arxiv](https://arxiv.org/abs/2503.01658)