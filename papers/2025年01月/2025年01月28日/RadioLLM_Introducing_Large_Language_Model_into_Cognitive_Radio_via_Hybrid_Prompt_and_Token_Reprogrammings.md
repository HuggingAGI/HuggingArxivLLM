# RadioLLM: 通过混合提示与令牌重编程，将大型语言模型融入认知无线电

发布时间：2025年01月28日

`LLM应用

**理由**：这篇论文主要讨论了如何将大型语言模型（LLMs）应用于认知无线电技术（CRT）中的信号处理任务，提出了RadioLLM框架，并通过实验验证了其有效性。论文的核心在于利用LLMs的泛化能力来解决CRT中的多样化任务，属于LLM在实际应用中的探索。因此，分类为LLM应用。` `无线电网络`

> RadioLLM: Introducing Large Language Model into Cognitive Radio via Hybrid Prompt and Token Reprogrammings

# 摘要

> 频谱资源日益紧张，无线设备快速增长，无线电网络的高效管理成为一大挑战。认知无线电技术（CRT）与深度学习（DL）结合，为信号分类、去噪和频谱分配等任务提供了新的解决方案。然而，现有的DL-CRT框架多为任务专用，难以适应多样化的现实场景。与此同时，大型语言模型（LLMs）在多个领域展现了强大的泛化能力，成为推动CRT技术发展的潜在力量。本文提出RadioLLM框架，结合混合提示与令牌重编程（HPTR）和频率调谐融合（FAF）模块，提升LLMs在CRT任务中的表现。HPTR整合信号特征与专家知识，FAF优化高频特征建模，助力精确信号处理。这些创新使RadioLLM能够应对多样化的CRT任务，填补了LLMs与传统信号处理方法之间的空白。大量实验表明，RadioLLM在多个基准数据集上表现优异，超越了现有基线方法。

> The increasing scarcity of spectrum resources and the rapid growth of wireless device have made efficient management of radio networks a critical challenge. Cognitive Radio Technology (CRT), when integrated with deep learning (DL), offers promising solutions for tasks such as radio signal classification (RSC), signal denoising, and spectrum allocation. However, existing DL-based CRT frameworks are often task-specific and lack scalability to diverse real-world scenarios. Meanwhile, Large Language Models (LLMs) have demonstrated exceptional generalization capabilities across multiple domains, making them a potential candidate for advancing CRT technologies. In this paper, we introduce RadioLLM, a novel framework that incorporates Hybrid Prompt and Token Reprogramming (HPTR) and a Frequency Attuned Fusion (FAF) module to enhance LLMs for CRT tasks. HPTR enables the integration of radio signal features with expert knowledge, while FAF improves the modeling of high-frequency features critical for precise signal processing. These innovations allow RadioLLM to handle diverse CRT tasks, bridging the gap between LLMs and traditional signal processing methods. Extensive empirical studies on multiple benchmark datasets demonstrate that the proposed RadioLLM achieves superior performance over current baselines.

[Arxiv](https://arxiv.org/abs/2501.17888)