# 大型音频语言模型对音频的理解能力如何？语音、场景与事件理解基准（LALMs）

发布时间：2025年09月16日

`LLM应用` `媒体与娱乐`

> Can Large Audio Language Models Understand Audio Well? Speech, Scene and Events Understanding Benchmark for LALMs

# 摘要

> 近年来，大型音频语言模型（LALMs）发展迅猛，凭借跨模态融合在通用音频理解领域展现出强劲实力。为评估其音频理解能力，研究人员已构建多种基准测试集。但现有测试集尚未充分探索现实交互中的关键特性：音频信号通常混合语音与非语音成分，且二者能量水平在不同场景中差异显著；同时，多数测试集未涉及对同一音频片段中语音、场景与事件的联合理解。为此，本研究提出SSEU-Bench——首个多功能音频理解基准测试集，明确考虑语音与非语音音频的能量差异，并涵盖语音、场景和事件的独立理解与联合理解设置。研究还发现，部分LALM在联合理解场景下的特定任务中表现不佳。为解决此问题，我们引入思维链（Chain-of-Thought），将复杂任务拆解为简单推理步骤，从而有效提升LALM的联合音频理解性能。

> Recently, Large Audio Language Models (LALMs) have progressed rapidly, demonstrating their strong efficacy in universal audio understanding through cross-modal integration. To evaluate the LALM's audio understanding performance, researchers have proposed different benchmarks. However, key aspects for real-world interactions are underexplored in existing benchmarks, i.e., audio signals typically contain both speech and non-speech components, and energy levels of these components can vary significantly across different scenarios. Moreover, most benchmarks do not consider the joint understanding of speech, scene, and events within the same audio clip. In this work, we introduce SSEU-Bench, the first versatile audio understanding benchmark that explicitly accounts for energy differences between speech and non-speech audio, with both independent and joint understanding settings for speech, scene, and events. Furthermore, we demonstrate that some LALMs tend to underperform on certain tasks in a joint understanding setting. To address this issue, we introduce Chain-of-Thought, which effectively improves the LALM's joint audio understanding performance by decomposing complex tasks into simpler reasoning steps

[Arxiv](https://arxiv.org/abs/2509.13148)