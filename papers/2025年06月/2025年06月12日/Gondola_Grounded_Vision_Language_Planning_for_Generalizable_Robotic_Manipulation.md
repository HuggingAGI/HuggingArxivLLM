# Gondola：面向通用机器人操作的视觉语言规划方案

发布时间：2025年06月12日

`LLM应用` `机器人` `视觉-语言规划`

> Gondola: Grounded Vision Language Planning for Generalizable Robotic Manipulation

# 摘要

> 机器人操作在面对未见过的对象、环境和任务时，面临着巨大的泛化挑战。为了提升泛化能力，近期研究将大型语言模型（LLMs）引入了规划和动作执行领域。尽管这些方法前景广阔，但在视觉环境中生成具体可行的计划时往往表现不佳。尽管已有研究尝试对LLMs进行视觉指令微调以提升机器人操作性能，但现有方法通常受限于单视角图像输入，并在精准对象定位方面存在困难。本文中，我们提出了一种名为Gondola的新型基于LLMs的视觉-语言规划模型，旨在实现可泛化的机器人操作。Gondola通过多视图图像和历史计划，生成包含目标对象和位置的文本描述与分割掩码交织的下一步动作计划。为了支持Gondola的训练，我们利用RLBench仿真器构建了三类数据集，包括机器人视觉-语言规划、多视图引用表达和伪长时任务数据集。在GemBench数据集的四个泛化水平（新型放置、刚性物体、关节物体和长时任务）上，Gondola的表现均超越了现有的基于LLMs的最先进方法。

> Robotic manipulation faces a significant challenge in generalizing across unseen objects, environments and tasks specified by diverse language instructions. To improve generalization capabilities, recent research has incorporated large language models (LLMs) for planning and action execution. While promising, these methods often fall short in generating grounded plans in visual environments. Although efforts have been made to perform visual instructional tuning on LLMs for robotic manipulation, existing methods are typically constrained by single-view image input and struggle with precise object grounding. In this work, we introduce Gondola, a novel grounded vision-language planning model based on LLMs for generalizable robotic manipulation. Gondola takes multi-view images and history plans to produce the next action plan with interleaved texts and segmentation masks of target objects and locations. To support the training of Gondola, we construct three types of datasets using the RLBench simulator, namely robot grounded planning, multi-view referring expression and pseudo long-horizon task datasets. Gondola outperforms the state-of-the-art LLM-based method across all four generalization levels of the GemBench dataset, including novel placements, rigid objects, articulated objects and long-horizon tasks.

[Arxiv](https://arxiv.org/abs/2506.11261)