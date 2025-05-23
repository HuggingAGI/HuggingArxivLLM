# # ARB：全面的阿拉伯语多模态推理基准

发布时间：2025年05月22日

`LLM应用

理由：这篇论文专注于评估和应用多模态模型在阿拉伯语推理任务中的表现，开发了一个基准测试来评估模型在不同领域的推理能力，属于LLM应用的范畴。` `语言学` `多模态推理`

> ARB: A Comprehensive Arabic Multimodal Reasoning Benchmark

# 摘要

> 随着大型多模态模型（LMMs）能力的不断提升，人们对评估其推理过程和最终输出的兴趣也日益浓厚。然而，大多数基准测试仍主要集中在英语上，忽视了具有丰富语言和文化背景的语言，如阿拉伯语。为了解决这一问题，我们推出了综合阿拉伯语多模态推理基准（ARB），这是首个专注于评估阿拉伯语跨文本和视觉模态逐步推理能力的基准测试。ARB涵盖了11个不同领域，包括视觉推理、文档理解、OCR、科学分析和文化解读，包含1,356个多模态样本，每个样本都配有5,119个人工整理的推理步骤和相应操作。我们对12个最先进的开源和闭源LMM进行了评估，发现它们在连贯性、忠实性和文化根基方面仍面临诸多挑战。ARB为诊断欠代表性语言的多模态推理提供了一个结构化的框架，标志着迈向包容、透明和文化感知的AI系统的关键一步。我们已发布基准、评分标准和评估套件，以支持未来的研究和可重复性。代码可在以下链接获取：https://github.com/mbzuai-oryx/ARB

> As Large Multimodal Models (LMMs) become more capable, there is growing interest in evaluating their reasoning processes alongside their final outputs. However, most benchmarks remain focused on English, overlooking languages with rich linguistic and cultural contexts, such as Arabic. To address this gap, we introduce the Comprehensive Arabic Multimodal Reasoning Benchmark (ARB), the first benchmark designed to evaluate step-by-step reasoning in Arabic across both textual and visual modalities. ARB spans 11 diverse domains, including visual reasoning, document understanding, OCR, scientific analysis, and cultural interpretation. It comprises 1,356 multimodal samples paired with 5,119 human-curated reasoning steps and corresponding actions. We evaluated 12 state-of-the-art open- and closed-source LMMs and found persistent challenges in coherence, faithfulness, and cultural grounding. ARB offers a structured framework for diagnosing multimodal reasoning in underrepresented languages and marks a critical step toward inclusive, transparent, and culturally aware AI systems. We release the benchmark, rubric, and evaluation suit to support future research and reproducibility. Code available at: https://github.com/mbzuai-oryx/ARB

[Arxiv](https://arxiv.org/abs/2505.17021)