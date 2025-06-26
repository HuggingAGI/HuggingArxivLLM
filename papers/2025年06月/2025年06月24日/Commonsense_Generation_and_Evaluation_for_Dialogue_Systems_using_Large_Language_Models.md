# 基于大型语言模型的对话系统常识生成与评估

发布时间：2025年06月24日

`LLM应用

理由：这篇论文探讨了如何利用预训练的大型语言模型（LLMs）进行对话系统的数据增强和评估，展示了LLMs在实际任务中的应用，属于LLM应用类别。` `对话系统` `常识推理`

> Commonsense Generation and Evaluation for Dialogue Systems using Large Language Models

# 摘要

> 本文初步探索了基于不同常识关系进行对话系统轮次级别数据增强的任务，并对生成的合成轮次进行自动评估。所提方法充分利用预训练大型语言模型（LLMs）的扩展知识和零样本能力，使其能够遵循指令、理解上下文信息，并运用常识推理能力。该方法从Chain-of-Thought（CoT）等方法中汲取灵感，更明确地应用于基于提示生成的对话数据增强任务，这些任务基于常识属性条件，并对生成的对话进行自动评估。

为了验证方法有效性，我们从5个知名对话数据集中随机抽取了200个部分对话，并根据不同的事件常识属性生成替代响应。这一新颖数据集使我们能够衡量LLMs在生成上下文相关常识知识方面的熟练程度，特别是涉及多达12种不同的具体ATOMIC[10]数据库关系。同时，我们提出了一种基于ACCENT[26]指标启发的评估框架，用于自动检测生成数据集的质量。与ACCENT不同，我们为每个常识属性设计了一个基于指令的提示，并使用最先进的LLMs自动检测上一步生成每个增强轮次时所使用的原始属性。

初步结果显示，我们的方法能够有效利用LLMs在对话系统中的常识推理和评估能力。


> This paper provides preliminary results on exploring the task of performing turn-level data augmentation for dialogue system based on different types of commonsense relationships, and the automatic evaluation of the generated synthetic turns. The proposed methodology takes advantage of the extended knowledge and zero-shot capabilities of pretrained Large Language Models (LLMs) to follow instructions, understand contextual information, and their commonsense reasoning capabilities. The approach draws inspiration from methodologies like Chain-of-Thought (CoT), applied more explicitly to the task of prompt-based generation for dialogue-based data augmentation conditioned on commonsense attributes, and the automatic evaluation of the generated dialogues.
  To assess the effectiveness of the proposed approach, first we extracted 200 randomly selected partial dialogues, from 5 different well-known dialogue datasets, and generate alternative responses conditioned on different event commonsense attributes. This novel dataset allows us to measure the proficiency of LLMs in generating contextually relevant commonsense knowledge, particularly up to 12 different specific ATOMIC [10] database relations. Secondly, we propose an evaluation framework to automatically detect the quality of the generated dataset inspired by the ACCENT [26] metric, which offers a nuanced approach to assess event commonsense. However, our method does not follow ACCENT's complex eventrelation tuple extraction process. Instead, we propose an instruction-based prompt for each commonsense attribute and use state-of-the-art LLMs to automatically detect the original attributes used when creating each augmented turn in the previous step.
  Preliminary results suggest that our approach effectively harnesses LLMs capabilities for commonsense reasoning and evaluation in dialogue systems.

[Arxiv](https://arxiv.org/abs/2506.19483)