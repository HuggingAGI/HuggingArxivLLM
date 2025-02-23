# RAG-Gym：通过流程监督优化推理与搜索智能体

发布时间：2025年02月19日

`RAG` `人工智能`

> RAG-Gym: Optimizing Reasoning and Search Agents with Process Supervision

# 摘要

> 检索增强生成（RAG）在知识密集型任务中展现出了巨大的潜力，但传统架构依赖静态检索，难以应对复杂问题中的顺序信息检索需求。虽然基于智能体的推理和搜索更显灵活，但现有方法仍高度依赖提示工程。我们提出RAG-Gym，一个通过在每个搜索步骤中提供精细流程监督来优化信息检索代理的统一框架。同时，我们在RAG-Gym框架内推出了ReSearch，一种将答案推理与搜索查询生成协同优化的创新代理架构。在四个具有挑战性的数据集上的实验表明，RAG-Gym使多种代理架构的性能提升了25.6%，ReSearch更是一贯超越现有基线。深入分析表明，先进LLMs可有效担任流程奖励评判员，且训练好的奖励模型可跨不同LLMs复用。此外，我们还研究了基于智能体的RAG在训练和推理方面的扩展特性。项目详情请访问https://rag-gym.github.io/。

> Retrieval-augmented generation (RAG) has shown great potential for knowledge-intensive tasks, but its traditional architectures rely on static retrieval, limiting their effectiveness for complex questions that require sequential information-seeking. While agentic reasoning and search offer a more adaptive approach, most existing methods depend heavily on prompt engineering. In this work, we introduce RAG-Gym, a unified optimization framework that enhances information-seeking agents through fine-grained process supervision at each search step. We also propose ReSearch, a novel agent architecture that synergizes answer reasoning and search query generation within the RAG-Gym framework. Experiments on four challenging datasets show that RAG-Gym improves performance by up to 25.6\% across various agent architectures, with ReSearch consistently outperforming existing baselines. Further analysis highlights the effectiveness of advanced LLMs as process reward judges and the transferability of trained reward models as verifiers for different LLMs. Additionally, we examine the scaling properties of training and inference in agentic RAG. The project homepage is available at https://rag-gym.github.io/.

[Arxiv](https://arxiv.org/abs/2502.13957)