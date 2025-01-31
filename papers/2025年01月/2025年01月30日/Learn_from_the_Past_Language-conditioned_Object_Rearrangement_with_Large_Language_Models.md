# 从过去学习：利用大型语言模型实现语言条件对象重排

发布时间：2025年01月30日

`LLM应用

理由：这篇论文提出了一种基于大型语言模型（LLM）的语言条件物体重新排列框架，利用LLM的自然语言理解和推理能力来处理机器人重新排列任务。这属于将LLM应用于具体任务（机器人重新排列）的范畴，因此归类为“LLM应用”。` `机器人`

> Learn from the Past: Language-conditioned Object Rearrangement with Large Language Models

# 摘要

> 物体重新排列是协作机器人的核心任务之一，旨在将物体调整至指定目标状态。然而，如何高效确定物体的放置位置仍是一大挑战。现有方法多依赖预收集数据集训练模型，且局限于特定指令，限制了其广泛适用性。本文提出了一种基于大型语言模型（LLM）的语言条件物体重新排列框架。该方法借鉴人类推理方式，利用过往成功经验推断目标位置。凭借LLM强大的自然语言理解和推理能力，我们的方法能以零-shot方式处理多种日常物体和自由形式指令。实验表明，该方法能有效执行机器人重新排列任务，包括复杂的长序列指令。

> Object rearrangement is a significant task for collaborative robots, where they are directed to manipulate objects into a specified goal state. Determining the placement of objects is a major challenge that influences the efficiency of the rearrangement process. Most current methods heavily rely on pre-collected datasets to train the model for predicting the goal position and are restricted to specific instructions, which limits their broader applicability and effectiveness.In this paper, we propose a framework of language-conditioned object rearrangement based on the Large Language Model (LLM). Particularly, our approach mimics human reasoning by using past successful experiences as a reference to infer the desired goal position. Based on LLM's strong natural language comprehension and inference ability, our method can generalise to handle various everyday objects and free-form language instructions in a zero-shot manner. Experimental results demonstrate that our methods can effectively execute the robotic rearrangement tasks, even those involving long sequential orders.

[Arxiv](https://arxiv.org/abs/2501.18516)