# # AirLLM：基于扩散策略的自适应LoRA，用于大型语言模型的无线远程微调

发布时间：2025年07月15日

`LLM应用

摘要中的论文主要探讨了在资源受限的边缘设备上高效运行大型语言模型（LLMs）的方法，特别是通过优化低秩适配（LoRA）参数的传输和配置，提出了AirLLM框架。该研究属于将LLM应用于实际场景中的优化和改进，因此归类为LLM应用。` `边缘计算`

> AirLLM: Diffusion Policy-based Adaptive LoRA for Remote Fine-Tuning of LLM over the Air

# 摘要

> 在边缘设备上运行大型语言模型（LLMs）正面临通信带宽受限和计算内存成本紧张的挑战，因此云辅助远程微调变得不可或缺。然而，现有的低秩适配（LoRA）方法通常采用固定或启发式秩配置，且通过空中传输所有LoRA参数的效率较低。为了解决这一问题，我们开发了AirLLM，一个面向通信感知的LoRA适配的分层扩散策略框架。AirLLM将秩配置建模为跨越所有插入LoRA投影的结构化动作向量。为了解决高维序列决策问题，Proximal Policy Optimization（PPO）代理通过联合观察无线状态和语言复杂性生成粗粒度决策，然后通过Denoising Diffusion Implicit Models（DDIM）优化为高分辨率、任务和信道自适应的秩向量。这两个模块通过交替优化训练，其中DDIM在Classifier-Free Guidance（CFG）范式下训练以保持与PPO奖励一致。实验结果表明，AirLLM在不同信噪比下不仅显著提升了微调性能，还大幅降低了传输成本，充分证明了强化驱动、扩散优化的秩适配在大规模高效远程微调中的有效性。

> Operating Large Language Models (LLMs) on edge devices is increasingly challenged by limited communication bandwidth and strained computational and memory costs. Thus, cloud-assisted remote fine-tuning becomes indispensable. Nevertheless, existing Low-Rank Adaptation (LoRA) approaches typically employ fixed or heuristic rank configurations, and the subsequent over-the-air transmission of all LoRA parameters could be rather inefficient. To address this limitation, we develop AirLLM, a hierarchical diffusion policy framework for communication-aware LoRA adaptation. Specifically, AirLLM models the rank configuration as a structured action vector that spans all LoRA-inserted projections. To solve the underlying high-dimensional sequential decision-making problem, a Proximal Policy Optimization (PPO) agent generates coarse-grained decisions by jointly observing wireless states and linguistic complexity, which are then refined via Denoising Diffusion Implicit Models (DDIM) to produce high-resolution, task- and channel-adaptive rank vectors. The two modules are optimized alternatively, with the DDIM trained under the Classifier-Free Guidance (CFG) paradigm to maintain alignment with PPO rewards. Experiments under varying signal-to-noise ratios demonstrate that AirLLM consistently enhances fine-tuning performance while significantly reducing transmission costs, highlighting the effectiveness of reinforcement-driven, diffusion-refined rank adaptation for scalable and efficient remote fine-tuning over the air.

[Arxiv](https://arxiv.org/abs/2507.11515)