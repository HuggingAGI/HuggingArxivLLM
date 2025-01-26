# RAG-Reward: 通过奖励建模与RLHF优化RAG

发布时间：2025年01月22日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）的优化问题，特别是通过奖励模型和强化学习来提升RAG的性能。论文提出了一个名为RAG-Reward的数据集，并开发了自动化注释管道来评估生成质量。这些内容直接与RAG相关，因此将其分类为RAG是合适的。`

> RAG-Reward: Optimizing RAG with Reward Modeling and RLHF

# 摘要

> 检索增强生成（RAG）通过为大型语言模型（LLMs）注入相关且最新的知识，显著提升了其回答知识密集型问题的能力。它不仅提高了生成质量，还增强了可信度。尽管已有大量研究致力于优化检索、生成和评估，但奖励模型在强化学习中的作用，尤其是在优化RAG和构建自动化基准测试管道方面，仍未被充分挖掘。本文提出了	extbf{RAG-Reward}数据集，旨在实现	extit{无幻觉、全面、可靠且高效的RAG}。我们定义了四个关键指标来评估生成质量，并开发了一个自动化注释管道，利用多个LLMs生成多样化的RAG场景输出。GPT-4o被用于评估和构建偏好数据。通过	extbf{RAG-Reward}，我们训练了奖励模型，并应用了基于人类反馈的强化学习（RLHF）来提升LLMs在RAG中的表现。实验结果显示，我们的奖励模型在保留测试集上达到了最先进的性能，验证了我们方法的有效性和数据集的高质量。此外，训练后的策略模型生成质量的显著提升，进一步证明了使用RLHF优化RAG管道的可行性。

> Retrieval-augmented generation (RAG) enhances Large Language Models (LLMs) with relevant and up-to-date knowledge, improving their ability to answer knowledge-intensive questions. It has been shown to enhance both generation quality and trustworthiness. While numerous works have focused on improving retrieval, generation, and evaluation, the role of reward models in reinforcement learning for optimizing RAG and establishing automated benchmarking pipelines remains underexplored. In this paper, we introduce \textbf{RAG-Reward}, a dataset designed to enable \textit{hallucination-free, comprehensive, reliable, and efficient RAG}. We define four key metrics for assessing generation quality and develop an automated annotation pipeline that leverages multiple LLMs to generate outputs across diverse RAG scenarios. GPT-4o is used to evaluate and construct preference data. Using \textbf{RAG-Reward}, we train reward models and apply reinforcement learning with human feedback (RLHF) to improve LLMs' effectiveness in RAG. Experimental results show that our reward model achieves state-of-the-art performance on a held-out test set, demonstrating both the effectiveness of our approach and the quality of our dataset. Furthermore, the improved generation quality of the trained policy model highlights the feasibility of using RLHF to enhance RAG pipelines.

[Arxiv](https://arxiv.org/abs/2501.13264)