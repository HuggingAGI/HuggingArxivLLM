# # 图增强推理：面向大语言模型推理的逐步演进知识图谱检索方法

发布时间：2025年03月03日

`LLM应用` `知识图谱`

> Graph-Augmented Reasoning: Evolving Step-by-Step Knowledge Graph Retrieval for LLM Reasoning

# 摘要

> 尽管大型语言模型（LLM）推理取得了显著成果，但其在领域知识覆盖、幻觉控制和推理深度方面仍存在局限，尤其是应用于资源受限环境中的小型模型时。本文首次探索了一种创新方法——图增强推理，通过整合分步知识图谱检索与分步推理，旨在突破这些限制。我们的目标是让冻结的小型LLM具备分步检索和处理数学知识的能力，从而在无需额外训练的情况下显著提升其问题解决能力。为此，我们提出了KG-RAR框架，该框架围绕面向过程的知识图谱构建展开，结合分层检索策略，并引入通用的后检索处理与奖励模型（PRP-RM），用于优化检索结果并评估每一步推理。实验结果表明，在Math500和GSM8K基准测试中，KG-RAR展现了显著优势，其中Llama-3B在Math500上实现了20.73%的相对性能提升。

> Recent large language model (LLM) reasoning, despite its success, suffers from limited domain knowledge, susceptibility to hallucinations, and constrained reasoning depth, particularly in small-scale models deployed in resource-constrained environments. This paper presents the first investigation into integrating step-wise knowledge graph retrieval with step-wise reasoning to address these challenges, introducing a novel paradigm termed as graph-augmented reasoning. Our goal is to enable frozen, small-scale LLMs to retrieve and process relevant mathematical knowledge in a step-wise manner, enhancing their problem-solving abilities without additional training. To this end, we propose KG-RAR, a framework centered on process-oriented knowledge graph construction, a hierarchical retrieval strategy, and a universal post-retrieval processing and reward model (PRP-RM) that refines retrieved information and evaluates each reasoning step. Experiments on the Math500 and GSM8K benchmarks across six models demonstrate that KG-RAR yields encouraging results, achieving a 20.73\% relative improvement with Llama-3B on Math500.

[Arxiv](https://arxiv.org/abs/2503.01642)