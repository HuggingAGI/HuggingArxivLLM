# REFINE-AF：任务无关框架，基于自动生成指令，采用基于自动化反馈的强化学习方法，实现语言模型对齐。

发布时间：2025年05月10日

`LLM应用` `机器学习`

> REFINE-AF: A Task-Agnostic Framework to Align Language Models via Self-Generated Instructions using Reinforcement Learning from Automated Feedback

# 摘要

> 基于指令的大语言模型（LLMs）在少样本或零样本自然语言处理（NLP）任务中表现出色。然而，创建人工标注的指令数据耗时费力，且数量和任务多样性往往受限。以往研究尝试通过从模型本身直接生成半自动化、任务无关指令框架来解决这一挑战。许多努力依赖于大型API-only参数模型（如GPT-3.5（175B）），这些模型昂贵且受限于查询数量。本文研究了使用半自动化框架的三个开源小型LLMs（如LLaMA 2-7B、LLama 2-13B和Mistral 7B）的性能，从而减少了生成用于微调LLMs指令数据集所需的人工干预、努力和成本。此外，我们证明将基于强化学习（RL）的训练算法整合到此LLMs框架中可进一步提升性能。对数据集的评估表明，与以往方法相比，这些基于RL的框架在63-66%的任务中实现了显著改进。

> Instruction-based Large Language Models (LLMs) have proven effective in numerous few-shot or zero-shot Natural Language Processing (NLP) tasks. However, creating human-annotated instruction data is time-consuming, expensive, and often limited in quantity and task diversity. Previous research endeavors have attempted to address this challenge by proposing frameworks capable of generating instructions in a semi-automated and task-agnostic manner directly from the model itself. Many of these efforts have relied on large API-only parameter-based models such as GPT-3.5 (175B), which are expensive, and subject to limits on a number of queries. This paper explores the performance of three open-source small LLMs such as LLaMA 2-7B, LLama 2-13B, and Mistral 7B, using a semi-automated framework, thereby reducing human intervention, effort, and cost required to generate an instruction dataset for fine-tuning LLMs. Furthermore, we demonstrate that incorporating a Reinforcement Learning (RL) based training algorithm into this LLMs-based framework leads to further enhancements. Our evaluation of the dataset reveals that these RL-based frameworks achieve a substantial improvements in 63-66% of the tasks compared to previous approaches.

[Arxiv](https://arxiv.org/abs/2505.06548)