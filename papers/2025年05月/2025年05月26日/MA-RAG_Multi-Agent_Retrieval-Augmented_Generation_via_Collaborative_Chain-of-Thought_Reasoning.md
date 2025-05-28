# # MA-RAG：多智能体协作链式推理驱动的检索增强生成

发布时间：2025年05月26日

`Agent` `信息检索` `智能体协作`

> MA-RAG: Multi-Agent Retrieval-Augmented Generation via Collaborative Chain-of-Thought Reasoning

# 摘要

> 我们提出了MA-RAG，一个用于增强检索生成（RAG）的多智能体框架，旨在解决复杂信息检索任务中的模糊性和推理难题。与传统RAG方法不同，MA-RAG通过协调规划器、步骤定义器、提取器和问答智能体等专业AI智能体，以任务感知的方式处理RAG流水线的每个阶段。模糊性可能源于未明确的查询、稀疏证据或跨来源信息整合需求。MA-RAG通过将问题分解为查询消歧、证据提取和答案合成等子任务，并分配给配备链式思维提示的智能体，有效应对这些挑战。智能体通过中间推理通信，逐步优化检索和合成过程。我们的设计无需模型微调，即可实现信息流的精细控制。更重要的是，智能体按需调用，使工作流程动态高效，避免冗余计算。这种模块化和推理驱动的架构使MA-RAG能够提供稳健且可解释的结果。实验表明，MA-RAG超越了无训练的最先进基线，并与微调系统相媲美，充分验证了基于协作智能体推理在RAG中的有效性。

> We present MA-RAG, a Multi-Agent framework for Retrieval-Augmented Generation (RAG) that addresses the inherent ambiguities and reasoning challenges in complex information-seeking tasks. Unlike conventional RAG methods that rely on either end-to-end fine-tuning or isolated component enhancements, MA-RAG orchestrates a collaborative set of specialized AI agents: Planner, Step Definer, Extractor, and QA Agents, to tackle each stage of the RAG pipeline with task-aware reasoning. Ambiguities may arise from underspecified queries, sparse or indirect evidence in retrieved documents, or the need to integrate information scattered across multiple sources. MA-RAG mitigates these challenges by decomposing the problem into subtasks, such as query disambiguation, evidence extraction, and answer synthesis, and dispatching them to dedicated agents equipped with chain-of-thought prompting. These agents communicate intermediate reasoning and progressively refine the retrieval and synthesis process. Our design allows fine-grained control over information flow without any model fine-tuning. Crucially, agents are invoked on demand, enabling a dynamic and efficient workflow that avoids unnecessary computation. This modular and reasoning-driven architecture enables MA-RAG to deliver robust, interpretable results. Experiments on multi-hop and ambiguous QA benchmarks demonstrate that MA-RAG outperforms state-of-the-art training-free baselines and rivals fine-tuned systems, validating the effectiveness of collaborative agent-based reasoning in RAG.

[Arxiv](https://arxiv.org/abs/2505.20096)