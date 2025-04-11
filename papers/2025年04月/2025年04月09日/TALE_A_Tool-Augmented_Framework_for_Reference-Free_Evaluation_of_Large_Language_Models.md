# TALE: 工具增强型框架，助力无参考大型语言模型评估

发布时间：2025年04月09日

`LLM应用` `人工智能` `问答系统`

> TALE: A Tool-Augmented Framework for Reference-Free Evaluation of Large Language Models

# 摘要

> 随着大型语言模型 (LLMs) 在现实世界和自主应用中的广泛应用，依赖静态、预先标注的参考标准进行评估在成本、扩展性和全面性方面面临诸多挑战。我们提出了一种工具增强的 LLM 评估框架 (TALE)，用于在没有预设正确答案的情况下评估 LLM 的输出。与传统依赖固定参考标准或仅依赖 LLM 作为评判者的指标不同，TALE 采用具备工具访问能力的智能体，主动检索和整合外部证据。它通过迭代生成网络查询、收集信息、总结发现，并通过反思优化后续搜索。通过摆脱对静态参考的依赖，TALE 能够更好地适应现实场景中常见的开放式问答任务。在多个开放式 QA 基准测试中的实验结果表明，TALE 不仅在衡量响应准确性方面优于标准的基于参考的指标，而且与人类评估达到了高度一致。TALE 在无需依赖静态参考的情况下，显著提升了 LLM 评估在现实动态场景中的可靠性。

> As Large Language Models (LLMs) become increasingly integrated into real-world, autonomous applications, relying on static, pre-annotated references for evaluation poses significant challenges in cost, scalability, and completeness. We propose Tool-Augmented LLM Evaluation (TALE), a framework to assess LLM outputs without predetermined ground-truth answers. Unlike conventional metrics that compare to fixed references or depend solely on LLM-as-a-judge knowledge, TALE employs an agent with tool-access capabilities that actively retrieves and synthesizes external evidence. It iteratively generates web queries, collects information, summarizes findings, and refines subsequent searches through reflection. By shifting away from static references, TALE aligns with free-form question-answering tasks common in real-world scenarios. Experimental results on multiple free-form QA benchmarks show that TALE not only outperforms standard reference-based metrics for measuring response accuracy but also achieves substantial to near-perfect agreement with human evaluations. TALE enhances the reliability of LLM evaluations in real-world, dynamic scenarios without relying on static references.

[Arxiv](https://arxiv.org/abs/2504.07385)