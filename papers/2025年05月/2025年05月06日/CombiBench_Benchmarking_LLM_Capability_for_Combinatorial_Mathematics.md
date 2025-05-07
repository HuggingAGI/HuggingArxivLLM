# CombiBench：评估大型语言模型在组合数学中的能力基准

发布时间：2025年05月06日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLM）在组合数学问题上的应用，特别是通过基准测试集CombiBench和评估框架Fine-Eval来测试模型的能力。论文的重点在于实际应用和性能评估，属于LLM的应用领域。` `数学竞赛` `人工智能`

> CombiBench: Benchmarking LLM Capability for Combinatorial Mathematics

# 摘要

> 神经符号方法结合大型语言模型与形式推理，在代数、几何和数论等数学竞赛问题上已达到人类水平。然而，组合数学领域仍具挑战性，主要由于缺乏合适的基准测试和定理库。为解决这一问题，我们推出了CombiBench——一个包含100个组合数学问题的全面基准测试集，每个问题均以Lean~4形式化表示，并配有非正式陈述。问题难度从初中到国际数学奥林匹克（IMO）和大学水平不等，涵盖十个组合数学主题。CombiBench包含自2000年以来的所有IMO组合数学问题（除IMO 2004 P3，因其陈述含图像），适用于测试IMO解题能力。我们还提供了一个全面且标准化的评估框架——Fine-Eval，用于形式数学评估。它不仅支持基于证明的问题，还首次支持填空题的评估。使用Fine-Eval作为评估方法，并以Kimina Lean Server作为后端，我们在CombiBench上对多个LLM进行了基准测试，发现它们在正式解决组合数学问题方面的能力仍然有限。在所有测试的模型中（均未针对此特定任务进行过训练），Kimina-Prover表现最佳，在``with solution''和``without solution''两种场景下分别解决了7个问题（共100个）。我们已开源基准测试数据集以及评估方法代码，地址为https://github.com/MoonshotAI/CombiBench/。

> Neurosymbolic approaches integrating large language models with formal reasoning have recently achieved human-level performance on mathematics competition problems in algebra, geometry and number theory. In comparison, combinatorics remains a challenging domain, characterized by a lack of appropriate benchmarks and theorem libraries. To address this gap, we introduce CombiBench, a comprehensive benchmark comprising 100 combinatorial problems, each formalized in Lean~4 and paired with its corresponding informal statement. The problem set covers a wide spectrum of difficulty levels, ranging from middle school to IMO and university level, and span over ten combinatorial topics. CombiBench is suitable for testing IMO solving capabilities since it includes all IMO combinatorial problems since 2000 (except IMO 2004 P3 as its statement contain an images). Furthermore, we provide a comprehensive and standardized evaluation framework, dubbed Fine-Eval (for $\textbf{F}$ill-in-the-blank $\textbf{in}$ L$\textbf{e}$an Evaluation), for formal mathematics. It accommodates not only proof-based problems but also, for the first time, the evaluation of fill-in-the-blank questions. Using Fine-Eval as the evaluation method and Kimina Lean Server as the backend, we benchmark several LLMs on CombiBench and observe that their capabilities for formally solving combinatorial problems remain limited. Among all models tested (none of which has been trained for this particular task), Kimina-Prover attains the best results, solving 7 problems (out of 100) under both ``with solution'' and ``without solution'' scenarios. We open source the benchmark dataset alongside with the code of the proposed evaluation method at https://github.com/MoonshotAI/CombiBench/.

[Arxiv](https://arxiv.org/abs/2505.03171)