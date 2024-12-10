# 《用于网络代理研究的 BrowserGym 生态系统》

发布时间：2024年12月06日

`Agent` `网络代理` `自动化创新`

> The BrowserGym Ecosystem for Web Agent Research

# 摘要

> BrowserGym 生态系统应对了对网络代理进行高效评估和基准测试的与日俱增的需求，尤其是那些借助自动化和大型语言模型（LLMs）来完成网络交互任务的代理。现有的诸多基准测试存在碎片化以及评估方法不一致的情况，导致难以达成可靠的比较和可重现的结果。BrowserGym 意在通过提供统一的、类似 gym 的环境，具备清晰界定的观察和行动空间，推动不同基准测试的标准化评估。结合 AgentLab 这一辅助框架，它有助于代理的创建、测试和分析，BrowserGym 为整合新的基准测试赋予了灵活性，同时保障了一致的评估和全面的实验管理。这种标准化手段旨在缩减开发网络代理的时间和复杂度，支持更可靠的比较，并促进对代理行为的深度分析，有可能造就更具适应性和能力的代理，最终加快 LLM 驱动的自动化创新进程。作为佐证，我们开展了首次大规模、多基准的网络代理实验，并对比了 6 个顶尖的 LLMs 在 BrowserGym 中当前所有基准测试里的表现。在其他发现中，我们的结果凸显了 OpenAI 和 Anthropic 的最新模型之间的显著差异，Claude-3.5-Sonnet 在几乎所有基准测试中都名列前茅，只有在与视觉相关的任务中，GPT-4o 更出色。尽管有这些进展，我们的结果强调，鉴于现实世界网络环境的固有复杂性以及当前模型的局限性，构建强大且高效的网络代理依旧是一项重大挑战。

> The BrowserGym ecosystem addresses the growing need for efficient evaluation and benchmarking of web agents, particularly those leveraging automation and Large Language Models (LLMs) for web interaction tasks. Many existing benchmarks suffer from fragmentation and inconsistent evaluation methodologies, making it challenging to achieve reliable comparisons and reproducible results. BrowserGym aims to solve this by providing a unified, gym-like environment with well-defined observation and action spaces, facilitating standardized evaluation across diverse benchmarks. Combined with AgentLab, a complementary framework that aids in agent creation, testing, and analysis, BrowserGym offers flexibility for integrating new benchmarks while ensuring consistent evaluation and comprehensive experiment management. This standardized approach seeks to reduce the time and complexity of developing web agents, supporting more reliable comparisons and facilitating in-depth analysis of agent behaviors, and could result in more adaptable, capable agents, ultimately accelerating innovation in LLM-driven automation. As a supporting evidence, we conduct the first large-scale, multi-benchmark web agent experiment and compare the performance of 6 state-of-the-art LLMs across all benchmarks currently available in BrowserGym. Among other findings, our results highlight a large discrepancy between OpenAI and Anthropic's latests models, with Claude-3.5-Sonnet leading the way on almost all benchmarks, except on vision-related tasks where GPT-4o is superior. Despite these advancements, our results emphasize that building robust and efficient web agents remains a significant challenge, due to the inherent complexity of real-world web environments and the limitations of current models.

[Arxiv](https://arxiv.org/abs/2412.05467)