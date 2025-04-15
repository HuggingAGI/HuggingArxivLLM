# 多模态大型语言模型的提示工程未来在于自适应：对稳健多模态性能的全面实验评估

发布时间：2025年04月14日

`LLM应用

理由：这篇论文探讨了提示工程在多模态大型语言模型中的应用，评估了不同提示方法在各种任务中的效果，并提供了优化模型性能的实用建议。它主要关注实际应用中的优化策略，因此属于LLM应用类别。` `多模态模型`

> The Future of MLLM Prompting is Adaptive: A Comprehensive Experimental Evaluation of Prompt Engineering Methods for Robust Multimodal Performance

# 摘要

> 多模态大型语言模型（MLLMs）通过整合文本、图像和代码等多样化模态，正准备改变机器处理和生成类人响应的方式。然而，要充分发挥其潜力，关键在于进行最优的提示工程。我们对应用于13个开源MLLMs的七种提示工程方法进行了全面实验评估，涵盖24项任务，包括推理与组合性、多模态理解和对齐、复杂代码生成与执行，以及知识检索与整合。我们的方法根据参数数量将模型分为小型（<4B）、中型（4B-10B）和大型（>10B）类别，并比较了包括零-shot、一-shot、少-shot、链式思维、类比、生成知识和树式思维在内的提示技术。虽然大型MLLMs在代码生成等结构化任务中表现出色，在少-shot提示下准确率高达96.88%，但所有模型在复杂推理和抽象理解方面都表现不佳，准确率通常低于60%，且幻觉率较高。结构化推理提示通常会增加小型模型的幻觉率高达75%，并导致更长的响应时间（大型MLLMs超过20秒），而更简单的提示方法则提供了更简洁和高效的输出。没有任何单一的提示方法能均匀优化所有任务类型。相反，结合基于示例的指导和选择性结构化推理的自适应策略，对于提高鲁棒性、效率和事实准确性至关重要。我们的发现为提示工程提供了实用建议，并支持在AI辅助编码、知识检索和多模态内容理解等应用中更可靠地部署MLLMs。

> Multimodal Large Language Models (MLLMs) are set to transform how machines process and generate human-like responses by integrating diverse modalities such as text, images, and code. Yet, effectively harnessing their capabilities hinges on optimal prompt engineering. We present a comprehensive experimental evaluation of seven prompt engineering methods applied to 13 open-source MLLMs over 24 tasks spanning Reasoning and Compositionality, Multimodal Understanding and Alignment, Complex Code Generation and Execution, and Knowledge Retrieval and Integration. Our approach stratifies models by parameter count into Small (<4B), Medium (4B-10B), and Large (>10B) categories and compares prompting techniques including Zero-Shot, One-Shot, Few-Shot, Chain-of-Thought, Analogical, Generated Knowledge, and Tree-of-Thought. While Large MLLMs excel in structured tasks such as code generation, achieving accuracies up to 96.88% under Few-Shot prompting, all models struggle with complex reasoning and abstract understanding, often yielding accuracies below 60% and high hallucination rates. Structured reasoning prompts frequently increased hallucination up to 75% in small models and led to longer response times (over 20 seconds in Large MLLMs), while simpler prompting methods provided more concise and efficient outputs. No single prompting method uniformly optimises all task types. Instead, adaptive strategies combining example-based guidance with selective structured reasoning are essential to enhance robustness, efficiency, and factual accuracy. Our findings offer practical recommendations for prompt engineering and support more reliable deployment of MLLMs across applications including AI-assisted coding, knowledge retrieval, and multimodal content understanding.

[Arxiv](https://arxiv.org/abs/2504.10179)