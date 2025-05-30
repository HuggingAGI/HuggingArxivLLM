# MoRE：自适应多任务学习的低秩专家混合方法

发布时间：2025年05月28日

`LLM理论` `人工智能` `机器学习`

> MoRE: A Mixture of Low-Rank Experts for Adaptive Multi-Task Learning

# 摘要

> 大型语言模型（LLMs）的快速发展推动了参数高效微调（PEFT）方法的广泛应用，其核心目标是以更少的参数实现LLMs的高效微调。作为PEFT领域的代表，低秩适配（LoRA）通过引入低秩矩阵近似增量微调参数，在多个场景中展现了卓越性能。随后，研究者提出了多种改进方案，但这些方法大多局限于单任务场景，或通过为多任务场景分别训练多个LoRA模块，导致LoRA在多任务场景中的效率和效果受限。为了解决这一问题，我们提出了一种新型的低秩专家混合（MoRE），专为多任务PEFT设计。具体而言，我们摒弃了传统的为每个任务单独使用一个LoRA的做法，而是将不同秩的LoRA模块与不同任务对齐，形成低秩专家。同时，我们设计了一种自适应秩选择器，能够智能选择适合每个任务的专家。通过联合训练这些低秩专家，MoRE显著提升了LoRA在多任务场景中的适应性和效率。我们还在多个多任务基准测试和不同LLMs上进行了全面实验，结果表明，与传统LoRA及其变体相比，MoRE在多任务场景中实现了性能的显著提升，且不会增加推理成本。此外，我们开源了模型和代码，以促进社区的进一步研究与应用。

> With the rapid development of Large Language Models (LLMs), Parameter-Efficient Fine-Tuning (PEFT) methods have gained significant attention, which aims to achieve efficient fine-tuning of LLMs with fewer parameters. As a representative PEFT method, Low-Rank Adaptation (LoRA) introduces low-rank matrices to approximate the incremental tuning parameters and achieves impressive performance over multiple scenarios. After that, plenty of improvements have been proposed for further improvement. However, these methods either focus on single-task scenarios or separately train multiple LoRA modules for multi-task scenarios, limiting the efficiency and effectiveness of LoRA in multi-task scenarios. To better adapt to multi-task fine-tuning, in this paper, we propose a novel Mixture of Low-Rank Experts (MoRE) for multi-task PEFT. Specifically, instead of using an individual LoRA for each task, we align different ranks of LoRA module with different tasks, which we named low-rank experts. Moreover, we design a novel adaptive rank selector to select the appropriate expert for each task. By jointly training low-rank experts, MoRE can enhance the adaptability and efficiency of LoRA in multi-task scenarios. Finally, we conduct extensive experiments over multiple multi-task benchmarks along with different LLMs to verify model performance. Experimental results demonstrate that compared to traditional LoRA and its variants, MoRE significantly improves the performance of LLMs in multi-task scenarios and incurs no additional inference cost. We also release the model and code to facilitate the community.

[Arxiv](https://arxiv.org/abs/2505.22694)