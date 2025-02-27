# TheoremExplainAgent：探索大型语言模型理解定理的多模态解释研究

发布时间：2025年02月26日

`Agent`

> TheoremExplainAgent: Towards Multimodal Explanations for LLM Theorem Understanding

# 摘要

> 理解领域特定的定理，不仅需要基于文本的推理，还需要通过结构化的视觉解释进行有效沟通，以实现更深入的理解。虽然大型语言模型（LLMs）在基于文本的定理推理方面表现出色，但生成连贯且具有教育意义的视觉解释仍然是一个开放的挑战。

在本研究中，我们引入了TheoremExplainAgent，这是一种基于智能体的方法，用于生成长篇定理讲解视频（超过5分钟），并结合Manim动画技术。为了系统性地评估多模态定理解释，我们提出了TheoremExplainBench，这是一个涵盖多个STEM学科的240个定理的基准测试，同时还提供了5个自动化评估指标。

研究结果显示，智能体规划对于生成详细长篇视频至关重要。其中，o3-mini智能体达到了93.8%的成功率和0.77的总体评分。然而，定量和定性研究表明，大多数生成的视频在视觉元素布局方面存在轻微问题。此外，多模态解释揭示了文本解释无法展现的深层推理缺陷，突显了多模态解释的重要性。


> Understanding domain-specific theorems often requires more than just text-based reasoning; effective communication through structured visual explanations is crucial for deeper comprehension. While large language models (LLMs) demonstrate strong performance in text-based theorem reasoning, their ability to generate coherent and pedagogically meaningful visual explanations remains an open challenge. In this work, we introduce TheoremExplainAgent, an agentic approach for generating long-form theorem explanation videos (over 5 minutes) using Manim animations. To systematically evaluate multimodal theorem explanations, we propose TheoremExplainBench, a benchmark covering 240 theorems across multiple STEM disciplines, along with 5 automated evaluation metrics. Our results reveal that agentic planning is essential for generating detailed long-form videos, and the o3-mini agent achieves a success rate of 93.8% and an overall score of 0.77. However, our quantitative and qualitative studies show that most of the videos produced exhibit minor issues with visual element layout. Furthermore, multimodal explanations expose deeper reasoning flaws that text-based explanations fail to reveal, highlighting the importance of multimodal explanations.

[Arxiv](https://arxiv.org/abs/2502.19400)