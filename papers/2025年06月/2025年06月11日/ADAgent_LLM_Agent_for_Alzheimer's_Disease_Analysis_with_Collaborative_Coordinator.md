# ADAgent：用于阿尔茨海默病分析的 LLM 代理与协作协调器

发布时间：2025年06月11日

`LLM应用` `人工智能`

> ADAgent: LLM Agent for Alzheimer's Disease Analysis with Collaborative Coordinator

# 摘要

> 阿尔茨海默病（AD）是一种渐进性和不可逆的神经退行性疾病。早期准确的诊断对于及时干预和治疗规划，以缓解渐进性神经退化至关重要。然而，大多数现有方法依赖于单一模式的数据，这与医疗专家使用的多方面方法形成鲜明对比。尽管一些深度学习方法处理多模态数据，但它们仅限于特定任务，输入模态种类有限，无法处理任意组合。这凸显了需要一个能够处理多种与AD相关的任务、处理多模态或缺失输入，并整合多种先进方法以提高性能的系统。本文中，我们提出了ADAgent，首个专门用于AD分析的AI代理，基于大型语言模型（LLM）构建，以回答用户查询并支持决策。ADAgent集成了推理引擎、专用医疗工具和协作结果协调器，以促进AD的多模态诊断和预后任务。大量实验表明，ADAgent优于现有最优方法，在准确性方面取得了显著提升，包括多模态诊断提高了2.7%，多模态预后改善了0.7%，并在MRI和PET诊断任务中实现了增强。

> Alzheimer's disease (AD) is a progressive and irreversible neurodegenerative disease. Early and precise diagnosis of AD is crucial for timely intervention and treatment planning to alleviate the progressive neurodegeneration. However, most existing methods rely on single-modality data, which contrasts with the multifaceted approach used by medical experts. While some deep learning approaches process multi-modal data, they are limited to specific tasks with a small set of input modalities and cannot handle arbitrary combinations. This highlights the need for a system that can address diverse AD-related tasks, process multi-modal or missing input, and integrate multiple advanced methods for improved performance. In this paper, we propose ADAgent, the first specialized AI agent for AD analysis, built on a large language model (LLM) to address user queries and support decision-making. ADAgent integrates a reasoning engine, specialized medical tools, and a collaborative outcome coordinator to facilitate multi-modal diagnosis and prognosis tasks in AD. Extensive experiments demonstrate that ADAgent outperforms SOTA methods, achieving significant improvements in accuracy, including a 2.7% increase in multi-modal diagnosis, a 0.7% improvement in multi-modal prognosis, and enhancements in MRI and PET diagnosis tasks.

[Arxiv](https://arxiv.org/abs/2506.11150)