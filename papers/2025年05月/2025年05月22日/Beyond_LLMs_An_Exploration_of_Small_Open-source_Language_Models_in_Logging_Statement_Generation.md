# 超越 LLM：探索小型开源语言模型在日志生成中的应用实践

发布时间：2025年05月22日

`LLM应用` `软件工程` `日志管理`

> Beyond LLMs: An Exploration of Small Open-source Language Models in Logging Statement Generation

# 摘要

> 软件维护离不开高质量的日志语句，但手动日志记录不仅困难、容易出错，还缺乏统一标准，常导致日志质量参差不齐。尽管大型语言模型在自动日志记录方面展现出潜力，但其隐私、资源消耗和适应企业需求方面的问题不容忽视。为突破这些限制，本文实证研究了小型开源语言模型（SOLMs）是否能通过合理利用成为一种可行的替代方案。具体而言，我们对四个突出的SOLMs进行了大规模实证研究，系统地评估了各种交互策略、参数高效的微调技术、模型规模和模型类型对自动日志记录的影响。我们的研究发现，检索增强生成（RAG）显著提升了性能，而LoRA是一种非常有效的PEFT技术。虽然较大的SOLMs通常表现更好，但这涉及计算资源的权衡，而经过指令微调的SOLMs通常优于其基础版本。值得注意的是，经过微调的SOLMs，特别是Qwen2.5-coder-14B，在准确预测日志位置和生成高质量语句方面优于现有的专用工具和LLM基线，这一结论得到了传统评估指标和LLM作为裁判的评估支持。此外，SOLMs还在各种未见过的代码仓库中展示了强大的泛化能力。

> Effective software maintenance heavily relies on high-quality logging statements, but manual logging is challenging, error-prone, and insufficiently standardized, often leading to inconsistent log quality. While large language models have shown promise in automatic logging, they introduce concerns regarding privacy, resource intensity, and adaptability to specific enterprise needs. To tackle these limitations, this paper empirically investigates whether Small Open-source Language Models (SOLMs) could become a viable alternative via proper exploitation. Specifically, we conduct a large-scale empirical study on four prominent SOLMs, systematically evaluating the impacts of various interaction strategies, parameter-efficient fine-tuning techniques, model sizes, and model types in automatic logging. Our key findings reveal that Retrieval-Augmented Generation significantly enhances performance, and LoRA is a highly effective PEFT technique. While larger SOLMs tend to perform better, this involves a trade-off with computational resources, and instruct-tuned SOLMs generally surpass their base counterparts. Notably, fine-tuned SOLMs, particularly Qwen2.5-coder-14B, outperformed existing specialized tools and LLM baselines in accurately predicting logging locations and generating high-quality statements, a conclusion supported by traditional evaluation metrics and LLM-as-a-judge evaluations. Furthermore, SOLMs also demonstrated robust generalization across diverse, unseen code repositories.

[Arxiv](https://arxiv.org/abs/2505.16590)