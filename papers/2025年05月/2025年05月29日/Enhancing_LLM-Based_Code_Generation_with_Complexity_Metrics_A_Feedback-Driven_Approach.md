# 提升基于LLM的代码生成能力：结合复杂度指标的反馈驱动方法

发布时间：2025年05月29日

`LLM应用` `软件工程` `代码生成`

> Enhancing LLM-Based Code Generation with Complexity Metrics: A Feedback-Driven Approach

# 摘要

> 大语言模型（LLMs）如GPT-4的出现为自动代码生成带来了巨大突破。尽管现有研究多集中于提升LLMs在代码生成中的效果，但对生成代码特性的深入理解及其在改进失败案例中的应用却鲜有探索。本文聚焦代码复杂度这一代码的基本特性，深入探究其与LLMs生成代码成功率之间的内在联系。

我们首先运用一系列标准复杂度指标，系统性地分析了它们与LLMs在代码生成任务（Pass@1）上表现的相关性。借助逻辑回归模型，我们成功识别出最能预测代码正确性的复杂度指标。基于这些发现，我们创新性地提出了一种迭代反馈方法：通过分析先前失败输出的复杂度指标，引导LLMs生成正确的代码。

我们通过HumanEval、MBPP、LeetCode和BigCodeBench等多个基准测试，以及GPT-4o、GPT-3.5 Turbo、Llama 3.1和GPT-o3 mini等多种LLMs对该方法进行了全面验证。实验结果令人振奋：在HumanEval数据集上，使用GPT-3.5 Turbo时，Pass@1较基线提升了35.71%（而基线仅提升12.5%）。进一步将实验扩展到BigCodeBench，并与Reflexion代码生成代理相结合，我们实现了GPT-4o提升20%和GPT-o3 mini提升23.07%的优异成绩。这些结果充分证明，基于复杂度的反馈机制能够显著提升直接LLM提示和基于代理的工作流性能。

> Automatic code generation has gained significant momentum with the advent of Large Language Models (LLMs) such as GPT-4. Although many studies focus on improving the effectiveness of LLMs for code generation, very limited work tries to understand the generated code's characteristics and leverage that to improve failed cases. In this paper, as the most straightforward characteristic of code, we investigate the relationship between code complexity and the success of LLM generated code. Using a large set of standard complexity metrics, we first conduct an empirical analysis to explore their correlation with LLM's performance on code generation (i.e., Pass@1). Using logistic regression models, we identify which complexity metrics are most predictive of code correctness. Building on these findings, we propose an iterative feedback method, where LLMs are prompted to generate correct code based on complexity metrics from previous failed outputs. We validate our approach across multiple benchmarks (i.e., HumanEval, MBPP, LeetCode, and BigCodeBench) and various LLMs (i.e., GPT-4o, GPT-3.5 Turbo, Llama 3.1, and GPT-o3 mini), comparing the results with two baseline methods: (a) zero-shot generation, and (b) iterative execution-based feedback without our code complexity insights. Experiment results show that our approach makes notable improvements, particularly with a smaller LLM (GPT3.5 Turbo), where, e.g., Pass@1 increased by 35.71% compared to the baseline's improvement of 12.5% on the HumanEval dataset. The study expands experiments to BigCodeBench and integrates the method with the Reflexion code generation agent, leading to Pass@1 improvements of 20% (GPT-4o) and 23.07% (GPT-o3 mini). The results highlight that complexity-aware feedback enhances both direct LLM prompting and agent-based workflows.

[Arxiv](https://arxiv.org/abs/2505.23953)