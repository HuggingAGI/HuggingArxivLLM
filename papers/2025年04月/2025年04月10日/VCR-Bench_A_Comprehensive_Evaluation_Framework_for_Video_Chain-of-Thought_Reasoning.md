# VCR-Bench：视频链式思维推理的全面评估框架

发布时间：2025年04月10日

`LLM应用` `视频分析` `视觉-语言模型`

> VCR-Bench: A Comprehensive Evaluation Framework for Video Chain-of-Thought Reasoning

# 摘要

> 链式推理（CoT）的进展显著提升了大型语言模型（LLMs）和大型视觉-语言模型（LVLMs）的能力。然而，视频链式推理的严格评估框架仍然缺失。现有视频基准未能充分评估推理过程，也无法揭示失败是源于感知能力还是推理能力的不足。因此，我们提出了VCR-Bench这一全新基准，旨在全面评估LVLMs的视频链式推理能力。VCR-Bench包含859个涵盖多种视频内容和时长的视频，以及1,034对高质量的问题-答案。每对问题-答案都经过人工标注，包含逐步的CoT推理过程，每个步骤都带有标签，表明其与感知或推理能力的关联。此外，我们设计了七个不同的任务维度，并提出了CoT分数，基于逐步标注的CoT推理过程来评估整个CoT过程。在VCR-Bench上进行的大量实验凸显了现有LVLMs的重大局限性。即使表现最佳的模型o1，仅达到62.8%的CoT分数和56.7%的准确率，而大多数模型得分低于40%。实验显示，大多数模型在感知步骤上的得分低于推理步骤，揭示了LVLMs在复杂视频推理中处理时空信息的关键瓶颈。CoT分数与准确率之间的强正相关性证实了我们评估框架的有效性，并突显了CoT推理在解决复杂视频推理任务中的关键作用。我们希望VCR-Bench能作为标准化的评估框架，并揭示复杂视频推理任务中的实际缺陷。

> The advancement of Chain-of-Thought (CoT) reasoning has significantly enhanced the capabilities of large language models (LLMs) and large vision-language models (LVLMs). However, a rigorous evaluation framework for video CoT reasoning remains absent. Current video benchmarks fail to adequately assess the reasoning process and expose whether failures stem from deficiencies in perception or reasoning capabilities. Therefore, we introduce VCR-Bench, a novel benchmark designed to comprehensively evaluate LVLMs' Video Chain-of-Thought Reasoning capabilities. VCR-Bench comprises 859 videos spanning a variety of video content and durations, along with 1,034 high-quality question-answer pairs. Each pair is manually annotated with a stepwise CoT rationale, where every step is tagged to indicate its association with the perception or reasoning capabilities. Furthermore, we design seven distinct task dimensions and propose the CoT score to assess the entire CoT process based on the stepwise tagged CoT rationals. Extensive experiments on VCR-Bench highlight substantial limitations in current LVLMs. Even the top-performing model, o1, only achieves a 62.8% CoT score and an 56.7% accuracy, while most models score below 40%. Experiments show most models score lower on perception than reasoning steps, revealing LVLMs' key bottleneck in temporal-spatial information processing for complex video reasoning. A robust positive correlation between the CoT score and accuracy confirms the validity of our evaluation framework and underscores the critical role of CoT reasoning in solving complex video reasoning tasks. We hope VCR-Bench to serve as a standardized evaluation framework and expose the actual drawbacks in complex video reasoning task.

[Arxiv](https://arxiv.org/abs/2504.07956)