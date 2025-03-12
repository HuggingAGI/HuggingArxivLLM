# 大型语言模型：数据驱动多任务优化的元代理概念验证研究

发布时间：2025年03月11日

`Agent` `优化算法` `机器学习`

> Large Language Model as Meta-Surrogate for Data-Driven Many-Task Optimization: A Proof-of-Principle Study

# 摘要

> 在多任务优化领域，代理模型能有效减轻重复适应度评估的计算负担。本研究提出了一种基于LLMs的元代理框架，通过知识迁移与多任务学习，构建统一的适应度预测模型。该框架以元数据和决策变量为输入，实现跨任务知识共享与快速适应。通过将适应度预测转化为条件概率估计，并采用统一的令牌序列表示方法，模型不仅实现了高效的知识迁移，还捕捉到了复杂的任务依赖关系。实验表明，该框架展现出强大的零样本泛化能力。在进化转移优化（ETO）中，该框架支持代理与个体层面的双层知识转移，显著提升了优化效率与鲁棒性。本研究为LLMs在代理建模中的应用提供了新思路，为多任务优化问题提供了一种灵活高效的解决方案。

> In many-task optimization scenarios, surrogate models are valuable for mitigating the computational burden of repeated fitness evaluations across tasks. This study proposes a novel meta-surrogate framework to assist many-task optimization, by leveraging the knowledge transfer strengths and emergent capabilities of large language models (LLMs). We formulate a unified framework for many-task fitness prediction, by defining a universal model with metadata to fit a group of problems. Fitness prediction is performed on metadata and decision variables, enabling efficient knowledge sharing across tasks and adaptability to new tasks. The LLM-based meta-surrogate treats fitness prediction as conditional probability estimation, employing a unified token sequence representation for task metadata, inputs, and outputs. This approach facilitates efficient inter-task knowledge sharing through shared token embeddings and captures complex task dependencies via multi-task model training. Experimental results demonstrate the model's emergent generalization ability, including zero-shot performance on problems with unseen dimensions. When integrated into evolutionary transfer optimization (ETO), our framework supports dual-level knowledge transfer -- at both the surrogate and individual levels -- enhancing optimization efficiency and robustness. This work establishes a novel foundation for applying LLMs in surrogate modeling, offering a versatile solution for many-task optimization.

[Arxiv](https://arxiv.org/abs/2503.08301)