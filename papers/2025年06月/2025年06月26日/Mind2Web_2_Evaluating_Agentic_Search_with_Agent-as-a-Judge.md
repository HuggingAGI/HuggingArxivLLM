# Mind2Web 2：以Agent为裁判评估智能体搜索

发布时间：2025年06月26日

`Agent` `人工智能` `搜索引擎`

> Mind2Web 2: Evaluating Agentic Search with Agent-as-a-Judge

# 摘要

> 智能体搜索系统（如Deep Research）代表了用户与大规模网络信息交互方式的重大变革。这些系统中，大型语言模型能够自主浏览网络、合成信息并返回详尽且有文献支持的答案。虽然智能体搜索在提升效率和实现认知卸载方面潜力巨大，但其日益增长的复杂性和开放性已经超越了现有评估基准和方法论，这些基准和方法大多基于短搜索范围和静态答案的假设。

本文介绍了Mind2Web 2，这是一个包含130个现实、高质量且具有长期规划的基准任务，要求实时网络浏览和广泛信息整合。构建过程中投入了超过1000小时的人工劳动。为应对评估时间变化和复杂答案的挑战，我们提出了一种创新的Agent-as-a-Judge框架。我们的方法基于树状结构的评分标准设计，构建任务特定的评估代理，以自动评估答案的正确性和来源归属。

我们对九种前沿智能体搜索系统和人类表现进行了全面评估，并进行了详细错误分析，以获得未来发展的洞见。表现最佳的系统OpenAI Deep Research已能实现50-70%的人类性能，同时仅花费一半时间，展现出巨大潜力。总体而言，Mind2Web 2为开发和评估下一代智能体搜索系统提供了严格的基础。

> Agentic search such as Deep Research systems, where large language models autonomously browse the web, synthesize information, and return comprehensive citation-backed answers, represents a major shift in how users interact with web-scale information. While promising greater efficiency and cognitive offloading, the growing complexity and open-endedness of agentic search have outpaced existing evaluation benchmarks and methodologies, which largely assume short search horizons and static answers. In this paper, we introduce Mind2Web 2, a benchmark of 130 realistic, high-quality, and long-horizon tasks that require real-time web browsing and extensive information synthesis, constructed with over 1,000 hours of human labor. To address the challenge of evaluating time-varying and complex answers, we propose a novel Agent-as-a-Judge framework. Our method constructs task-specific judge agents based on a tree-structured rubric design to automatically assess both answer correctness and source attribution. We conduct a comprehensive evaluation of nine frontier agentic search systems and human performance, along with a detailed error analysis to draw insights for future development. The best-performing system, OpenAI Deep Research, can already achieve 50-70% of human performance while spending half the time, showing a great potential. Altogether, Mind2Web 2 provides a rigorous foundation for developing and benchmarking the next generation of agentic search systems.

[Arxiv](https://arxiv.org/abs/2506.21506)