# MASTER：借助多智能体模拟教学，提升大型语言模型的能力

发布时间：2025年06月03日

`LLM应用

摘要主要讨论了指令微调和数据增强方法（MASTER）的应用，以及构建BOOST-QA数据集用于模型微调，展示了其在提升模型性能方面的实际效果，属于LLM的应用层面。` `数据增强`

> MASTER: Enhancing Large Language Model via Multi-Agent Simulated Teaching

# 摘要

> 指令微调对自然语言处理任务至关重要，它能显著提升预训练模型的指令理解和任务执行能力。然而，为大型模型获取高质量的微调数据却面临诸多挑战，主要源于数据收集的难度和高昂的生产成本。为解决这一难题，我们提出了MASTER——一种创新的数据增强方法。通过模拟多个认知水平各异的智能体之间的互动，MASTER能够有效丰富原始数据。我们设计了三种基于教学原理的教学场景，借助多智能体对话生成高质量的师生互动数据。利用MASTER，我们构建了BOOST-QA这一微调数据集，该数据集是在Orca-Math-200k、ProcQA和OpenHermes2.5等现有数据集的基础上进行增强的。实验结果表明，经过BOOST-QA微调的模型在多个基准测试中表现优异，展现出强大的多任务泛化能力。值得注意的是，MASTER显著提升了模型在复杂任务中的推理能力，为未来的研究提供了宝贵的见解。

> Instruction fine-tuning is crucial in NLP tasks, enhancing pretrained models' instruction-following capabilities and task-specific performance. However, obtaining high-quality fine-tuning data for large models is challenging due to data collection difficulties and high production costs. To address this, we propose MASTER, a novel data augmentation method that enriches original data through interactions among multiple agents with varying cognitive levels. We simulate three pedagogically grounded teaching scenarios, leveraging multi-agent conversations to generate high-quality teacher-student interaction data. Utilizing MASTER, we construct BOOST-QA, a fine-tuning dataset augmented from existing datasets like Orca-Math-200k, ProcQA, and OpenHermes2.5. Experiments show that models fine-tuned with BOOST-QA perform excellently across multiple benchmarks, demonstrating strong multitask generalization. Notably, MASTER significantly improves models' reasoning abilities in complex tasks, providing valuable insights for future research.

[Arxiv](https://arxiv.org/abs/2506.02689)