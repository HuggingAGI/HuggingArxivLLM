# SleepCoT: 基于思维链蒸馏的轻量级个性化睡眠健康模型

发布时间：2024年10月22日

`LLM应用

理由：这篇论文主要讨论了如何通过少样本思维链（CoT）蒸馏的方法，将大型语言模型（LLMs）的能力转移到小型语言模型中，以应用于个性化睡眠健康管理。该方法涉及从大模型中蒸馏出问题解决策略、长尾专家知识和个性化推荐能力，并将其转化为更高效、紧凑的模型。论文还展示了该方法在生成个性化睡眠建议、支持用户特定后续查询和回答领域特定知识问题方面的应用。因此，这篇论文属于LLM应用类别，因为它专注于将LLM技术应用于具体的健康管理场景。` `健康管理`

> SleepCoT: A Lightweight Personalized Sleep Health Model via Chain-of-Thought Distillation

# 摘要

> 我们提出了一种基于少样本思维链（CoT）蒸馏的个性化睡眠健康管理新方法，使小型语言模型（> 2B参数）在专业健康领域能与大型语言模型（LLMs）媲美。该方法从大模型中蒸馏出问题解决策略、长尾专家知识和个性化推荐能力，转化为更高效、紧凑的模型。与现有系统不同，我们的方法具备三大功能：生成个性化睡眠建议、支持用户特定后续查询、回答领域特定知识问题。我们选择睡眠健康作为研究重点，因其可通过可穿戴设备量化，且对整体健康影响显著。实验采用GPT-4o合成数据、Qwen-max创建指令集、Qwen2.5 1.5B进行模型蒸馏，结果显示在惩罚、推理和知识应用方面，模型性能显著优于基线小型模型。基于100份模拟睡眠报告和1,000个领域问题的实验表明，我们的模型在保持实际部署效率的同时，性能与大型模型相当。这项研究不仅推动了AI驱动的健康管理，还为资源受限环境提供了利用LLM能力的新途径，有望提升个性化医疗解决方案的可及性。

> We present a novel approach to personalized sleep health management using few-shot Chain-of-Thought (CoT) distillation, enabling small-scale language models (> 2B parameters) to rival the performance of large language models (LLMs) in specialized health domains. Our method simultaneously distills problem-solving strategies, long-tail expert knowledge, and personalized recommendation capabilities from larger models into more efficient, compact models. Unlike existing systems, our approach offers three key functionalities: generating personalized sleep health recommendations, supporting user-specific follow-up inquiries, and providing responses to domain-specific knowledge questions. We focus on sleep health due to its measurability via wearable devices and its impact on overall well-being. Our experimental setup, involving GPT-4o for data synthesis, Qwen-max for instruction set creation, and Qwen2.5 1.5B for model distillation, demonstrates significant improvements over baseline small-scale models in penalization, reasoning, and knowledge application. Experiments using 100 simulated sleep reports and 1,000 domain-specific questions shows our model achieves comparable performance to larger models while maintaining efficiency for real-world deployment. This research not only advances AI-driven health management but also provides a novel approach to leveraging LLM capabilities in resource-constrained environments, potentially enhancing the accessibility of personalized healthcare solutions.

[Arxiv](https://arxiv.org/abs/2410.16924)