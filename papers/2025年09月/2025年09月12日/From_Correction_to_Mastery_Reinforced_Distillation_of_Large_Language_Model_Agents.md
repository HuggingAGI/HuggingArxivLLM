# 从纠错到精通：大型语言模型智能体的强化蒸馏

发布时间：2025年09月12日

`Agent` `基础理论`

> From Correction to Mastery: Reinforced Distillation of Large Language Model Agents

# 摘要

> 大型语言模型智能体凭借迭代推理与工具调用能力，在复杂任务中表现出色，但其性能往往依赖超大规模、高成本的骨干模型。现有的蒸馏方法通常让小型学生模型模仿教师模型的完整推理轨迹，然而师生间的推理能力与知识储备差距常导致错误不断累积。为此，我们提出SCoRe——一个以学生模型为核心的框架：学生自主生成推理轨迹，教师仅在首次出现关键错误时介入，从而生成与学生能力适配的训练数据，并精准定位其薄弱环节。学生模型首先在修正后的轨迹数据上完成微调，接着短视域强化学习从首次关键错误前的已验证前缀启动，并在该节点设定目标奖励。该设计不仅能激励模型跳出单纯模仿，实现自主解题，还能提升训练稳定性。在12项高难度基准测试中，经SCoRe蒸馏的70亿参数学生模型，其智能体性能甚至可媲美720亿参数的教师模型。

> Large Language Model agents excel at solving complex tasks through iterative reasoning and tool use, but typically depend on ultra-large, costly backbones. Existing distillation approaches train smaller students to imitate full teacher trajectories, yet reasoning and knowledge gaps between the teacher and student often lead to compounding errors. We propose SCoRe, a student-centered framework in which the student generates trajectories and the teacher intervenes only at the first critical error, producing training data matched to the student's ability and exposing specific weaknesses. The student is first fine-tuned on corrected trajectories. Subsequently, short-horizon reinforcement learning starts from the verified prefix before the first critical error, with target rewards assigned at that step. This design encourages autonomous problem-solving beyond imitation and improves training stability. Particularly, on 12 challenging benchmarks, a 7B-parameter student distilled with SCoRe matches the agentic performance of a 72B-parameter teacher.

[Arxiv](https://arxiv.org/abs/2509.14257)