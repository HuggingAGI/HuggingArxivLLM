# 宣传检测的混合标注方法：结合大型语言模型预标注与人工智慧

发布时间：2025年07月24日

`LLM应用` `社交媒体分析` `媒体生态系统`

> Hybrid Annotation for Propaganda Detection: Integrating LLM Pre-Annotations with Human Intelligence

# 摘要

> 社交媒体上的宣传检测仍具挑战性，主要源于任务复杂性和高质量标注数据的稀缺性。本文提出了一种结合人类专业知识与大型语言模型（LLM）辅助的全新框架，旨在提升标注的一致性和扩展性。我们构建了一个层次分类法，将14种细致的宣传技巧归类为三大更广泛的类别。在HQP数据集上开展的人工标注研究发现，细粒度标签的标注者间一致性较低。我们实现了一个LLM辅助的预标注流水线，用于提取宣传片段、生成简洁解释并分配局部及全局标签。后续的人工验证研究显示，标注一致性和时间效率均显著提升。在此基础上，我们微调了小型语言模型（SLM）以执行结构化标注。与基于人工标注的微调不同，我们采用高质量的LLM生成数据进行训练，使大型模型生成这些标注，而小型模型则通过知识蒸馏学习生成这些标注。我们的研究为构建可扩展且鲁棒的宣传检测系统做出了贡献，支持构建透明、可问责的媒体生态系统的理念，与SDG 16目标一致。代码已公开发布于我们的GitHub仓库。


> Propaganda detection on social media remains challenging due to task complexity and limited high-quality labeled data. This paper introduces a novel framework that combines human expertise with Large Language Model (LLM) assistance to improve both annotation consistency and scalability. We propose a hierarchical taxonomy that organizes 14 fine-grained propaganda techniques into three broader categories, conduct a human annotation study on the HQP dataset that reveals low inter-annotator agreement for fine-grained labels, and implement an LLM-assisted pre-annotation pipeline that extracts propagandistic spans, generates concise explanations, and assigns local labels as well as a global label. A secondary human verification study shows significant improvements in both agreement and time-efficiency. Building on this, we fine-tune smaller language models (SLMs) to perform structured annotation. Instead of fine-tuning on human annotations, we train on high-quality LLM-generated data, allowing a large model to produce these annotations and a smaller model to learn to generate them via knowledge distillation. Our work contributes towards the development of scalable and robust propaganda detection systems, supporting the idea of transparent and accountable media ecosystems in line with SDG 16. The code is publicly available at our GitHub repository.

[Arxiv](https://arxiv.org/abs/2507.18343)