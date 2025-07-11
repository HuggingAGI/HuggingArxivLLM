# # **摘要**  
MoSE: 逐技能专家混合学习，赋能自动驾驶

发布时间：2025年07月10日

`LLM应用` `自动驾驶` `机器人`

> MoSE: Skill-by-Skill Mixture-of-Expert Learning for Autonomous Driving

# 摘要

> 近期研究表明，基于网络规模数据训练的大规模语言模型（LLMs）和视觉语言模型（VLMs）能够赋能端到端自动驾驶系统，实现更好的泛化和解释能力。具体而言，通过动态路由输入到特定参数子集，混合专家（MoE）技术使通用的LLMs或VLMs在保持计算效率的同时实现性能显著提升。然而，通用的MoE模型通常需要大量训练数据和复杂优化。受人类驾驶者学习过程启发，我们提出了一种技能导向的MoE，名为MoSE，它模仿了人类驾驶者按技能和步骤的学习与推理过程。我们提出了一种技能导向的路由机制，从定义和标注特定技能开始，使专家能够识别各种场景和推理任务所需的驾驶能力，从而支持按技能学习。进一步将驾驶过程与人类推理中的多步规划和端到端驾驶模型相匹配，我们构建了分层技能数据集，并对路由器进行预训练，以鼓励模型逐步推理。与多轮对话不同，MoSE将有价值的辅助任务（如描述、推理、规划）整合到一个前向过程中，而不会增加任何额外计算成本。我们的模型在CODA AD角案例推理任务中，仅使用不到30亿的稀疏激活参数，就超越了多个80亿+参数模型。与基于开源模型和数据的方法相比，我们的方法以更小的激活模型尺寸（至少减少62.5%）实现了单轮对话下的最优性能。


> Recent studies show large language models (LLMs) and vision language models (VLMs) trained using web-scale data can empower end-to-end autonomous driving systems for a better generalization and interpretation. Specifically, by dynamically routing inputs to specialized subsets of parameters, the Mixture-of-Experts (MoE) technique enables general LLMs or VLMs to achieve substantial performance improvements while maintaining computational efficiency. However, general MoE models usually demands extensive training data and complex optimization. In this work, inspired by the learning process of human drivers, we propose a skill-oriented MoE, called MoSE, which mimics human drivers' learning process and reasoning process, skill-by-skill and step-by-step. We propose a skill-oriented routing mechanism that begins with defining and annotating specific skills, enabling experts to identify the necessary driving competencies for various scenarios and reasoning tasks, thereby facilitating skill-by-skill learning. Further align the driving process to multi-step planning in human reasoning and end-to-end driving models, we build a hierarchical skill dataset and pretrain the router to encourage the model to think step-by-step. Unlike multi-round dialogs, MoSE integrates valuable auxiliary tasks (e.g.\ description, reasoning, planning) in one single forward process without introducing any extra computational cost. With less than 3B sparsely activated parameters, our model outperforms several 8B+ parameters on CODA AD corner case reasoning task. Compared to existing methods based on open-source models and data, our approach achieves state-of-the-art performance with significantly reduced activated model size (at least by $62.5\%$) with a single-turn conversation.

[Arxiv](https://arxiv.org/abs/2507.07818)