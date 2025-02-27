# 更快、更优、更经济：LLM 与 RAG 系统多目标超参数优化探索

发布时间：2025年02月25日

`RAG` `系统设计`

> Faster, Cheaper, Better: Multi-Objective Hyperparameter Optimization for LLM and RAG Systems

# 摘要

> 检索增强生成（RAG）作为提升大型语言模型（LLM）系统性能的热门技术，带来了大量需要选择和调整的参数与超参数。这些参数不仅包括LLM、嵌入和排序模型本身，还涉及控制RAG组件的超参数。然而，由于解空间庞大、目标评估噪声以及高昂的评估成本，对RAG或LLM系统进行全面优化仍具挑战性——尤其是在多目标场景下。本研究首次提出了针对整个LLM和RAG系统在成本、延迟、安全性和对齐性方面的多目标参数优化方法。实验结果表明，贝叶斯优化方法在两个新的RAG基准任务上显著优于基线方法，展现了更优的帕累托前沿。最后，我们为设计多目标RAG系统的从业者提供了重要建议，强调了如最优配置可能无法跨任务和目标推广等关键点。

> While Retrieval Augmented Generation (RAG) has emerged as a popular technique for improving Large Language Model (LLM) systems, it introduces a large number of choices, parameters and hyperparameters that must be made or tuned. This includes the LLM, embedding, and ranker models themselves, as well as hyperparameters governing individual RAG components. Yet, collectively optimizing the entire configuration in a RAG or LLM system remains under-explored - especially in multi-objective settings - due to intractably large solution spaces, noisy objective evaluations, and the high cost of evaluations. In this work, we introduce the first approach for multi-objective parameter optimization of cost, latency, safety and alignment over entire LLM and RAG systems. We find that Bayesian optimization methods significantly outperform baseline approaches, obtaining a superior Pareto front on two new RAG benchmark tasks. We conclude our work with important considerations for practitioners who are designing multi-objective RAG systems, highlighting nuances such as how optimal configurations may not generalize across tasks and objectives.

[Arxiv](https://arxiv.org/abs/2502.18635)