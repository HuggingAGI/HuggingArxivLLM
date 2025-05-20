# 促进大型模型中的多模态推理，实现直接机器人操控

发布时间：2025年05月19日

`LLM应用` `机器人` `自动化`

> Incentivizing Multimodal Reasoning in Large Models for Direct Robot Manipulation

# 摘要

> # 摘要
大型多模态模型近期展现出了卓越的推理能力，尤其是在解决复杂数学问题和实现精准空间感知方面。我们的核心观点是，这些能力可以自然延伸至机器人操作领域，使 LMMs 能够通过推理直接从语言中推断下一步目标，而非依赖单独的动作头。然而，这一方法面临两大挑战：如何让 LMMs 理解空间动作空间，以及如何充分发挥其在这些任务中的推理能力。

为了解决第一个挑战，我们提出了一种创新的任务形式，该形式基于物体部件和夹爪的当前状态，并采用新的轴表示替代传统的欧拉角来重新定义旋转。这种表示方法更符合空间推理，并且在统一的语言空间中更易于解释。针对第二个挑战，我们设计了一条管道，利用先进的 LMMs 生成一个小型但高质量的推理数据集，包含多轮对话，成功解决机器人操作任务，用于监督微调。随后，我们通过在模拟环境中进行试错交互来进行强化学习，以进一步提升模型在机器人操作中的推理能力。

我们的推理模型基于 7B 模型构建，命名为 ReasonManip，凭借其系统-2 级推理能力，展现出三大显著优势：i) 对分布外环境、物体和任务的出色泛化能力；ii) 由跨域共享的统一语言表示所赋予的内在模拟到现实迁移能力；iii) 高级推理与低级控制之间清晰的可解释性连接。大量实验验证了这一范式的有效性及其在推动 LMM 驱动的机器人操作方面的潜力。


> Recent Large Multimodal Models have demonstrated remarkable reasoning capabilities, especially in solving complex mathematical problems and realizing accurate spatial perception. Our key insight is that these emerging abilities can naturally extend to robotic manipulation by enabling LMMs to directly infer the next goal in language via reasoning, rather than relying on a separate action head. However, this paradigm meets two main challenges: i) How to make LMMs understand the spatial action space, and ii) How to fully exploit the reasoning capacity of LMMs in solving these tasks. To tackle the former challenge, we propose a novel task formulation, which inputs the current states of object parts and the gripper, and reformulates rotation by a new axis representation instead of traditional Euler angles. This representation is more compatible with spatial reasoning and easier to interpret within a unified language space. For the latter challenge, we design a pipeline to utilize cutting-edge LMMs to generate a small but high-quality reasoning dataset of multi-round dialogues that successfully solve manipulation tasks for supervised fine-tuning. Then, we perform reinforcement learning by trial-and-error interactions in simulation to further enhance the model's reasoning abilities for robotic manipulation. Our resulting reasoning model built upon a 7B backbone, named ReasonManip, demonstrates three notable advantages driven by its system-2 level reasoning capabilities: i) exceptional generalizability to out-of-distribution environments, objects, and tasks; ii) inherent sim-to-real transfer ability enabled by the unified language representation shared across domains; iii) transparent interpretability connecting high-level reasoning and low-level control. Extensive experiments demonstrate the effectiveness of the proposed paradigm and its potential to advance LMM-driven robotic manipulation.

[Arxiv](https://arxiv.org/abs/2505.12744)