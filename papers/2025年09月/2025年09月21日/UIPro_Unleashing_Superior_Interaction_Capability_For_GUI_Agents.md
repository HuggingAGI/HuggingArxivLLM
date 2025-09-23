# UIPro：赋能GUI智能体，释放卓越交互能力

发布时间：2025年09月21日

`Agent` `基础理论`

> UIPro: Unleashing Superior Interaction Capability For GUI Agents

# 摘要

> 构建能像人类一样感知并操作图形用户界面（GUIs）的自主智能体，是人工智能领域长期以来的愿景。这类智能体的核心在于GUI交互能力，具体包括GUI理解与规划能力。现有方法多借助视觉语言模型（VLMs）的多模态理解能力来开发GUI智能体，但受限于场景单一、数据规模不足及动作空间异构等问题，通用GUI智能体的研发进展缓慢。为解决上述问题，本文提出	extbf{UIPro}——一种新型通用GUI智能体，其训练数据涵盖多平台、多任务的海量GUI交互数据，并采用统一的动作空间。我们首先构建了包含2060万项GUI理解任务的综合数据集，用于预训练UIPro，使其具备强大的GUI接地能力——这正是下游GUI智能体任务的核心所在。接着，我们构建统一动作空间以整合异构的GUI智能体任务数据集，生成合并数据集后，通过持续微调进一步提升UIPro的动作预测能力。实验结果显示，UIPro在不同平台的多个GUI任务基准测试中均表现卓越，充分验证了我们方法的有效性。

> Building autonomous agents that perceive and operate graphical user interfaces (GUIs) like humans has long been a vision in the field of artificial intelligence. Central to these agents is the capability for GUI interaction, which involves GUI understanding and planning capabilities. Existing methods have tried developing GUI agents based on the multi-modal comprehension ability of vision-language models (VLMs). However, the limited scenario, insufficient size, and heterogeneous action spaces hinder the progress of building generalist GUI agents. To resolve these issues, this paper proposes \textbf{UIPro}, a novel generalist GUI agent trained with extensive multi-platform and multi-task GUI interaction data, coupled with a unified action space. We first curate a comprehensive dataset encompassing 20.6 million GUI understanding tasks to pre-train UIPro, granting it a strong GUI grounding capability, which is key to downstream GUI agent tasks. Subsequently, we establish a unified action space to harmonize heterogeneous GUI agent task datasets and produce a merged dataset to foster the action prediction ability of UIPro via continued fine-tuning. Experimental results demonstrate UIPro's superior performance across multiple GUI task benchmarks on various platforms, highlighting the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2509.17328)