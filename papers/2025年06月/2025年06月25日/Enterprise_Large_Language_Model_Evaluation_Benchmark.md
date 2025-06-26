# 企业级大型语言模型评估基准

发布时间：2025年06月25日

`LLM应用

摘要中提到的论文主要探讨了大型语言模型（LLMs）在企业环境中的应用潜力和评估方法。论文提出了一套基于布卢姆分类法的任务框架，并构建了一个基准测试集来评估LLMs在企业特定任务中的表现。研究结果揭示了现有模型在不同任务中的性能差距，并为企业优化模型提供了见解。因此，这篇论文属于LLM应用类别。`

> Enterprise Large Language Model Evaluation Benchmark

# 摘要

> 大型语言模型 (LLMs) 在提升各类AI工具生产力方面展现出巨大潜力，但现有基准测试（如MMLU）未能充分评估企业特定任务的复杂性。我们提出了一套基于布卢姆分类法的14项任务框架，全面评估LLM在企业环境中的能力。为应对噪声数据和高昂标注成本的挑战，我们开发了一套可扩展的流水线，整合了LLM作为标注器、LLM作为评估器以及修正型检索增强生成（CRAG），构建了一个包含9700个样本的稳健基准测试集。对六款领先模型的评估显示，开源模型（如DeepSeek R1）在推理任务中可与专有模型相媲美，但在基于判断的场景下表现较弱，这可能源于过度思考的问题。我们的基准测试揭示了企业应用中的关键性能差距，并为企业优化模型提供了实用见解。这项研究为企业提供了定制化评估的蓝图，推动了LLM的实际部署进程。

> Large Language Models (LLMs) ) have demonstrated promise in boosting productivity across AI-powered tools, yet existing benchmarks like Massive Multitask Language Understanding (MMLU) inadequately assess enterprise-specific task complexities. We propose a 14-task framework grounded in Bloom's Taxonomy to holistically evaluate LLM capabilities in enterprise contexts. To address challenges of noisy data and costly annotation, we develop a scalable pipeline combining LLM-as-a-Labeler, LLM-as-a-Judge, and corrective retrieval-augmented generation (CRAG), curating a robust 9,700-sample benchmark. Evaluation of six leading models shows open-source contenders like DeepSeek R1 rival proprietary models in reasoning tasks but lag in judgment-based scenarios, likely due to overthinking. Our benchmark reveals critical enterprise performance gaps and offers actionable insights for model optimization. This work provides enterprises a blueprint for tailored evaluations and advances practical LLM deployment.

[Arxiv](https://arxiv.org/abs/2506.20274)