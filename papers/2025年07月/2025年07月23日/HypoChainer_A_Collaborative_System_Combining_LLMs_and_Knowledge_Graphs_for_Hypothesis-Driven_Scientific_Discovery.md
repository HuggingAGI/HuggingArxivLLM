# HypoChainer：结合大型语言模型与知识图谱的协作系统，专为假设驱动的科学发现而设计

发布时间：2025年07月23日

`LLM应用

论文摘要：现代科学发现正面临一项重大挑战：如何整合对生物医学和药物开发至关重要的庞大而异构知识。传统的假设驱动研究虽然有效，却受限于人类认知的局限、生物系统的复杂性以及试错实验的高昂成本。深度学习模型，尤其是图神经网络（GNNs），虽然加速了预测的生成，但海量的输出使得人工选择进行验证变得不可扩展。大型语言模型（LLMs）在过滤和假设生成方面展现出潜力，却因幻觉问题和缺乏对结构化知识的 grounding 而可靠性不足。为了解决这些问题，我们提出了 HypoChainer，一个协作式可视化框架，整合了人类专业知识、LLM 驱动的推理以及知识图谱（KGs），以增强假设生成和验证。HypoChainer 分三个阶段运行：第一阶段，探索与上下文关联——专家利用增强检索的 LLM（RAGs）和降维技术在大规模 GNN 预测中导航，借助交互式解释。第二阶段，假设链形成——专家围绕预测和语义关联的实体，迭代检查 KG 关系，并根据 LLM 和 KG 的建议细化假设。第三阶段，验证优先级排序——基于 KG 支持的证据对细化的假设进行筛选，以识别高优先级的实验候选者，同时通过可视化分析进一步强化推理中的薄弱环节。我们通过两个领域的案例研究和专家访谈，展示了 HypoChainer 的有效性，突显其支持可解释、可扩展且基于知识的科学发现的潜力。

LLM应用` `生物医学` `药物开发`

> HypoChainer: A Collaborative System Combining LLMs and Knowledge Graphs for Hypothesis-Driven Scientific Discovery

# 摘要

> 现代科学发现正面临一项重大挑战：如何整合对生物医学和药物开发至关重要的庞大而异构知识。传统的假设驱动研究虽然有效，却受限于人类认知的局限、生物系统的复杂性以及试错实验的高昂成本。深度学习模型，尤其是图神经网络（GNNs），虽然加速了预测的生成，但海量的输出使得人工选择进行验证变得不可扩展。大型语言模型（LLMs）在过滤和假设生成方面展现出潜力，却因幻觉问题和缺乏对结构化知识的 grounding 而可靠性不足。为了解决这些问题，我们提出了 HypoChainer，一个协作式可视化框架，整合了人类专业知识、LLM 驱动的推理以及知识图谱（KGs），以增强假设生成和验证。HypoChainer 分三个阶段运行：第一阶段，探索与上下文关联——专家利用增强检索的 LLM（RAGs）和降维技术在大规模 GNN 预测中导航，借助交互式解释。第二阶段，假设链形成——专家围绕预测和语义关联的实体，迭代检查 KG 关系，并根据 LLM 和 KG 的建议细化假设。第三阶段，验证优先级排序——基于 KG 支持的证据对细化的假设进行筛选，以识别高优先级的实验候选者，同时通过可视化分析进一步强化推理中的薄弱环节。我们通过两个领域的案例研究和专家访谈，展示了 HypoChainer 的有效性，突显其支持可解释、可扩展且基于知识的科学发现的潜力。


> Modern scientific discovery faces growing challenges in integrating vast and heterogeneous knowledge critical to breakthroughs in biomedicine and drug development. Traditional hypothesis-driven research, though effective, is constrained by human cognitive limits, the complexity of biological systems, and the high cost of trial-and-error experimentation. Deep learning models, especially graph neural networks (GNNs), have accelerated prediction generation, but the sheer volume of outputs makes manual selection for validation unscalable. Large language models (LLMs) offer promise in filtering and hypothesis generation, yet suffer from hallucinations and lack grounding in structured knowledge, limiting their reliability. To address these issues, we propose HypoChainer, a collaborative visualization framework that integrates human expertise, LLM-driven reasoning, and knowledge graphs (KGs) to enhance hypothesis generation and validation. HypoChainer operates in three stages: First, exploration and contextualization -- experts use retrieval-augmented LLMs (RAGs) and dimensionality reduction to navigate large-scale GNN predictions, assisted by interactive explanations. Second, hypothesis chain formation -- experts iteratively examine KG relationships around predictions and semantically linked entities, refining hypotheses with LLM and KG suggestions. Third, validation prioritization -- refined hypotheses are filtered based on KG-supported evidence to identify high-priority candidates for experimentation, with visual analytics further strengthening weak links in reasoning. We demonstrate HypoChainer's effectiveness through case studies in two domains and expert interviews, highlighting its potential to support interpretable, scalable, and knowledge-grounded scientific discovery.

[Arxiv](https://arxiv.org/abs/2507.17209)