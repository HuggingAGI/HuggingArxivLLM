# 奉承之舞：视频LLMs中的阿谀行为基准测试与分析

发布时间：2025年06月08日

`LLM应用` `视频处理` `人工智能`

> Flattery in Motion: Benchmarking and Analyzing Sycophancy in Video-LLMs

# 摘要

> 视频大语言模型（Video-LLMs）在实际应用中越来越依赖基于视觉证据的多模态推理，因此确保其事实准确性和可靠性至关重要。然而，这些模型存在顺从性问题，即它们倾向于无条件认同用户输入，即便该输入与视觉证据相矛盾，这严重影响了它们的可信度。当前研究大多忽视了顺从性在视频语言领域的具体表现，缺乏系统性基准和针对性评估来深入理解 Video-LLMs 在面对误导性输入时的行为。为解决这一问题，我们提出了 VISE（视频-LLM 顺从性基准与评估），这是首个专注于评估前沿 Video-LLMs 顺从性行为的基准，覆盖多种问题形式、提示偏见和视觉推理任务。VISE 创新性地将语言学视角引入视觉领域，实现了对多种顺从性类型和交互模式的细致分析。此外，我们还提出了一种基于关键帧选择的可解释、无需训练的缓解策略，揭示了通过强化视觉接地来减少顺从性偏见的潜在路径。

> As video large language models (Video-LLMs) become increasingly integrated into real-world applications that demand grounded multimodal reasoning, ensuring their factual consistency and reliability is of critical importance. However, sycophancy, the tendency of these models to align with user input even when it contradicts the visual evidence, undermines their trustworthiness in such contexts. Current sycophancy research has largely overlooked its specific manifestations in the video-language domain, resulting in a notable absence of systematic benchmarks and targeted evaluations to understand how Video-LLMs respond under misleading user input. To fill this gap, we propose VISE (Video-LLM Sycophancy Benchmarking and Evaluation), the first dedicated benchmark designed to evaluate sycophantic behavior in state-of-the-art Video-LLMs across diverse question formats, prompt biases, and visual reasoning tasks. Specifically, VISE pioneeringly brings linguistic perspectives on sycophancy into the visual domain, enabling fine-grained analysis across multiple sycophancy types and interaction patterns. In addition, we explore key-frame selection as an interpretable, training-free mitigation strategy, which reveals potential paths for reducing sycophantic bias by strengthening visual grounding.

[Arxiv](https://arxiv.org/abs/2506.07180)