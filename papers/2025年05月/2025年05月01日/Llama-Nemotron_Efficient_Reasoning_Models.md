# # Llama-Nemotron：高效推理模型的构建

发布时间：2025年05月01日

`LLM应用`

> Llama-Nemotron: Efficient Reasoning Models

# 摘要

> 我们很高兴推出 Llama-Nemotron 系列模型，这是一个开放的异构推理模型家族，具备卓越的推理能力、推理效率以及适用于企业使用的开放许可证。该家族包含三种规模的模型—— Nano（80亿参数）、Super（490亿参数）和Ultra（2530亿参数）——它们在与目前最先进的推理模型（如 DeepSeek-R1）竞争中表现出色，同时提供了更优的推理吞吐量和内存效率。

在本报告中，我们将探讨这些模型的训练过程，其中包括从 Llama 3 模型中使用神经架构搜索以加速推理，知识蒸馏，以及持续预训练，随后进入以推理为核心的后训练阶段，该阶段主要分为两个部分：监督微调和大规模强化学习。Llama-Nemotron 模型是首个支持动态推理切换的开源模型，允许用户在推理过程中在标准聊天模式和推理模式之间进行切换。

为了进一步支持开放研究并促进模型开发，我们提供了以下资源：
1. 我们在商业许可的 NVIDIA 开源模型协议下发布了 Llama-Nemotron 推理模型——LN-Nano、LN-Super 和 LN-Ultra。
2. 我们发布了完整的后训练数据集：Llama-Nemotron-Post-Training-Dataset。
3. 我们还发布了我们的训练代码库：NeMo、NeMo-Aligner 和 Megatron-LM。


> We introduce the Llama-Nemotron series of models, an open family of heterogeneous reasoning models that deliver exceptional reasoning capabilities, inference efficiency, and an open license for enterprise use. The family comes in three sizes -- Nano (8B), Super (49B), and Ultra (253B) -- and performs competitively with state-of-the-art reasoning models such as DeepSeek-R1 while offering superior inference throughput and memory efficiency. In this report, we discuss the training procedure for these models, which entails using neural architecture search from Llama 3 models for accelerated inference, knowledge distillation, and continued pretraining, followed by a reasoning-focused post-training stage consisting of two main parts: supervised fine-tuning and large scale reinforcement learning. Llama-Nemotron models are the first open-source models to support a dynamic reasoning toggle, allowing users to switch between standard chat and reasoning modes during inference. To further support open research and facilitate model development, we provide the following resources: 1. We release the Llama-Nemotron reasoning models -- LN-Nano, LN-Super, and LN-Ultra -- under the commercially permissive NVIDIA Open Model License Agreement. 2. We release the complete post-training dataset: Llama-Nemotron-Post-Training-Dataset. 3. We also release our training codebases: NeMo, NeMo-Aligner, and Megatron-LM.

[Arxiv](https://arxiv.org/abs/2505.00949)