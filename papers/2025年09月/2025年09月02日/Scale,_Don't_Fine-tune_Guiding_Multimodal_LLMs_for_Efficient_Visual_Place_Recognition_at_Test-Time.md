# 扩展而非微调：测试时引导多模态LLM实现高效视觉地点识别

发布时间：2025年09月02日

`LLM应用` `交通运输`

> Scale, Don't Fine-tune: Guiding Multimodal LLMs for Efficient Visual Place Recognition at Test-Time

# 摘要

> 视觉地点识别（VPR）已从手工设计描述符演进到深度学习方法，但仍面临诸多挑战。当前方法（如视觉基础模型（VFMs）和多模态大型语言模型（MLLMs））虽增强了语义理解，但微调时存在计算开销大、跨域迁移能力弱的问题。为解决这些局限，我们提出一种新颖的零样本框架，该框架采用测试时缩放（TTS），通过基于引导的方法利用MLLMs的视觉-语言对齐能力直接进行相似度评分。该方法借助生成长度可控JSON输出的结构化提示，省去了两阶段处理步骤。集成不确定性感知自一致性（UASC）的TTS框架无需额外训练成本即可实现实时适应，在多样环境中泛化性能优异。实验结果显示，该方法在跨域VPR任务上性能显著提升，计算效率更是提高了210倍。

> Visual Place Recognition (VPR) has evolved from handcrafted descriptors to deep learning approaches, yet significant challenges remain. Current approaches, including Vision Foundation Models (VFMs) and Multimodal Large Language Models (MLLMs), enhance semantic understanding but suffer from high computational overhead and limited cross-domain transferability when fine-tuned. To address these limitations, we propose a novel zero-shot framework employing Test-Time Scaling (TTS) that leverages MLLMs' vision-language alignment capabilities through Guidance-based methods for direct similarity scoring. Our approach eliminates two-stage processing by employing structured prompts that generate length-controllable JSON outputs. The TTS framework with Uncertainty-Aware Self-Consistency (UASC) enables real-time adaptation without additional training costs, achieving superior generalization across diverse environments. Experimental results demonstrate significant improvements in cross-domain VPR performance with up to 210$\times$ computational efficiency gains.

[Arxiv](https://arxiv.org/abs/2509.02129)