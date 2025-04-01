# GenSwarm: 基于语言模型的多机器人代码策略生成与可扩展部署

发布时间：2025年03月31日

`LLM应用` `机器人` `自动化`

> GenSwarm: Scalable Multi-Robot Code-Policy Generation and Deployment via Language Models

# 摘要

> 传统上，多机器人系统的控制策略开发是一个复杂且繁琐的过程，难以灵活应对动态任务需求。这促使研究者探索自动创建控制策略的方法。然而，现有方法需要通过反复手动调整目标函数，导致开发周期延长。本研究提出了一种名为	extit{GenSwarm}的端到端系统，该系统利用大型语言模型，根据用户提供的简单自然语言指令，自动为多机器人任务生成和部署控制策略。作为多语言智能体系统，GenSwarm实现了零样本学习能力，能够快速适应新任务或未见过的任务场景。其代码策略的白盒特性确保了高可重复性和可解释性。凭借其可扩展的软硬件架构，GenSwarm支持在模拟和真实多机器人系统中高效部署策略，实现了从指令到执行的完整端到端功能，这将为机器人专家和非专家带来重要价值。GenSwarm系统的代码已开源，访问地址为：https://github.com/WindyLab/GenSwarm。

> The development of control policies for multi-robot systems traditionally follows a complex and labor-intensive process, often lacking the flexibility to adapt to dynamic tasks. This has motivated research on methods to automatically create control policies. However, these methods require iterative processes of manually crafting and refining objective functions, thereby prolonging the development cycle. This work introduces \textit{GenSwarm}, an end-to-end system that leverages large language models to automatically generate and deploy control policies for multi-robot tasks based on simple user instructions in natural language. As a multi-language-agent system, GenSwarm achieves zero-shot learning, enabling rapid adaptation to altered or unseen tasks. The white-box nature of the code policies ensures strong reproducibility and interpretability. With its scalable software and hardware architectures, GenSwarm supports efficient policy deployment on both simulated and real-world multi-robot systems, realizing an instruction-to-execution end-to-end functionality that could prove valuable for robotics specialists and non-specialists alike.The code of the proposed GenSwarm system is available online: https://github.com/WindyLab/GenSwarm.

[Arxiv](https://arxiv.org/abs/2503.23875)