# # Enabling On-Device Medical AI Assistants via Input-Driven Saliency Adaptation
基于输入驱动显著性适应打造设备端医疗AI助手

发布时间：2025年06月06日

`LLM应用` `边缘计算`

> Enabling On-Device Medical AI Assistants via Input-Driven Saliency Adaptation

# 摘要

> 大型语言模型（LLMs）在医疗领域影响深远，但在实时、资源受限的环境中（如边缘设备）部署时，其规模仍显庞大。本研究提出了一种新型医疗助手系统，通过我们的通用压缩框架优化，使其在特定领域内高效部署。该系统基于特定领域数据测量神经元的重要性，从而激进地剪裁不相关的神经元，显著减小模型体积，同时保持性能。剪裁后，我们采用后训练量化技术进一步降低内存占用，并在MedMCQA、MedQA和PubMedQA等医学基准测试中评估压缩模型的表现。此外，我们将压缩50%的Gemma模型和压缩67%的LLaMA3模型部署于Jetson Orin Nano（峰值18.7瓦）和Raspberry Pi 5（峰值6.3瓦）设备上，在硬件资源限制下实现了实时、节能的推理能力。

> Large Language Models (LLMs) have significant impact on the healthcare scenarios but remain prohibitively large for deployment in real-time, resource-constrained environments such as edge devices. In this work, we introduce a novel medical assistant system, optimized through our general-purpose compression framework, which tailors Large Language Models (LLMs) for deployment in specialized domains. By measuring neuron saliency on domain-specific data, our method can aggressively prune irrelevant neurons, reducing model size while preserving performance. Following pruning, we apply post-training quantization to further reduce the memory footprint, and evaluate the compressed model across medical benchmarks including MedMCQA, MedQA, and PubMedQA. We also deploy the 50\% compressed Gemma and the 67\% compressed LLaMA3 models on Jetson Orin Nano (18.7W peak) and Raspberry Pi 5 (6.3W peak), achieving real-time, energy-efficient inference under hardware constraints.

[Arxiv](https://arxiv.org/abs/2506.11105)