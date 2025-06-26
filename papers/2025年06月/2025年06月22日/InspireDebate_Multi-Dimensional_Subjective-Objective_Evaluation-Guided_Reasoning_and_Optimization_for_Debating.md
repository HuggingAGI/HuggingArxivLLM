# InspireDebate：多维度主观-客观评估引导的推理与优化，用于辩论。

发布时间：2025年06月22日

`LLM应用` `智能辩论系统`

> InspireDebate: Multi-Dimensional Subjective-Objective Evaluation-Guided Reasoning and Optimization for Debating

# 摘要

> 大型语言模型（LLMs）的快速发展推动了辩论任务如论点质量评估和辩论过程模拟的显著进步。然而，现有的基于LLM的辩论系统专注于回应特定论点，却忽视了真实性、逻辑有效性等关键的客观评估。此外，这些系统缺乏在评估指标、链式推理（CoT）以及多轮辩论完善等多维度上的结构化优化方法，从而限制了其有效性。为了解决这些相互关联的挑战，我们提出了一种创新的双组件框架：(1) $	extbf{InspireScore}$，一个新型评估系统，构建了包含四项主观标准（情感诉求、论点清晰度、论点安排和主题相关性）以及两项客观指标（事实真实性和逻辑有效性）的多维评估架构；(2) $	extbf{InspireDebate}$，一个优化的辩论框架，通过增强链式推理、多维直接偏好优化（DPO）以及基于网络检索增强生成（Web-RAG）的实时知识 grounding，采用分阶段优化方法。实证评估表明，$	extbf{InspireScore}$与专家判断的相关性比现有方法高出44$\%$，而$	extbf{InspireDebate}$也表现出显著改进，比基线模型高出57$\%$。源代码可在https://github.com/fywang12/InspireDebate获取。

> With the rapid advancements in large language models (LLMs), debating tasks, such as argument quality assessment and debate process simulation, have made significant progress. However, existing LLM-based debating systems focus on responding to specific arguments while neglecting objective assessments such as authenticity and logical validity. Furthermore, these systems lack a structured approach to optimize across various dimensions$-$including evaluation metrics, chain-of-thought (CoT) reasoning, and multi-turn debate refinement$-$thereby limiting their effectiveness. To address these interconnected challenges, we propose a dual-component framework: (1) $\textbf{InspireScore}$, a novel evaluation system that establishes a multi-dimensional assessment architecture incorporating four subjective criteria (emotional appeal, argument clarity, argument arrangement, and topic relevance) alongside two objective metrics (fact authenticity and logical validity); and (2) $\textbf{InspireDebate}$, an optimized debating framework employing a phased optimization approach through CoT reasoning enhancement, multi-dimensional Direct Preference Optimization (DPO), and real-time knowledge grounding via web-based Retrieval Augmented Generation (Web-RAG). Empirical evaluations demonstrate that $\textbf{InspireScore}$ achieves 44$\%$ higher correlation with expert judgments compared to existing methods, while $\textbf{InspireDebate}$ shows significant improvements, outperforming baseline models by 57$\%$. Source code is available at https://github.com/fywang12/InspireDebate.

[Arxiv](https://arxiv.org/abs/2506.18102)