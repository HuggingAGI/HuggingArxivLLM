# CCL25-Eval 任务 10 系统报告：SRAG-MAV 在细粒度中文仇恨言论识别中的应用

发布时间：2025年07月24日

`LLM应用` `中文文本处理`

> System Report for CCL25-Eval Task 10: SRAG-MAV for Fine-Grained Chinese Hate Speech Recognition

# 摘要

> 本文介绍了我们为CCL25-Eval任务10设计的系统，专注于细粒度中文仇恨言论识别（FGCHSR）。我们创新性地提出了SRAG-MAV框架，该框架通过任务重新定义（TR）、自我检索增强生成（SRAG）和多轮累计投票（MAV）的协同作用实现高性能。我们的方法将复杂的四元组抽取任务简化为更易处理的三元组抽取，通过动态检索生成上下文提示，并采用多轮推理结合投票机制提升输出的稳定性和性能。基于Qwen2.5-7B模型，我们的系统在STATE ToxiCN数据集上取得了硬得分26.66、软得分48.35以及平均得分37.505的优异成绩，显著优于GPT-4o（平均得分15.63）和微调后的Qwen2.5-7B（平均得分35.365）。我们的代码已开源，地址为https://github.com/king-wang123/CCL25-SRAG-MAV。

> This paper presents our system for CCL25-Eval Task 10, addressing Fine-Grained Chinese Hate Speech Recognition (FGCHSR). We propose a novel SRAG-MAV framework that synergistically integrates task reformulation(TR), Self-Retrieval-Augmented Generation (SRAG), and Multi-Round Accumulative Voting (MAV). Our method reformulates the quadruplet extraction task into triplet extraction, uses dynamic retrieval from the training set to create contextual prompts, and applies multi-round inference with voting to improve output stability and performance. Our system, based on the Qwen2.5-7B model, achieves a Hard Score of 26.66, a Soft Score of 48.35, and an Average Score of 37.505 on the STATE ToxiCN dataset, significantly outperforming baselines such as GPT-4o (Average Score 15.63) and fine-tuned Qwen2.5-7B (Average Score 35.365). The code is available at https://github.com/king-wang123/CCL25-SRAG-MAV.

[Arxiv](https://arxiv.org/abs/2507.18580)