# RefactorCoderQA：面向云和边缘部署场景中多领域编码问题解决方案的大型语言模型（LLMs）基准测试

发布时间：2025年09月12日

`Agent` `基础理论`

> RefactorCoderQA: Benchmarking LLMs for Multi-Domain Coding Question Solutions in Cloud and Edge Deployment

# 摘要

> 为优化大型语言模型（LLMs）的推理与问题解决能力，我们提出一种新颖的云边协同架构，构建结构化多智能体提示框架。该框架包含三个核心组件：GuideLLM——部署于边缘端的轻量级模型，负责提供方法指导；SolverLLM——云端部署的高性能模型，负责生成代码解决方案；JudgeLLM——用于评估解决方案正确性与质量的自动评估器。为在真实场景中评估并验证该架构的有效性，我们构建了RefactorCoderQA——一个用于评估和提升大型语言模型（LLMs）在多领域编码任务中性能的综合基准。针对现有基准的局限性，RefactorCoderQA系统覆盖软件工程、数据科学、机器学习、自然语言处理等多个技术领域，并采用Stack Overflow上的真实编码挑战作为实验数据。大量实验结果显示，我们的微调模型RefactorCoder-MoE达到了当前最优性能，以76.84%的总体准确率显著优于主流开源及商业基线模型。人类评估进一步验证了生成方案的可解释性、准确性及实际应用价值。此外，我们还对吞吐量、延迟等系统级指标进行了评估，以深入分析所提架构的性能特征及权衡关系。

> To optimize the reasoning and problem-solving capabilities of Large Language Models (LLMs), we propose a novel cloud-edge collaborative architecture that enables a structured, multi-agent prompting framework. This framework comprises three specialized components: GuideLLM, a lightweight model deployed at the edge to provide methodological guidance; SolverLLM, a more powerful model hosted in the cloud responsible for generating code solutions; and JudgeLLM, an automated evaluator for assessing solution correctness and quality. To evaluate and demonstrate the effectiveness of this architecture in realistic settings, we introduce RefactorCoderQA, a comprehensive benchmark designed to evaluate and enhance the performance of Large Language Models (LLMs) across multi-domain coding tasks. Motivated by the limitations of existing benchmarks, RefactorCoderQA systematically covers various technical domains, including Software Engineering, Data Science, Machine Learning, and Natural Language Processing, using authentic coding challenges from Stack Overflow. Extensive experiments reveal that our fine-tuned model, RefactorCoder-MoE, achieves state-of-the-art performance, significantly outperforming leading open-source and commercial baselines with an overall accuracy of 76.84%. Human evaluations further validate the interpretability, accuracy, and practical relevance of the generated solutions. In addition, we evaluate system-level metrics, such as throughput and latency, to gain deeper insights into the performance characteristics and trade-offs of the proposed architecture.

[Arxiv](https://arxiv.org/abs/2509.10436)