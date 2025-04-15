# M1：迈向可扩展测试时间计算，基于Mamba推理模型

发布时间：2025年04月14日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在推理能力方面的改进，特别是针对长链式推理和上下文扩展的限制。作者提出了一种新型的混合线性RNN推理模型，并结合知识蒸馏和强化学习来优化模型性能。这些内容属于模型理论和架构的创新，因此归类为LLM理论。` `RNN`

> M1: Towards Scalable Test-Time Compute with Mamba Reasoning Models

# 摘要

> 解决复杂数学问题需要有效的推理能力。近期大型语言模型（LLMs）通过长链式推理在推理过程中的计算扩展，显著提升了性能。然而，基于Transformer的模型在扩展上下文长度方面存在固有限制，主要源于其二次计算复杂度和线性内存需求。本文提出了一种基于Mamba架构的新型混合线性RNN推理模型M1，支持内存高效推理。我们的方法结合了知识蒸馏和强化学习（RL）训练，进一步优化了模型性能。实验结果表明，M1不仅超越了以往的线性RNN模型，而且在相近规模下，其性能可与Deepseek R1蒸馏推理模型相媲美。与高性能通用推理引擎vLLM对比，M1的生成速度提升了超过3倍。凭借吞吐量的提升，我们在固定生成时间预算下，通过自我一致性投票（self-consistency voting）实现了比DeepSeek R1蒸馏Transformer推理模型更高的准确性。总体而言，我们提出了一种混合Mamba推理模型，并为通过自我一致性或长链式推理进行测试时间生成扩展提供了一种更有效的方法。

> Effective reasoning is crucial to solving complex mathematical problems. Recent large language models (LLMs) have boosted performance by scaling test-time computation through long chain-of-thought reasoning. However, transformer-based models are inherently limited in extending context length due to their quadratic computational complexity and linear memory requirements. In this paper, we introduce a novel hybrid linear RNN reasoning model, M1, built on the Mamba architecture, which allows memory-efficient inference. Our approach leverages a distillation process from existing reasoning models and is further enhanced through RL training. Experimental results on the AIME and MATH benchmarks show that M1 not only outperforms previous linear RNN models but also matches the performance of state-of-the-art Deepseek R1 distilled reasoning models at a similar scale. We also compare our generation speed with a highly performant general purpose inference engine, vLLM, and observe more than a 3x speedup compared to a same size transformer. With throughput speedup, we are able to achieve higher accuracy compared to DeepSeek R1 distilled transformer reasoning models under a fixed generation time budget using self-consistency voting. Overall, we introduce a hybrid Mamba reasoning model and provide a more effective approach to scaling test-time generation using self-consistency or long chain of thought reasoning.

[Arxiv](https://arxiv.org/abs/2504.10449)