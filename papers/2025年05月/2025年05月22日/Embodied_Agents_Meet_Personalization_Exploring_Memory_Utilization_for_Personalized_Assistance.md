# 具身智能体与个性化相遇：探索记忆在个性化服务中的应用

发布时间：2025年05月22日

`Agent` `智能家居` `个性化服务`

> Embodied Agents Meet Personalization: Exploring Memory Utilization for Personalized Assistance

# 摘要

> 由大型语言模型（LLMs）驱动的具身智能体在家庭物品重新排列任务中表现出色。然而，这些任务主要集中在单轮交互和简化的指令上，无法真正反映为用户提供有意义帮助的复杂性。为了实现个性化的帮助，具身智能体需要通过利用过去的交互历史来理解用户对物理世界赋予的独特语义（如最喜欢的杯子、早餐习惯），从而准确解释动态的、现实世界的指令。然而，具身智能体在利用记忆提供个性化帮助方面的有效性仍鲜有研究。为了解决这一空白，我们提出了MEMENTO，这是一个个性化的具身智能体评估框架，旨在全面评估利用记忆的能力，以提供个性化的帮助。我们的框架包含一个两阶段的记忆评估过程设计，能够量化记忆利用对任务性能的影响。这一过程通过关注其在目标解释中的作用，使我们能够评估智能体在物体重新排列任务中对个性化知识的理解：（1）根据个人意义（物体语义）识别目标物体的能力，以及（2）从一致的用户模式（如习惯）中推断物体-位置配置的能力。我们对各种LLMs的实验揭示了记忆利用方面的重大限制，即使是像GPT-4o这样的前沿模型，在需要参考多个记忆时，性能也会下降30.5%，特别是在涉及用户模式的任务中。这些发现，连同我们的详细分析和案例研究，为未来开发更有效的个性化具身智能体提供了宝贵的见解。项目网站：https://connoriginal.github.io/MEMENTO

> Embodied agents empowered by large language models (LLMs) have shown strong performance in household object rearrangement tasks. However, these tasks primarily focus on single-turn interactions with simplified instructions, which do not truly reflect the challenges of providing meaningful assistance to users. To provide personalized assistance, embodied agents must understand the unique semantics that users assign to the physical world (e.g., favorite cup, breakfast routine) by leveraging prior interaction history to interpret dynamic, real-world instructions. Yet, the effectiveness of embodied agents in utilizing memory for personalized assistance remains largely underexplored. To address this gap, we present MEMENTO, a personalized embodied agent evaluation framework designed to comprehensively assess memory utilization capabilities to provide personalized assistance. Our framework consists of a two-stage memory evaluation process design that enables quantifying the impact of memory utilization on task performance. This process enables the evaluation of agents' understanding of personalized knowledge in object rearrangement tasks by focusing on its role in goal interpretation: (1) the ability to identify target objects based on personal meaning (object semantics), and (2) the ability to infer object-location configurations from consistent user patterns, such as routines (user patterns). Our experiments across various LLMs reveal significant limitations in memory utilization, with even frontier models like GPT-4o experiencing a 30.5% performance drop when required to reference multiple memories, particularly in tasks involving user patterns. These findings, along with our detailed analyses and case studies, provide valuable insights for future research in developing more effective personalized embodied agents. Project website: https://connoriginal.github.io/MEMENTO

[Arxiv](https://arxiv.org/abs/2505.16348)