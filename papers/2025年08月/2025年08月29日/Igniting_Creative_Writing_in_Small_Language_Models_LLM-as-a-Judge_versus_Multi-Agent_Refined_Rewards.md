# 激发小型语言模型的创意写作：LLM评判者与多智能体优化奖励的对比

发布时间：2025年08月29日

`强化学习` `媒体与娱乐`

> Igniting Creative Writing in Small Language Models: LLM-as-a-Judge versus Multi-Agent Refined Rewards

# 摘要

> 大型语言模型（LLMs）虽已展现出卓越的创意写作能力，但其高昂的计算成本却限制了广泛应用。增强小型语言模型（SLMs）成为一种颇具前景的替代方案，但现有方法如监督微调（SFT）难以突破新颖性瓶颈，而人类反馈强化学习（RLHF）又成本不菲。本文在AI反馈强化学习（RLAIF）框架下，提出了两种独特的AI驱动奖励策略，旨在激发70亿参数SLM的创意写作潜能，尤其聚焦中文问候语生成任务。第一种策略采用了基于高质量偏好数据训练的奖励模型（RM），这些数据由为创意任务量身打造的新型多智能体拒绝采样框架精心构建。第二种更创新的策略则采用原则引导的LLM评判模型（LLM-as-a-Judge），其奖励函数通过融合反思机制的对抗训练方案进行优化，以直接提供奖励信号。综合实验表明，两种方法的生成效果均显著优于基线模型，其中原则引导的LLM评判模型更是表现突出，生成质量更胜一筹。此外，该策略在训练效率和降低人工标注数据依赖方面优势显著，为构建创意SLMs开辟了一条更具扩展性和实用性的道路。我们的自动评估方法也与人类判断高度吻合。相关代码和数据已公开于https://github.com/weixiaolong94-hub/Igniting-Creative-Writing-in-Small-Language-Models。

> Large Language Models (LLMs) have demonstrated remarkable creative writing capabilities, yet their substantial computational demands hinder widespread use. Enhancing Small Language Models (SLMs) offers a promising alternative, but current methods like Supervised Fine-Tuning (SFT) struggle with novelty, and Reinforcement Learning from Human Feedback (RLHF) is costly. This paper explores two distinct AI-driven reward strategies within a Reinforcement Learning from AI Feedback (RLAIF) framework to ignite the creative writing of a 7B-parameter SLM, specifically for generating Chinese greetings. The first strategy employs a RM trained on high-quality preference data curated by a novel multi-agent rejection sampling framework designed for creative tasks. The second, more novel strategy utilizes a principle-guided LLM-as-a-Judge, whose reward function is optimized via an adversarial training scheme with a reflection mechanism, to directly provide reward signals. Comprehensive experiments reveal that while both approaches significantly enhance creative output over baselines, the principle-guided LLM-as-a-Judge demonstrably yields superior generation quality. Furthermore, it offers notable advantages in training efficiency and reduced dependency on human-annotated data, presenting a more scalable and effective path towards creative SLMs. Our automated evaluation methods also exhibit strong alignment with human judgments. Our code and data are publicly available at https://github.com/weixiaolong94-hub/Igniting-Creative-Writing-in-Small-Language-Models.

[Arxiv](https://arxiv.org/abs/2508.21476)