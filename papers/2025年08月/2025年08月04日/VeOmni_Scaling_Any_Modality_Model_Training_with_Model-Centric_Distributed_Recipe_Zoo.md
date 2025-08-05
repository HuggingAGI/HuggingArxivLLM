# VeOmni：通过模型为中心的分布式配方集合扩展任意模态模型训练

发布时间：2025年08月04日

`LLM理论

理由：这篇论文探讨了多模态大型语言模型（LLMs）的训练挑战，并提出了一种新的高效训练框架eomni。它专注于优化训练过程和系统设计，属于LLM的理论和方法层面。` `人工智能` `系统设计`

> VeOmni: Scaling Any Modality Model Training with Model-Centric Distributed Recipe Zoo

# 摘要

> 大型语言模型（LLMs）的最新进展在多模态理解和生成方面取得了显著突破。然而，由于需要处理多种模态的异构模型架构，训练多模态LLMs仍然面临重大挑战，这对高效大规模训练的系统设计提出了复杂要求。现有框架通常将模型定义与并行逻辑纠缠在一起，导致端到端多模态训练的可扩展性有限，并带来显著的工程开销。

我们提出了eomni，这是一个模块化且高效的训练框架，旨在加速多模态LLMs的开发。通过引入以模型为中心的分布式策略，eomni实现了通信与计算的解耦，从而在多模态LLMs上实现了高效的三维并行。此外，eomni还提供了一个灵活的配置界面，支持通过极小的代码改动无缝集成新的模态。

借助eomni，一个包含300亿参数的多模态专家混合模型（MoE）可以在128个GPU上实现超过2,800 tokens/sec/GPU的吞吐量，并通过三维并行扩展至160,000的上下文长度，充分展现了其在训练大型多模态LLMs方面的卓越效率和可扩展性。

> Recent advances in large language models (LLMs) have driven impressive progress in omni-modal understanding and generation. However, training omni-modal LLMs remains a significant challenge due to the heterogeneous model architectures required to process diverse modalities, necessitating sophisticated system design for efficient large-scale training. Existing frameworks typically entangle model definition with parallel logic, incurring limited scalability and substantial engineering overhead for end-to-end omni-modal training. %
We present \veomni, a modular and efficient training framework to accelerate the development of omni-modal LLMs. \veomni introduces model-centric distributed recipes that decouples communication from computation, enabling efficient 3D parallelism on omni-modal LLMs. \veomni also features a flexible configuration interface supporting seamless integration of new modalities with minimal code change. %
Using \veomni, a omni-modal mixture-of-experts (MoE) model with 30B parameters can be trained with over 2,800 tokens/sec/GPU throughput and scale to 160K context lengths via 3D parallelism on 128 GPUs, showcasing its superior efficiency and scalability for training large omni-modal LLMs.

[Arxiv](https://arxiv.org/abs/2508.02317)