# 针对古兰经研究的检索增强生成方法研究：基于13个开源大型语言模型的探索

发布时间：2025年03月20日

`LLM应用`

> Investigating Retrieval-Augmented Generation in Quranic Studies: A Study of 13 Open-Source Large Language Models

# 摘要

> 在处理古兰经研究等敏感且领域特定的任务时，生成精准且符合语境的回答至关重要。然而，通用型LLMs常常难以避免产生幻觉（即生成的回答偏离权威来源），这在宗教语境下引发了对其可靠性的担忧。本研究旨在开发能够整合领域知识，同时保持回答准确性、相关性和忠实性的系统。

本研究考察了13个开源LLMs，分为大型（如Llama3:70b、Gemma2:27b、QwQ:32b）、中型（如Gemma2:9b、Llama3:8b）和小型（如Llama3.2:3b、Phi3:3.8b）三类。采用检索增强生成（RAG）来弥补使用分离模型带来的问题。研究采用了包含114章古兰经经文含义、历史背景和特点的描述性数据集，使模型能够在回应前收集相关知识。

评估模型时，采用了由人工评估者设定的三个关键指标：上下文相关性、回答忠实性和回答相关性。研究发现，大型模型在捕捉查询语义和生成准确、基于上下文的回答方面始终优于小型模型。尽管Llama3.2:3b模型被视为小型模型，但它在忠实性（4.619）和相关性（4.857）方面表现优异，这表明经过良好优化的小型架构具有潜力。

本文探讨了在领域特定应用中使用LLMs时，模型规模、计算效率和回答质量之间的权衡。研究结果表明，虽然大型模型在性能上占据优势，但小型模型在优化得当时也能展现出令人惊喜的表现。这为在资源受限的场景下选择模型提供了重要参考。

> Accurate and contextually faithful responses are critical when applying large language models (LLMs) to sensitive and domain-specific tasks, such as answering queries related to quranic studies. General-purpose LLMs often struggle with hallucinations, where generated responses deviate from authoritative sources, raising concerns about their reliability in religious contexts. This challenge highlights the need for systems that can integrate domain-specific knowledge while maintaining response accuracy, relevance, and faithfulness. In this study, we investigate 13 open-source LLMs categorized into large (e.g., Llama3:70b, Gemma2:27b, QwQ:32b), medium (e.g., Gemma2:9b, Llama3:8b), and small (e.g., Llama3.2:3b, Phi3:3.8b). A Retrieval-Augmented Generation (RAG) is used to make up for the problems that come with using separate models. This research utilizes a descriptive dataset of Quranic surahs including the meanings, historical context, and qualities of the 114 surahs, allowing the model to gather relevant knowledge before responding. The models are evaluated using three key metrics set by human evaluators: context relevance, answer faithfulness, and answer relevance. The findings reveal that large models consistently outperform smaller models in capturing query semantics and producing accurate, contextually grounded responses. The Llama3.2:3b model, even though it is considered small, does very well on faithfulness (4.619) and relevance (4.857), showing the promise of smaller architectures that have been well optimized. This article examines the trade-offs between model size, computational efficiency, and response quality while using LLMs in domain-specific applications.

[Arxiv](https://arxiv.org/abs/2503.16581)