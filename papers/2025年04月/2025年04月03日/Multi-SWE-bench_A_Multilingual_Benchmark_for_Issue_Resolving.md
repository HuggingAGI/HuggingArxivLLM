# Multi-SWE-bench：一个多语言的故障排除基准测试

发布时间：2025年04月03日

`LLM应用` `软件工程` `编程语言`

> Multi-SWE-bench: A Multilingual Benchmark for Issue Resolving

# 摘要

> 代码修复任务旨在通过修改代码库生成补丁，解决具体问题。然而，现有的基准测试如 SWE-bench 过于专注于 Python，难以全面评估大型语言模型（LLMs）在多元软件生态中的表现。为此，我们推出了多语言代码修复基准测试 Multi-SWE-bench，涵盖 Java、TypeScript、JavaScript、Go、Rust、C 和 C++ 等语言。该基准测试包含 1,632 个高质量实例，由 68 位专家标注者从 2,456 个候选中精选而出，确保评估的准确性和可靠性。基于 Multi-SWE-bench，我们采用三种代表性方法（Agentless、SWE-agent 和 OpenHands）对多款先进模型进行了全面评估，并通过深入分析揭示了关键实证洞见。此外，我们发起了 Multi-SWE-RL 开源社区，致力于为代码修复任务构建大规模强化学习（RL）训练数据集。作为初步贡献，我们发布了包含 4,723 个结构良好实例的数据集，覆盖七种编程语言，为该领域的 RL 研究奠定了坚实基础。更重要的是，我们开源了完整的数据生产管道和详细教程，鼓励开源社区持续贡献，共同扩展数据集。我们期待 Multi-SWE-bench 和不断壮大的 Multi-SWE-RL 社区能够成为推动 RL 发展的重要催化剂，让我们离 AGI 的曙光更进一步。

> The task of issue resolving is to modify a codebase to generate a patch that addresses a given issue. However, existing benchmarks, such as SWE-bench, focus almost exclusively on Python, making them insufficient for evaluating Large Language Models (LLMs) across diverse software ecosystems. To address this, we introduce a multilingual issue-resolving benchmark, called Multi-SWE-bench, covering Java, TypeScript, JavaScript, Go, Rust, C, and C++. It includes a total of 1,632 high-quality instances, which were carefully annotated from 2,456 candidates by 68 expert annotators, ensuring that the benchmark can provide an accurate and reliable evaluation. Based on Multi-SWE-bench, we evaluate a series of state-of-the-art models using three representative methods (Agentless, SWE-agent, and OpenHands) and present a comprehensive analysis with key empirical insights. In addition, we launch a Multi-SWE-RL open-source community, aimed at building large-scale reinforcement learning (RL) training datasets for issue-resolving tasks. As an initial contribution, we release a set of 4,723 well-structured instances spanning seven programming languages, laying a solid foundation for RL research in this domain. More importantly, we open-source our entire data production pipeline, along with detailed tutorials, encouraging the open-source community to continuously contribute and expand the dataset. We envision our Multi-SWE-bench and the ever-growing Multi-SWE-RL community as catalysts for advancing RL toward its full potential, bringing us one step closer to the dawn of AGI.

[Arxiv](https://arxiv.org/abs/2504.02605)