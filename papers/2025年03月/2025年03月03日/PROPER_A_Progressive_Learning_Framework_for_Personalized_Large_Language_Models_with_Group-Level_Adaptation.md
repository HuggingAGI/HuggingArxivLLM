# PROPER：面向个性化大语言模型的渐进式学习框架，支持群体级适应

发布时间：2025年03月03日

`LLM应用` `人工智能` `用户体验`

> PROPER: A Progressive Learning Framework for Personalized Large Language Models with Group-Level Adaptation

# 摘要

> 个性化大型语言模型（LLMs）旨在根据用户的偏好调整输出。最近，参数高效的微调（PEFT）方法的进展突显了通过利用用户历史数据微调用户特定参数，将群体级别的LLMs转化为个性化LLMs的有效性。然而，用户数据通常较为稀疏，这使得将LLMs适应特定用户模式颇具挑战性。为了解决这一问题，我们提出了PROPER，一种基于社会科学中观层面理论的新型渐进式学习框架。PROPER通过基于用户偏好分组和分阶段适用来连接群体级别和用户级别模型。它融合了专家混合（MoE）结构和低秩适配（LoRA），并采用用户感知路由自动将用户分配到合适的组。此外，我们还提出了一种LoRA感知路由，以促进个体用户LoRA与组级别LoRA的集成。实验结果表明，PROPER在多个任务中显著优于现有最优模型，证明了我们方法的有效性。

> Personalized large language models (LLMs) aim to tailor their outputs to user preferences. Recent advances in parameter-efficient fine-tuning (PEFT) methods have highlighted the effectiveness of adapting population-level LLMs to personalized LLMs by fine-tuning user-specific parameters with user history. However, user data is typically sparse, making it challenging to adapt LLMs to specific user patterns. To address this challenge, we propose PROgressive PERsonalization (PROPER), a novel progressive learning framework inspired by meso-level theory in social science. PROPER bridges population-level and user-level models by grouping users based on preferences and adapting LLMs in stages. It combines a Mixture-of-Experts (MoE) structure with Low Ranked Adaptation (LoRA), using a user-aware router to assign users to appropriate groups automatically. Additionally, a LoRA-aware router is proposed to facilitate the integration of individual user LoRAs with group-level LoRAs. Experimental results show that PROPER significantly outperforms SOTA models across multiple tasks, demonstrating the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2503.01303)