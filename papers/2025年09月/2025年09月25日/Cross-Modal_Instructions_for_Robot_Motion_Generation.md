# 面向机器人运动生成的跨模态指令

发布时间：2025年09月25日

`LLM应用` `工业与制造`

> Cross-Modal Instructions for Robot Motion Generation

# 摘要

> 要让机器人掌握新技能，传统方法通常需要远程操作或动觉教学来演示动作——说白了，就是手把手地物理引导机器人。尽管近年来有研究尝试用手绘草图来定义机器人要做的动作，但数据收集依旧麻烦，演示数据集也很难扩大规模。为此，我们在本文中提出了一种全新范式——跨模态指令学习。这种方法不用物理动作演示，而是用粗略的注释来“教”机器人，注释里还能加入自由文本标签。我们还设计了CrossInstruct框架：它把跨模态指令作为示例，直接喂给基础视觉语言模型（VLM）的上下文输入。接着，VLM会反复询问一个小型微调模型，然后在多个2D视角下合成出想要的动作。这些动作数据随后会被融合，在机器人的工作空间里形成3D运动轨迹的连贯分布。CrossInstruct把大型VLM的推理能力和细粒度指向模型结合起来，不仅能生成可执行的机器人动作，还能跳出有限指令示例的局限，在新环境里也能用。我们还搭了个下游强化学习流程，它能利用CrossInstruct的输出，快速学会完成精细任务的策略。我们在基准仿真任务和真实机器人硬件上做了严格测试，结果显示CrossInstruct不用额外微调就能生效，还能为后续强化学习优化的策略提供很好的初始状态。

> Teaching robots novel behaviors typically requires motion demonstrations via teleoperation or kinaesthetic teaching, that is, physically guiding the robot. While recent work has explored using human sketches to specify desired behaviors, data collection remains cumbersome, and demonstration datasets are difficult to scale. In this paper, we introduce an alternative paradigm, Learning from Cross-Modal Instructions, where robots are shaped by demonstrations in the form of rough annotations, which can contain free-form text labels, and are used in lieu of physical motion. We introduce the CrossInstruct framework, which integrates cross-modal instructions as examples into the context input to a foundational vision-language model (VLM). The VLM then iteratively queries a smaller, fine-tuned model, and synthesizes the desired motion over multiple 2D views. These are then subsequently fused into a coherent distribution over 3D motion trajectories in the robot's workspace. By incorporating the reasoning of the large VLM with a fine-grained pointing model, CrossInstruct produces executable robot behaviors that generalize beyond the environment of in the limited set of instruction examples. We then introduce a downstream reinforcement learning pipeline that leverages CrossInstruct outputs to efficiently learn policies to complete fine-grained tasks. We rigorously evaluate CrossInstruct on benchmark simulation tasks and real hardware, demonstrating effectiveness without additional fine-tuning and providing a strong initialization for policies subsequently refined via reinforcement learning.

[Arxiv](https://arxiv.org/abs/2509.21107)