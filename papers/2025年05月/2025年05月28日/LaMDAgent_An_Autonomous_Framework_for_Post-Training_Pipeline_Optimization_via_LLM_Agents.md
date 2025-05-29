# LaMDAgent：基于LLM代理的训练后流水线自主优化框架

发布时间：2025年05月28日

`Agent` `人工智能`

> LaMDAgent: An Autonomous Framework for Post-Training Pipeline Optimization via LLM Agents

# 摘要

> 大型语言模型（LLMs）在各类任务中表现优异。为了更好地将LLMs应用于特定领域或场景，通常会采用监督微调（SFT）、偏好学习和模型合并等后训练技术。尽管这些方法在各自领域得到了深入研究，但如何自动构建完整的后训练流程仍是一个亟待探索的领域。现有方法通常依赖手动设计，或仅专注于优化单一组件，例如数据排序或合并策略。在本研究中，我们提出了LaMDAgent（Language Model Developing Agent的缩写），这是一个全新的智能体框架，能够自主构建和优化完整的后训练流程。通过基于LLM的智能体，LaMDAgent系统性地探索了多样化的模型生成技术、数据集和超参数配置，并借助任务反馈机制，在极小人工干预的情况下发现高性能的训练流程。实验结果表明，LaMDAgent将工具使用准确率提升了9.0个百分点，同时保持了模型遵循指令的能力。此外，它还揭示了传统人工探索中常被忽视的有效后训练策略。我们进一步分析了数据和模型规模对探索成本的影响，发现模型规模的扩展带来了新的挑战，而数据规模的扩展则能以更低成本实现高效的流程发现。

> Large Language Models (LLMs) have demonstrated exceptional performance across a wide range of tasks. To further tailor LLMs to specific domains or applications, post-training techniques such as Supervised Fine-Tuning (SFT), Preference Learning, and model merging are commonly employed. While each of these methods has been extensively studied in isolation, the automated construction of complete post-training pipelines remains an underexplored area. Existing approaches typically rely on manual design or focus narrowly on optimizing individual components, such as data ordering or merging strategies. In this work, we introduce LaMDAgent (short for Language Model Developing Agent), a novel framework that autonomously constructs and optimizes full post-training pipelines through the use of LLM-based agents. LaMDAgent systematically explores diverse model generation techniques, datasets, and hyperparameter configurations, leveraging task-based feedback to discover high-performing pipelines with minimal human intervention. Our experiments show that LaMDAgent improves tool-use accuracy by 9.0 points while preserving instruction-following capabilities. Moreover, it uncovers effective post-training strategies that are often overlooked by conventional human-driven exploration. We further analyze the impact of data and model size scaling to reduce computational costs on the exploration, finding that model size scalings introduces new challenges, whereas scaling data size enables cost-effective pipeline discovery.

[Arxiv](https://arxiv.org/abs/2505.21963)