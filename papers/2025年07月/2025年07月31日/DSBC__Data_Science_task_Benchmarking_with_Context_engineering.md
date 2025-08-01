# DSBC：数据科学任务评测与上下文能力

发布时间：2025年07月31日

`LLM应用` `数据科学` `自动化`

> DSBC : Data Science task Benchmarking with Context engineering

# 摘要

> # 摘要
大型语言模型（LLMs）的最新进展对数据科学工作流产生了深远影响，催生了专门用于自动化分析任务的数据科学代理。尽管这些代理迅速普及，但系统性评估其有效性和局限性的基准仍十分稀缺。本文中，我们引入了一个全面的基准测试，通过观察我们商业应用的使用情况，专门设计来反映用户与数据科学代理的真实交互。

我们评估了三个 LLM：Claude-4.0-Sonnet、Gemini-2.5-Flash 和 OpenAI-o4-Mini，采用三种方法：带上下文工程的零-shot、多步带上下文工程和带 SmolAgent。基准测试涵盖了八类数据科学任务，并深入探讨了模型对常见提示问题（如数据泄露和略显模糊的指令）的敏感性。此外，我们还研究了温度参数对每个模型和方法的整体及特定任务结果的影响。

研究发现，不同模型和方法之间存在显著的性能差异，揭示了影响实际部署的关键因素。本文中引入的基准测试数据集和评估框架旨在为未来研究更强大和有效的数据科学代理奠定基础。


> Recent advances in large language models (LLMs) have significantly impacted data science workflows, giving rise to specialized data science agents designed to automate analytical tasks. Despite rapid adoption, systematic benchmarks evaluating the efficacy and limitations of these agents remain scarce. In this paper, we introduce a comprehensive benchmark specifically crafted to reflect real-world user interactions with data science agents by observing usage of our commercial applications. We evaluate three LLMs: Claude-4.0-Sonnet, Gemini-2.5-Flash, and OpenAI-o4-Mini across three approaches: zero-shot with context engineering, multi-step with context engineering, and with SmolAgent. Our benchmark assesses performance across a diverse set of eight data science task categories, additionally exploring the sensitivity of models to common prompting issues, such as data leakage and slightly ambiguous instructions. We further investigate the influence of temperature parameters on overall and task-specific outcomes for each model and approach. Our findings reveal distinct performance disparities among the evaluated models and methodologies, highlighting critical factors that affect practical deployment. The benchmark dataset and evaluation framework introduced herein aim to provide a foundation for future research of more robust and effective data science agents.

[Arxiv](https://arxiv.org/abs/2507.23336)