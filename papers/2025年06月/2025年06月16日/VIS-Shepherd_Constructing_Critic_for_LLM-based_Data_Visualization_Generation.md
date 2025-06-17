# VIS-Shepherd：为基于LLM的数据可视化生成构建评估器

发布时间：2025年06月16日

`LLM应用

理由：这篇论文探讨了大型语言模型在数据可视化生成中的应用，开发了一种基于多模态LLM的评估工具，并通过实验验证了其有效性。研究重点在于LLM的实际应用，而非其理论或机制。` `数据可视化` `评估工具`

> VIS-Shepherd: Constructing Critic for LLM-based Data Visualization Generation

# 摘要

> 大型语言模型（LLMs）在数据可视化生成方面取得了令人鼓舞的成果，但其输出往往需要人工调整才能达到理想效果。本研究推出VIS-Shepherd，一款基于多模态大型语言模型（MLLM）的专用评估工具，旨在对LLM生成的可视化效果进行评估并提供改进建议。我们的方法核心在于构建一个高质量的可视化评价数据集，通过收集人工创作的可视化实例、生成对应的LLM实例，并构建专业的评价反馈。我们采用模型自动评估和人类偏好研究相结合的方式，验证了本方法的有效性。实验表明，即使使用参数量较小（70亿参数）的开源MLLM模型，借助我们的高质量可视化评价数据集，其性能也能显著提升，可与更大规模的开源或专有模型相媲美。这项研究不仅展现了基于MLLM的自动化可视化评价的巨大潜力，更为提升LLM生成数据可视化的质量提供了明确方向。项目地址：https://github.com/bopan3/VIS-Shepherd。

> Data visualization generation using Large Language Models (LLMs) has shown promising results but often produces suboptimal visualizations that require human intervention for improvement. In this work, we introduce VIS-Shepherd, a specialized Multimodal Large Language Model (MLLM)-based critic to evaluate and provide feedback for LLM-generated data visualizations. At the core of our approach is a framework to construct a high-quality visualization critique dataset, where we collect human-created visualization instances, synthesize corresponding LLM-generated instances, and construct high-quality critiques. We conduct both model-based automatic evaluation and human preference studies to evaluate the effectiveness of our approach. Our experiments show that even small (7B parameters) open-source MLLM models achieve substantial performance gains by leveraging our high-quality visualization critique dataset, reaching levels comparable to much larger open-source or even proprietary models. Our work demonstrates significant potential for MLLM-based automated visualization critique and indicates promising directions for enhancing LLM-based data visualization generation. Our project page: https://github.com/bopan3/VIS-Shepherd.

[Arxiv](https://arxiv.org/abs/2506.13326)