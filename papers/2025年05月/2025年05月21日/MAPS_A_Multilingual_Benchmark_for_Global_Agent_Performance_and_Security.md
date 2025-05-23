# # MAPS：一个多语言基准测试，评估全球智能体的性能与安全。

发布时间：2025年05月21日

`Agent` `人工智能` `语言技术`

> MAPS: A Multilingual Benchmark for Global Agent Performance and Security

# 摘要

> 基于大型语言模型（LLMs）并与工具及记忆进行交互的智能体AI系统，在能力与应用范围上迅速发展。然而，由于LLMs在多语言环境中表现欠佳，通常导致性能下降和安全性降低，智能体系统可能继承这些局限性。这引发了对这些系统全球可用性的担忧，因为使用非英语语言的用户可能会遇到不可靠或存在安全风险的智能体行为。尽管对评估智能体AI的兴趣日益增长，现有的基准测试却仅专注于英语环境，忽视了多语言场景。为填补这一空白，我们提出了MAPS，一个多语言基准测试套件，旨在评估智能体AI系统在多种语言和任务中的表现。MAPS基于四个广泛使用的智能体基准测试构建：GAIA（现实世界任务）、SWE-bench（代码生成）、MATH（数学推理）以及智能体安全基准（安全）。我们将每个数据集翻译成十种不同的语言，最终得到805个独特的任务和8,855个特定语言的实例。我们的基准测试套件支持对多语言环境如何影响智能体性能和鲁棒性的系统性分析。实证结果显示，从英语切换到其他语言时，性能和安全性均显著下降，且下降程度因任务而异，与翻译输入量相关。基于这些发现，我们提供了切实可行的建议，以指导多语言环境下智能体AI系统的开发与评估。这项工作建立了一个标准化的评估框架，推动未来研究朝着公平、可靠且全球可访问的智能体AI方向发展。MAPS基准测试套件现已公开，可通过以下链接访问：https://huggingface.co/datasets/Fujitsu-FRE/MAPS

> Agentic AI systems, which build on Large Language Models (LLMs) and interact with tools and memory, have rapidly advanced in capability and scope. Yet, since LLMs have been shown to struggle in multilingual settings, typically resulting in lower performance and reduced safety, agentic systems risk inheriting these limitations. This raises concerns about the global accessibility of such systems, as users interacting in languages other than English may encounter unreliable or security-critical agent behavior. Despite growing interest in evaluating agentic AI, existing benchmarks focus exclusively on English, leaving multilingual settings unexplored. To address this gap, we propose MAPS, a multilingual benchmark suite designed to evaluate agentic AI systems across diverse languages and tasks. MAPS builds on four widely used agentic benchmarks - GAIA (real-world tasks), SWE-bench (code generation), MATH (mathematical reasoning), and the Agent Security Benchmark (security). We translate each dataset into ten diverse languages, resulting in 805 unique tasks and 8,855 total language-specific instances. Our benchmark suite enables a systematic analysis of how multilingual contexts affect agent performance and robustness. Empirically, we observe consistent degradation in both performance and security when transitioning from English to other languages, with severity varying by task and correlating with the amount of translated input. Building on these findings, we provide actionable recommendations to guide agentic AI systems development and assessment under multilingual settings. This work establishes a standardized evaluation framework, encouraging future research towards equitable, reliable, and globally accessible agentic AI. MAPS benchmark suite is publicly available at https://huggingface.co/datasets/Fujitsu-FRE/MAPS

[Arxiv](https://arxiv.org/abs/2505.15935)