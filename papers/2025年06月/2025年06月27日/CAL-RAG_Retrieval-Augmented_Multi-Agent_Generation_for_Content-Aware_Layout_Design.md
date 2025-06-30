# # CAL-RAG：基于检索增强的多智能体生成，专为内容感知布局设计而优化

发布时间：2025年06月27日

`LLM应用` `人工智能` `智能设计`

> CAL-RAG: Retrieval-Augmented Multi-Agent Generation for Content-Aware Layout Design

# 摘要

> 内容感知布局生成——在背景画布上智能排列文本、Logo和底图等视觉元素——仍是智能设计系统中的基础性难题。尽管深度生成模型和大型语言模型（LLMs）在结构化内容生成方面展现出潜力，现有方法大多缺乏对上下文设计示例的参考，在语义对齐和视觉连贯性方面仍有不足。本文提出CAL-RAG框架，这是一个结合多模态检索、大型语言模型和协作智能体推理的检索增强型布局生成系统。CAL-RAG从结构化知识库中检索相关布局示例，并借助基于LLM的布局推荐器提出结构化元素布局建议。视觉语言评分器智能体通过视觉指标评估布局质量，反馈智能体则提供针对性优化建议，支持迭代改进。我们在LangGraph平台上实现这一框架，并在包含丰富语义和结构变化的PKU PosterLayout数据集上进行评估。实验结果表明，CAL-RAG在底图有效性、元素对齐和重叠等多个评估指标上达到当前最优性能，显著超越了LayoutPrompter等强劲基线。这证明了将检索增强与多步智能体推理相结合，能够为自动化布局生成提供一种可扩展、可解释且高保真的解决方案。


> Automated content-aware layout generation -- the task of arranging visual elements such as text, logos, and underlays on a background canvas -- remains a fundamental yet under-explored problem in intelligent design systems. While recent advances in deep generative models and large language models (LLMs) have shown promise in structured content generation, most existing approaches lack grounding in contextual design exemplars and fall short in handling semantic alignment and visual coherence. In this work we introduce CAL-RAG, a retrieval-augmented, agentic framework for content-aware layout generation that integrates multimodal retrieval, large language models, and collaborative agentic reasoning. Our system retrieves relevant layout examples from a structured knowledge base and invokes an LLM-based layout recommender to propose structured element placements. A vision-language grader agent evaluates the layout with visual metrics, and a feedback agent provides targeted refinements, enabling iterative improvement. We implement our framework using LangGraph and evaluate it on the PKU PosterLayout dataset, a benchmark rich in semantic and structural variability. CAL-RAG achieves state-of-the-art performance across multiple layout metrics -- including underlay effectiveness, element alignment, and overlap -- substantially outperforming strong baselines such as LayoutPrompter. These results demonstrate that combining retrieval augmentation with agentic multi-step reasoning yields a scalable, interpretable, and high-fidelity solution for automated layout generation.

[Arxiv](https://arxiv.org/abs/2506.21934)