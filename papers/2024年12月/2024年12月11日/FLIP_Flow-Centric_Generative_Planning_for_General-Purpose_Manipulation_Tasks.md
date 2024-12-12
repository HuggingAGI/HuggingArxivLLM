# FLIP：用于通用操作任务的以流为核心的生成式规划

发布时间：2024年12月11日

`Agent` `机器人` `视觉规划`

> FLIP: Flow-Centric Generative Planning for General-Purpose Manipulation Tasks

# 摘要

> 我们致力于为世界模型构建一个基于模型的规划框架，它能随着模型和数据预算的增多而拓展，适用于仅有语言和视觉输入的通用操控任务。为此，我们推出了以流为核心的生成式规划（FLIP），这是一种基于视觉空间的模型规划算法，具备三个关键模块：1. 作为通用动作提议模块的多模态流生成模型；2. 作为动态模块的流条件视频生成模型；3. 作为价值模块的视觉语言表示学习模型。给定初始图像和作为目标的语言指令，FLIP 能够逐步探寻长期的流和视频规划，以实现最大化折扣回报来完成任务。FLIP 能够以图像流作为通用动作表征，在对象、机器人和任务之间合成长期规划，而且密集的流信息也为长期视频生成提供了丰富指引。另外，合成的流和视频规划能够引导机器人执行的低级控制策略的训练。在各类基准上的实验表明，FLIP 能够提升长期视频规划合成的成功率和质量，还具有交互式世界模型属性，为未来工作开拓了更广泛的应用。

> We aim to develop a model-based planning framework for world models that can be scaled with increasing model and data budgets for general-purpose manipulation tasks with only language and vision inputs. To this end, we present FLow-centric generative Planning (FLIP), a model-based planning algorithm on visual space that features three key modules: 1. a multi-modal flow generation model as the general-purpose action proposal module; 2. a flow-conditioned video generation model as the dynamics module; and 3. a vision-language representation learning model as the value module. Given an initial image and language instruction as the goal, FLIP can progressively search for long-horizon flow and video plans that maximize the discounted return to accomplish the task. FLIP is able to synthesize long-horizon plans across objects, robots, and tasks with image flows as the general action representation, and the dense flow information also provides rich guidance for long-horizon video generation. In addition, the synthesized flow and video plans can guide the training of low-level control policies for robot execution. Experiments on diverse benchmarks demonstrate that FLIP can improve both the success rates and quality of long-horizon video plan synthesis and has the interactive world model property, opening up wider applications for future works.

[Arxiv](https://arxiv.org/abs/2412.08261)