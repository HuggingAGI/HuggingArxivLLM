# SIRAG：基于过程监督多智能体框架的稳定可解释检索增强生成（RAG）研究

发布时间：2025年09月17日

`RAG` `基础理论`

> SIRAG: Towards Stable and Interpretable RAG with A Process-Supervised Multi-Agent Framework

# 摘要

> 检索增强生成（RAG）技术让大型语言模型（LLMs）能够调用外部知识源，但其性能好坏取决于检索器与生成器的协同配合。由于这两个组件独立开发，两者的协同效果往往欠佳：检索器可能返回无关或冗余文档，生成器也可能无法充分利用检索到的证据。为此，我们提出一种过程监督的多智能体框架，旨在弥合检索器与生成器之间的鸿沟。该框架引入两个轻量级智能体：决策器（Decision Maker）负责判断是继续检索还是停止检索并开始生成答案；知识选择器（Knowledge Selector）则过滤检索文档，仅保留最有价值的证据。为实现细粒度监督，我们采用LLM作为评估器（LLM-as-a-Judge），对每个中间动作进行过程级奖励评估，从而实现比仅依赖最终答案正确性更精准的信用分配。我们进一步采用树状推演策略探索多样化推理路径，并通过近端策略优化（PPO）对两个智能体进行端到端训练。在单跳和多跳问答基准测试中，我们的方法相比标准RAG基线，不仅准确率更高、收敛更稳定，还能生成更可解释的推理轨迹。值得注意的是，该框架模块化且即插即用，无需修改检索器或生成器，适用于实际的RAG应用场景。

> Retrieval-Augmented Generation (RAG) enables large language models (LLMs) to access external knowledge sources, but the effectiveness of RAG relies on the coordination between the retriever and the generator. Since these components are developed independently, their interaction is often suboptimal: the retriever may return irrelevant or redundant documents, while the generator may fail to fully leverage retrieved evidence. In this work, we propose a process-supervised multi-agent framework to bridge the gap between retriever and generator. The framework introduces two lightweight agents: a Decision Maker, which determines when to continue retrieval or stop for answer generation, and a Knowledge Selector, which filters retrieved documents to retain only the most useful evidence. To provide fine-grained supervision, we employ an LLM-as-a-Judge that evaluates each intermediate action with process-level rewards, ensuring more accurate credit assignment than relying solely on final answer correctness. We further adopt a tree-structured rollout strategy to explore diverse reasoning paths, and train both agents with Proximal Policy Optimization (PPO) in an end-to-end manner. Experiments on single-hop and multi-hop question answering benchmarks show that our approach achieves higher accuracy, more stable convergence, and produces more interpretable reasoning trajectories compared with standard RAG baselines. Importantly, the proposed framework is modular and plug-and-play, requiring no modification to the retriever or generator, making it practical for real-world RAG applications.

[Arxiv](https://arxiv.org/abs/2509.18167)