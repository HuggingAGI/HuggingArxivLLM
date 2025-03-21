# # 以视觉为中心的遥感基准测试

发布时间：2025年03月19日

`LLM应用` `多模态学习`

> A Vision Centric Remote Sensing Benchmark

# 摘要

> 多模态大型语言模型 (MLLMs) 在视觉语言任务中表现优异，但在遥感 (RS) 领域的应用尚处于探索阶段。与自然图像不同，RS图像的独特挑战让当前MLLMs在视觉定位和空间推理方面力有未逮。本研究聚焦基于CLIP的MLLMs在RS任务中的局限性，揭示了它们难以区分视觉差异显著但语义相近的RS图像。为此，我们提出了一个遥感多模态视觉模式 (RSMMVP) 基准测试，通过识别CLIP盲配对（即CLIP模型错误地为视觉差异显著的RS图像分配高相似性得分的情况），评估MLLMs在RS任务中的表现。通过视觉问答 (VQA) 评估，我们分析了当前最先进的MLLMs的表现，揭示了它们在特定于RS的表示学习方面的显著局限性。研究结果不仅为CLIP视觉编码的弱点提供了深刻见解，更为未来开发更有效的MLLMs奠定了基础，这些模型专门针对遥感应用进行优化。

> Multimodal Large Language Models (MLLMs) have achieved remarkable success in vision-language tasks but their remote sensing (RS) counterpart are relatively under explored. Unlike natural images, RS imagery presents unique challenges that current MLLMs struggle to handle, particularly in visual grounding and spatial reasoning. This study investigates the limitations of CLIP-based MLLMs in RS, highlighting their failure to differentiate visually distinct yet semantically similar RS images. To address this, we introduce a remote sensing multimodal visual patterns (RSMMVP) benchmark. It is designed to evaluate MLLMs in RS tasks by identifying the CLIP-blind pairs, where CLIP-based models incorrectly assign high similarity scores to visually distinct RS images. Through a visual question answering (VQA) evaluation, we analyze the performance of state-of-the-art MLLMs, revealing significant limitations in RS specific representation learning. The results provide valuable insights into the weaknesses of CLIP-based visual encoding and offer a foundation for future research to develop more effective MLLMs tailored for remote sensing applications.

[Arxiv](https://arxiv.org/abs/2503.15816)