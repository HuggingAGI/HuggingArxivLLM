# # ReSem3D: 通过细粒度语义接地构建可优化的3D空间约束，实现通用机器人操作能力

发布时间：2025年07月24日

`LLM应用` `机器人` `计算机视觉`

> ReSem3D: Refinable 3D Spatial Constraints via Fine-Grained Semantic Grounding for Generalizable Robotic Manipulation

# 摘要

> 基于语义的三维空间约束将高层语义表征与低层动作空间对齐，促进机器人操纵中任务理解和执行的统一。多模态大型语言模型 (MLLMs) 与视觉基础模型 (VFMs) 的协同推理使得跨模态三维空间约束构建成为可能。然而，现有方法存在三个关键限制：(1) 约束建模中语义粒度较粗，(2) 缺乏实时闭环规划，(3) 在语义多样化环境中鲁棒性不足。

    为了解决这些挑战，我们提出 ReSem3D，这是一个适用于语义多样化环境的统一操纵框架。通过利用 VFMs 与 MLLMs 之间的协同作用，ReSem3D 实现了细粒度的视觉接地，并动态构建分层三维空间约束，以实现实时操纵。具体而言，该框架通过 MLLMs 中的分层递归推理驱动，与 VFMs 交互，在自然语言指令和 RGB-D 观察的基础上，分两个阶段自动构建三维空间约束：部件级提取和区域级细化。随后，这些约束被编码为关节空间中的实时优化目标，从而实现对动态扰动的反应行为。

    在语义丰富的家庭环境和稀疏的化学实验室环境中进行了广泛的模拟和真实世界实验。结果表明，ReSem3D 在零样本条件下能够执行多样化的操纵任务，展现出强大的适应性和泛化能力。代码和视频可在 https://resem3d.github.io 获取。
    

> Semantics-driven 3D spatial constraints align highlevel semantic representations with low-level action spaces, facilitating the unification of task understanding and execution in robotic manipulation. The synergistic reasoning of Multimodal Large Language Models (MLLMs) and Vision Foundation Models (VFMs) enables cross-modal 3D spatial constraint construction. Nevertheless, existing methods have three key limitations: (1) coarse semantic granularity in constraint modeling, (2) lack of real-time closed-loop planning, (3) compromised robustness in semantically diverse environments. To address these challenges, we propose ReSem3D, a unified manipulation framework for semantically diverse environments, leveraging the synergy between VFMs and MLLMs to achieve fine-grained visual grounding and dynamically constructs hierarchical 3D spatial constraints for real-time manipulation. Specifically, the framework is driven by hierarchical recursive reasoning in MLLMs, which interact with VFMs to automatically construct 3D spatial constraints from natural language instructions and RGB-D observations in two stages: part-level extraction and region-level refinement. Subsequently, these constraints are encoded as real-time optimization objectives in joint space, enabling reactive behavior to dynamic disturbances. Extensive simulation and real-world experiments are conducted in semantically rich household and sparse chemical lab environments. The results demonstrate that ReSem3D performs diverse manipulation tasks under zero-shot conditions, exhibiting strong adaptability and generalization. Code and videos at https://resem3d.github.io.

[Arxiv](https://arxiv.org/abs/2507.18262)