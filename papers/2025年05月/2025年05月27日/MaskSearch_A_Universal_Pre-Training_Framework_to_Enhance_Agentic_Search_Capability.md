# MaskSearch：提升智能搜索能力的通用预训练框架

发布时间：2025年05月27日

`Agent` `问答系统` `多跳问答`

> MaskSearch: A Universal Pre-Training Framework to Enhance Agentic Search Capability

# 摘要

> 检索增强语言模型（RALMs）是一种经典范式，通过检索外部知识来提升生成能力。近期代理技术的进步使大型语言模型（LLMs）能够自主利用工具进行检索、规划和推理。虽然现有基于训练的方法展现出潜力，但任务特定数据的固有特性限制了它们的代理能力。为了进一步提升代理的通用搜索能力，我们提出了一种全新的预训练框架——MaskSearch。在预训练阶段，我们引入了检索增强的遮蔽预测（RAMP）任务，模型通过学习在大量预训练数据上利用搜索工具填充遮蔽片段，从而获得LLMs的通用检索和推理能力。之后，模型在下游任务上进行进一步训练以实现性能提升。我们采用了监督微调（SFT）和强化学习（RL）两种训练方式。对于SFT，我们结合了基于代理和基于蒸馏的方法来生成训练数据，从包含规划器、重写器和观察者的多代理系统开始，随后采用自我演进的教师模型。而对于RL，我们采用DAPO作为训练框架，并采用包含答案奖励和格式奖励的混合奖励系统。此外，我们引入了一种课程学习方法，使模型能够根据遮蔽片段的数量逐步从简单实例学习到更具挑战性的实例。我们在开放领域多跳问答场景下评估了我们的框架。通过大量实验，我们证明MaskSearch显著提升了LLM基搜索代理在域内和跨域下游任务上的性能。

> Retrieval-Augmented Language Models (RALMs) represent a classic paradigm where models enhance generative capabilities using external knowledge retrieved via a specialized module. Recent advancements in Agent techniques enable Large Language Models (LLMs) to autonomously utilize tools for retrieval, planning, and reasoning. While existing training-based methods show promise, their agentic abilities are limited by inherent characteristics of the task-specific data used during training. To further enhance the universal search capability of agents, we propose a novel pre-training framework, MaskSearch. In the pre-training stage, we introduce the Retrieval Augmented Mask Prediction (RAMP) task, where the model learns to leverage search tools to fill masked spans on a large number of pre-training data, thus acquiring universal retrieval and reasoning capabilities for LLMs. After that, the model is trained on downstream tasks to achieve further improvement. We apply both Supervised Fine-tuning (SFT) and Reinforcement Learning (RL) for training. For SFT, we combine agent-based and distillation-based methods to generate training data, starting with a multi-agent system consisting of a planner, rewriter, observer, and followed by a self-evolving teacher model. While for RL, we employ DAPO as the training framework and adopt a hybrid reward system consisting of answer rewards and format rewards. Additionally, we introduce a curriculum learning approach that allows the model to learn progressively from easier to more challenging instances based on the number of masked spans. We evaluate the effectiveness of our framework in the scenario of open-domain multi-hop question answering. Through extensive experiments, we demonstrate that MaskSearch significantly enhances the performance of LLM-based search agents on both in-domain and out-of-domain downstream tasks.

[Arxiv](https://arxiv.org/abs/2505.20285)