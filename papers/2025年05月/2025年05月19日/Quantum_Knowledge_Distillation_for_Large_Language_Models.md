# 量子知识蒸馏用于大型语言模型

发布时间：2025年05月19日

`LLM应用` `模型压缩`

> Quantum Knowledge Distillation for Large Language Models

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域发挥着重要作用，广泛应用于机器翻译和内容创作。然而，随着模型规模的扩大，资源消耗也急剧增加。量子计算凭借其在处理量子特性问题上的独特优势，为这一挑战提供了新思路。本文提出了一种结合量子计算的LLMs蒸馏算法——QD-LLM，旨在降低模型加载和推理的资源需求。具体来说，蒸馏过程中，数据同时输入LLMs和量子学生模型，初步量化两者输出差异；随后，基于真实标签优化量子学生模型，使其输出更接近LLMs。整个过程仅更新量子学生模型参数，最终获得的优化模型能够在推理阶段独立高效完成特定任务。实验表明，QD-LLM在减少训练参数、内存消耗、训练和推理时间方面表现优异，同时性能得以保持。此外，其优化模型在特定任务上超越了专门设计的模型。我们相信，QD-LLM为探索量子计算在模型压缩中的应用奠定了基础，并有望扩展到更多NLP挑战中。

> Large Language Models (LLMs) are integral to advancing natural language processing, used extensively from machine translation to content creation. However, as these models scale to billions of parameters, their resource demands increase dramatically. Meanwhile, quantum computing is recognized for efficiently solving complex problems with quantum characteristics like superposition and entanglement, providing a novel approach to these challenges. This paper attempts to combine quantum computing with LLMs and proposes a Quantum knowledge Distillation algorithm for LLMs (QD-LLM), aimed at reducing the computational and memory overhead required for model loading and inference. Specifically, during the distillation stage, data is fed simultaneously into both the LLMs and the designed quantum student model to initially quantify the difference between their outputs; subsequently, with the help of the true label, the optimization of the quantum student model is executed to minimize the difference with the LLM's output. Throughout this process, only the parameters of the quantum student network are updated to make its output closer to that of the LLMs, thereby achieving the purpose of distillation. Finally, the optimized student model obtained by QD-LLM can efficiently solve domain-specific tasks during inference without the usage of the original LLMs. Experimental results show that, compared to mainstream compression methods, QD-LLM significantly reduces the number of training parameters, memory consumption, training time, and inference time while maintaining performance. Moreover, the optimized student model obtained by QD-LLM surpasses specific models designed for these tasks. We believe that QD-LLM can lay the groundwork for exploring the utilization of quantum computing in model compression and its potential extension to other natural language processing challenges.

[Arxiv](https://arxiv.org/abs/2505.13205)