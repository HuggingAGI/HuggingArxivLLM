# Compiler-R1：探索利用强化学习实现智能体编译器自动调优

发布时间：2025年05月29日

`LLM应用` `编译器` `机器学习`

> Compiler-R1: Towards Agentic Compiler Auto-tuning with Reinforcement Learning

# 摘要

> 编译器自动调优通过优化Pass序列来提升性能指标，例如中间表示（IR）指令数量。尽管近期利用大型语言模型（LLMs）的进展在自动化编译器调优方面展现出潜力，但仍存在两大挑战：缺乏高质量的推理数据集用于代理训练，以及与编译环境的有效交互有限。本研究介绍了Compiler-R1，首个专为编译器自动调优设计的强化学习（RL）驱动框架，旨在增强LLM的能力。Compiler-R1配备了一个精挑细选的高质量推理数据集，以及一个创新的两阶段端到端RL训练管道，通过基于结果的奖励实现高效的环境探索和学习。在七个数据集上的广泛实验证明，与opt -Oz相比，Compiler-R1平均实现了8.46%的IR指令数量减少，充分展示了RL训练的LLM在编译器优化中的强大潜力。我们的代码和数据集已在GitHub上公开发布，地址为https://github.com/Panhaolin2001/Compiler-R1。


> Compiler auto-tuning optimizes pass sequences to improve performance metrics such as Intermediate Representation (IR) instruction count. Although recent advances leveraging Large Language Models (LLMs) have shown promise in automating compiler tuning, two significant challenges still remain: the absence of high-quality reasoning datasets for agents training, and limited effective interactions with the compilation environment. In this work, we introduce Compiler-R1, the first reinforcement learning (RL)-driven framework specifically augmenting LLM capabilities for compiler auto-tuning. Compiler-R1 features a curated, high-quality reasoning dataset and a novel two-stage end-to-end RL training pipeline, enabling efficient environment exploration and learning through an outcome-based reward. Extensive experiments across seven datasets demonstrate Compiler-R1 achieving an average 8.46% IR instruction count reduction compared to opt -Oz, showcasing the strong potential of RL-trained LLMs for compiler optimization. Our code and datasets are publicly available at https://github.com/Panhaolin2001/Compiler-R1.

[Arxiv](https://arxiv.org/abs/2506.15701)