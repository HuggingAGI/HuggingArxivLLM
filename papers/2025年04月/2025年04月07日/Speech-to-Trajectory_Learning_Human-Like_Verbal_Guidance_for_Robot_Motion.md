# 语音轨迹：学习类人语言指引方法应用于机器人运动控制

发布时间：2025年04月07日

`Agent` `机器人`

> Speech-to-Trajectory: Learning Human-Like Verbal Guidance for Robot Motion

# 摘要

> 要将机器人真正融入实际应用，它们需要能够理解和执行未经训练的用户发出的自然语言指令。由于人类语言的变异性，相同的指令可能用不同的方式表达，但机器人仍需保持一致的行为。尽管大型语言模型（LLMs）在语言理解方面取得了进展，但它们在处理用户表达的变异性方面表现欠佳，往往依赖预定义命令，并且输出结果不可预测。本文介绍了一种全新的语音到轨迹框架——指令语言模型（DLM），它能够直接将口头指令映射为可执行的运动轨迹，无需依赖预定义短语。DLM通过行为克隆（BC）在人类引导的机器人运动模拟演示中进行学习。为了增强泛化能力，基于GPT的语义增强生成多样化的训练指令改写，并标注相同的运动轨迹。DLM还集成了基于扩散策略的轨迹生成方法，用于自适应运动优化和随机采样。与基于LLM的方法相比，DLM无需大量提示工程，即可确保一致且可预测的运动行为，从而实现对机器人实时指导。由于DLM通过轨迹数据进行学习，它具有平台无关性，能够在各种机器人平台上部署。实验结果表明，DLM在指令泛化、减少对结构化表达的依赖以及实现类人运动方面均取得了显著成效。

> Full integration of robots into real-life applications necessitates their ability to interpret and execute natural language directives from untrained users. Given the inherent variability in human language, equivalent directives may be phrased differently, yet require consistent robot behavior. While Large Language Models (LLMs) have advanced language understanding, they often falter in handling user phrasing variability, rely on predefined commands, and exhibit unpredictable outputs. This letter introduces the Directive Language Model (DLM), a novel speech-to-trajectory framework that directly maps verbal commands to executable motion trajectories, bypassing predefined phrases. DLM utilizes Behavior Cloning (BC) on simulated demonstrations of human-guided robot motion. To enhance generalization, GPT-based semantic augmentation generates diverse paraphrases of training commands, labeled with the same motion trajectory. DLM further incorporates a diffusion policy-based trajectory generation for adaptive motion refinement and stochastic sampling. In contrast to LLM-based methods, DLM ensures consistent, predictable motion without extensive prompt engineering, facilitating real-time robotic guidance. As DLM learns from trajectory data, it is embodiment-agnostic, enabling deployment across diverse robotic platforms. Experimental results demonstrate DLM's improved command generalization, reduced dependence on structured phrasing, and achievement of human-like motion.

[Arxiv](https://arxiv.org/abs/2504.05084)