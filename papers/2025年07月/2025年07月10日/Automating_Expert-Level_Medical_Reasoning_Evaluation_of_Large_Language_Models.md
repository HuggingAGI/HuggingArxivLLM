# 大型语言模型的专家级医学推理评估自动化

发布时间：2025年07月10日

`LLM应用` `评估工具`

> Automating Expert-Level Medical Reasoning Evaluation of Large Language Models

# 摘要

> 随着大型语言模型（LLMs）在临床决策中的应用日益广泛，确保其推理过程的透明和可信变得尤为重要。然而，现有评估策略要么在评估质量上不尽如人意，要么在扩展性上表现不佳，且缺乏一个严谨的基准体系。为解决这一问题，我们推出了MedThink-Bench，这是一个专为严谨、可解释且可扩展地评估LLMs医疗推理能力而设计的基准工具。它包含十个医学领域中的500个具有挑战性的问题，每个问题都配有专家精心编写的逐步推理说明。在此基础上，我们提出了LLM-w-Ref，一个创新的评估框架。该框架通过利用细粒度的推理说明和LLM作为裁判机制，能够以专家级的准确度评估中间推理过程，同时保持良好的扩展性。实验结果表明，LLM-w-Ref与专家判断之间存在显著的正相关性。通过对十二个最先进的LLMs进行基准测试，我们发现较小规模的模型（如MedGemma-27B）在某些情况下甚至能够超越更大规模的专有模型（如OpenAI-o3）。总体而言，MedThink-Bench为评估LLMs的医疗推理能力提供了一个基础工具，推动了其在临床实践中安全可靠的应用。

> As large language models (LLMs) become increasingly integrated into clinical decision-making, ensuring transparent and trustworthy reasoning is essential. However, existing evaluation strategies of LLMs' medical reasoning capability either suffer from unsatisfactory assessment or poor scalability, and a rigorous benchmark remains lacking. To address this, we introduce MedThink-Bench, a benchmark designed for rigorous, explainable, and scalable assessment of LLMs' medical reasoning. MedThink-Bench comprises 500 challenging questions across ten medical domains, each annotated with expert-crafted step-by-step rationales. Building on this, we propose LLM-w-Ref, a novel evaluation framework that leverages fine-grained rationales and LLM-as-a-Judge mechanisms to assess intermediate reasoning with expert-level fidelity while maintaining scalability. Experiments show that LLM-w-Ref exhibits a strong positive correlation with expert judgments. Benchmarking twelve state-of-the-art LLMs, we find that smaller models (e.g., MedGemma-27B) can surpass larger proprietary counterparts (e.g., OpenAI-o3). Overall, MedThink-Bench offers a foundational tool for evaluating LLMs' medical reasoning, advancing their safe and responsible deployment in clinical practice.

[Arxiv](https://arxiv.org/abs/2507.07988)