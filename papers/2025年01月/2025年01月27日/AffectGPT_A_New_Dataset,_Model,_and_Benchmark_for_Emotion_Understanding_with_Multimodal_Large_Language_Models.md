# AffectGPT: 多模态大语言模型情感理解的新数据集、模型与基准

发布时间：2025年01月27日

`LLM应用

**理由**：这篇论文主要讨论了多模态大型语言模型（MLLMs）在情感识别领域的应用，特别是通过构建新的数据集和模型（如AffectGPT）来提升情感理解的能力。论文的核心在于如何利用MLLMs来解决实际问题（情感识别），并提出了具体的应用框架和基准测试。因此，它属于**LLM应用**类别。` `情感分析`

> AffectGPT: A New Dataset, Model, and Benchmark for Emotion Understanding with Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）的崛起，将多模态情感识别（MER）推向了新高度——从简单的判别任务跃升至具备高级视频理解与自然语言描述的复杂情感理解。然而，当前领域面临两大挑战：一是缺乏大规模、密集描述性情感注释的数据集；二是缺少一个以多模态为核心的框架，以充分发挥MLLMs在情感理解上的潜力。为此，我们构建了一个全新的MLLM情感理解基准，包含创新数据集MER-Caption和模型AffectGPT。通过基于模型的众包数据收集策略，我们打造了迄今为止最大的描述性情感数据集，涵盖115K样本和超过2K细粒度情感类别。AffectGPT模型特别设计了预融合操作，以强化多模态整合。此外，我们推出了MER-UniBench，这是一个统一基准，其评估指标既适用于传统MER任务，也适配MLLMs的自由形式自然语言输出。大量实验验证了AffectGPT在各类MER任务中的卓越表现。我们公开了AffectGPT模型和MER-Caption数据集，旨在推动情感理解领域的深入探索与创新。

> The emergence of multimodal large language models (MLLMs) advances multimodal emotion recognition (MER) to the next level-from naive discriminative tasks to complex emotion understanding with advanced video understanding abilities and natural language description. However, the current community suffers from a lack of large-scale datasets with intensive, descriptive emotion annotations, as well as a multimodal-centric framework to maximize the potential of MLLMs for emotion understanding. To address this, we establish a new benchmark for MLLM-based emotion understanding with a novel dataset (MER-Caption), and a new model (AffectGPT). Utilizing our model-based crowd-sourcing data collection strategy, we construct the largest descriptive emotion dataset to date (by far), featuring over 2K fine-grained emotion categories across 115K samples. We also introduce the AffectGPT model, designed with pre-fusion operations to enhance multimodal integration. Finally, we present MER-UniBench, a unified benchmark with evaluation metrics tailored for both typical MER tasks and the free-form, natural language output style of MLLMs. Extensive experimental results demonstrate AffectGPT's robust performance across various MER tasks. We are publicly releasing both the AffectGPT model and the MER-Caption dataset to foster further research and development in emotion understanding.

[Arxiv](https://arxiv.org/abs/2501.16566)