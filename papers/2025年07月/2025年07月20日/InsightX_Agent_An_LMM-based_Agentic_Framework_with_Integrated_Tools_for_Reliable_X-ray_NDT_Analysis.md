# InsightX Agent: 基于LMM的智能体框架，集成专业工具实现可靠X射线无损检测分析

发布时间：2025年07月20日

`Agent` `工业检测` `人工智能`

> InsightX Agent: An LMM-based Agentic Framework with Integrated Tools for Reliable X-ray NDT Analysis

# 摘要

> 无损检测（NDT），尤其是X射线检测，在工业质量保证中至关重要。然而，现有基于深度学习的方法在交互性、可解释性和自我评估能力方面存在不足，限制了其可靠性和操作人员的信任。本文提出了一种名为InsightX Agent的新颖LMM代理框架，旨在提供可靠、可解释且交互式的X射线无损检测分析。与传统顺序化流水线不同，InsightX Agent将大型多模态模型（LMM）作为中央协调器，协调稀疏可变形多尺度检测器（SDMSD）和基于证据的反思工具（EGR）。SDMSD生成多尺度特征图的密集缺陷区域建议，并通过非极大值抑制（NMS）进行稀疏化处理，优化X射线图像中小而密集目标的检测，同时保持计算效率。EGR工具通过基于链式推理的审查流程引导LMM代理，整合背景评估、单个缺陷分析、误报消除、置信度校准和质量保证功能，以验证并优化SDMSD的初始建议。通过策略性地运用和智能使用工具，InsightX Agent超越了被动数据处理，实现了主动推理，从而提高了诊断的可靠性，并提供了整合多种信息源的解释。在GDXray+数据集上的实验评估表明，InsightX Agent不仅实现了高达96.35%的目标检测F1分数，还显著提升了分析的可解释性和可信度，凸显了代理型LLM框架在工业检测任务中的变革潜力。

> Non-destructive testing (NDT), particularly X-ray inspection, is vital for industrial quality assurance, yet existing deep-learning-based approaches often lack interactivity, interpretability, and the capacity for critical self-assessment, limiting their reliability and operator trust. To address these shortcomings, this paper proposes InsightX Agent, a novel LMM-based agentic framework designed to deliver reliable, interpretable, and interactive X-ray NDT analysis. Unlike typical sequential pipelines, InsightX Agent positions a Large Multimodal Model (LMM) as a central orchestrator, coordinating between the Sparse Deformable Multi-Scale Detector (SDMSD) and the Evidence-Grounded Reflection (EGR) tool. The SDMSD generates dense defect region proposals for multi-scale feature maps and sparsifies them through Non-Maximum Suppression (NMS), optimizing detection of small, dense targets in X-ray images while maintaining computational efficiency. The EGR tool guides the LMM agent through a chain-of-thought-inspired review process, incorporating context assessment, individual defect analysis, false positive elimination, confidence recalibration and quality assurance to validate and refine the SDMSD's initial proposals. By strategically employing and intelligently using tools, InsightX Agent moves beyond passive data processing to active reasoning, enhancing diagnostic reliability and providing interpretations that integrate diverse information sources. Experimental evaluations on the GDXray+ dataset demonstrate that InsightX Agent not only achieves a high object detection F1-score of 96.35% but also offers significantly improved interpretability and trustworthiness in its analyses, highlighting the transformative potential of agentic LLM frameworks for industrial inspection tasks.

[Arxiv](https://arxiv.org/abs/2507.14899)