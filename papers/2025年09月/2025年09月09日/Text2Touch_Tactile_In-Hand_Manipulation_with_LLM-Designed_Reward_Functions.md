# Text2Touch：基于LLM设计奖励函数的触觉手持操作

发布时间：2025年09月09日

`LLM应用` `工业与制造`

> Text2Touch: Tactile In-Hand Manipulation with LLM-Designed Reward Functions

# 摘要

> 大型语言模型（LLMs）已开始助力灵巧操作的奖励设计自动化，但此前研究均未纳入触觉传感——这种感知方式对实现类人灵巧性至关重要。为此，我们提出Text2Touch方法，将LLM生成的奖励机制引入多轴手中物体旋转这一高难度任务：该任务需在现实场景中结合基于视觉的触觉传感，并支持掌心向上与掌心向下两种握持姿态。我们的提示工程策略可扩展至70多个环境变量，而模拟到现实的蒸馏技术则成功实现了策略向具备触觉功能的全驱动四指灵巧机器人手的迁移。实验表明，Text2Touch显著优于精心调优的人工设计基线，不仅旋转速度更快、操作更稳定，其奖励函数的长度和复杂度还降低了一个数量级。这些结果证实，LLM设计的奖励机制能大幅缩短从概念构思到可部署灵巧触觉技能的研发周期，为更高效、更具扩展性的多模态机器人学习提供了有力支持。项目网站：https://hpfield.github.io/text2touch-website

> Large language models (LLMs) are beginning to automate reward design for dexterous manipulation. However, no prior work has considered tactile sensing, which is known to be critical for human-like dexterity. We present Text2Touch, bringing LLM-crafted rewards to the challenging task of multi-axis in-hand object rotation with real-world vision based tactile sensing in palm-up and palm-down configurations. Our prompt engineering strategy scales to over 70 environment variables, and sim-to-real distillation enables successful policy transfer to a tactile-enabled fully actuated four-fingered dexterous robot hand. Text2Touch significantly outperforms a carefully tuned human-engineered baseline, demonstrating superior rotation speed and stability while relying on reward functions that are an order of magnitude shorter and simpler. These results illustrate how LLM-designed rewards can significantly reduce the time from concept to deployable dexterous tactile skills, supporting more rapid and scalable multimodal robot learning. Project website: https://hpfield.github.io/text2touch-website

[Arxiv](https://arxiv.org/abs/2509.07445)