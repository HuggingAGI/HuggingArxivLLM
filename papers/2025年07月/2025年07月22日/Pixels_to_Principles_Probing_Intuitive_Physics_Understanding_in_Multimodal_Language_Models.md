# 从像素到原理：探究多模态语言模型的直观物理理解能力

发布时间：2025年07月22日

`LLM应用` `教育技术`

> Pixels to Principles: Probing Intuitive Physics Understanding in Multimodal Language Models

# 摘要

> 本文系统性评估了当前最先进的多模态大型语言模型（MLLMs）在直觉物理任务上的表现，采用GRASP和IntPhys 2数据集进行测试。我们对开源模型InternVL 2.5、Qwen 2.5 VL、LLaVA-OneVision以及专有模型Gemini 2.0 Flash Thinking进行了评估，发现即使是最新模型也难以可靠地区分物理上合理与不合理的场景。为了超越单纯的性能指标，我们对模型嵌入进行了探针分析，在关键处理阶段提取中间表示，以评估任务相关信息的保存情况。研究结果表明，根据任务难度的不同，视觉-语言模态之间会出现关键性对齐问题：视觉编码器能够成功捕获物理合理性的线索，但这些信息未能被语言模型有效利用，导致推理失败。这种对齐问题表明，MLLMs在直觉物理任务上的主要限制并非视觉组件，而是视觉与语言信息整合的有效性。我们的研究结果强调了视觉-语言对齐作为改进的关键方向，为未来MLLMs的发展提供了重要启示。


> This paper presents a systematic evaluation of state-of-the-art multimodal large language models (MLLMs) on intuitive physics tasks using the GRASP and IntPhys 2 datasets. We assess the open-source models InternVL 2.5, Qwen 2.5 VL, LLaVA-OneVision, and the proprietary Gemini 2.0 Flash Thinking, finding that even the latest models struggle to reliably distinguish physically plausible from implausible scenarios. To go beyond performance metrics, we conduct a probing analysis of model embeddings, extracting intermediate representations at key processing stages to examine how well task-relevant information is preserved. Our results show that, depending on task difficulty, a critical vision-language misalignment can emerge: vision encoders successfully capture physical plausibility cues, but this information is not effectively utilized by the language model, leading to failures in reasoning. This misalignment suggests that the primary limitation of MLLMs in intuitive physics tasks is not the vision component but the ineffective integration of visual and linguistic information. Our findings highlight vision-language alignment as a key area for improvement, offering insights for future MLLMs development.

[Arxiv](https://arxiv.org/abs/2507.16572)