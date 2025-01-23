# 大型语言模型公共服务中断与事件的实证分析

发布时间：2025年01月21日

`LLM应用

**理由**：这篇论文主要关注的是公共LLM服务（如ChatGPT、Claude等）的故障与恢复过程，属于对LLM在实际应用中的表现和问题的研究。论文通过实证分析，探讨了这些服务的故障特性、恢复时间、周期性等问题，旨在为优化LLM系统的构建和使用提供依据。因此，它属于LLM应用类别。` `人工智能` `系统可靠性`

> An Empirical Characterization of Outages and Incidents in Public Services for Large Language Models

# 摘要

> # 摘要
随着ChatGPT、DALLE和Claude等公共LLM服务的普及，理解其故障及恢复过程变得至关重要。然而，这一新兴领域的研究尚不充分。为此，我们对公共LLM服务的故障与恢复进行了实证研究，收集了来自OpenAI、Anthropic等3家主要提供商的8个常用服务的数据集，并深入分析了故障恢复的统计特性、时间模式、共现性及影响范围。研究发现：(1) OpenAI的ChatGPT故障解决时间较长，但发生频率低于Anthropic的Claude；(2) OpenAI和Anthropic的服务故障呈现显著的周和月周期性；(3) OpenAI在故障隔离方面表现更佳。这些发现为优化LLM系统的构建和使用提供了依据。相关数据和代码已公开在https://zenodo.org/records/14018219和https://github.com/atlarge-research/llm-service-analysis。

> People and businesses increasingly rely on public LLM services, such as ChatGPT, DALLE, and Claude. Understanding their outages, and particularly measuring their failure-recovery processes, is becoming a stringent problem. However, only limited studies exist in this emerging area. Addressing this problem, in this work we conduct an empirical characterization of outages and failure-recovery in public LLM services. We collect and prepare datasets for 8 commonly used LLM services across 3 major LLM providers, including market-leads OpenAI and Anthropic. We conduct a detailed analysis of failure recovery statistical properties, temporal patterns, co-occurrence, and the impact range of outage-causing incidents. We make over 10 observations, among which: (1) Failures in OpenAI's ChatGPT take longer to resolve but occur less frequently than those in Anthropic's Claude;(2) OpenAI and Anthropic service failures exhibit strong weekly and monthly periodicity; and (3) OpenAI services offer better failure-isolation than Anthropic services. Our research explains LLM failure characteristics and thus enables optimization in building and using LLM systems. FAIR data and code are publicly available on https://zenodo.org/records/14018219 and https://github.com/atlarge-research/llm-service-analysis.

[Arxiv](https://arxiv.org/abs/2501.12469)