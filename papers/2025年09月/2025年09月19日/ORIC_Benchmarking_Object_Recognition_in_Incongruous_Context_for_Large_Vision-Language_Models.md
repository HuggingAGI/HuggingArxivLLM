# ORIC：大型视觉语言模型的不协调语境物体识别基准测试

发布时间：2025年09月19日

`LLM应用` `基础理论`

> ORIC: Benchmarking Object Recognition in Incongruous Context for Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）凭借视觉与文本信息的融合，在图像描述、视觉问答及机器人领域已取得显著突破。然而，在物体意外出现或语境中本应存在却缺失的不协调场景下，LVLMs仍易出错，进而导致两类关键识别问题：物体误判与幻觉生成。为系统探究此问题，我们提出了不协调语境物体识别基准（ORIC）——一个专门评估LVLMs在物体-语境关系违背预期场景下表现的全新基准。ORIC采用两大核心策略：（1）LLM引导采样，用于识别存在但语境不协调的物体；（2）CLIP引导采样，用于检测合理却不存在、易引发幻觉的物体，进而构建不协调语境。通过对18个LVLMs及两个开放词汇检测模型的评估，我们发现其存在显著识别短板，凸显了语境不协调带来的严峻挑战。这项研究深入揭示了LVLMs的局限性，同时为语境感知物体识别领域的后续研究提供了重要启示。

> Large Vision-Language Models (LVLMs) have made significant strides in image caption, visual question answering, and robotics by integrating visual and textual information. However, they remain prone to errors in incongruous contexts, where objects appear unexpectedly or are absent when contextually expected. This leads to two key recognition failures: object misidentification and hallucination. To systematically examine this issue, we introduce the Object Recognition in Incongruous Context Benchmark (ORIC), a novel benchmark that evaluates LVLMs in scenarios where object-context relationships deviate from expectations. ORIC employs two key strategies: (1) LLM-guided sampling, which identifies objects that are present but contextually incongruous, and (2) CLIP-guided sampling, which detects plausible yet nonexistent objects that are likely to be hallucinated, thereby creating an incongruous context. Evaluating 18 LVLMs and two open-vocabulary detection models, our results reveal significant recognition gaps, underscoring the challenges posed by contextual incongruity. This work provides critical insights into LVLMs' limitations and encourages further research on context-aware object recognition.

[Arxiv](https://arxiv.org/abs/2509.15695)