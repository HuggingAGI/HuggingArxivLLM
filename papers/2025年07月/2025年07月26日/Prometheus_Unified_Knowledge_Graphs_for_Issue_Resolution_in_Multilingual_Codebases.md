# Prometheus：为多语言代码库中的问题解决提供统一知识图谱

发布时间：2025年07月26日

`Agent` `软件工程` `代码分析`

> Prometheus: Unified Knowledge Graphs for Issue Resolution in Multilingual Codebases

# 摘要

> 语言模型（LM）代理如SWE-agent和OpenHands在自动化问题解决方面有所突破，但现有方法多局限于处理Python问题，并依赖SWE-bench中预构建的容器，这限制了其在多语言仓库中的实际应用。为此，我们推出Prometheus，专注于解决真实世界中的问题，超越传统基准测试的局限。

Prometheus是一个多代理系统，它将整个代码仓库转化为统一的知识图谱，从而优化问题解决的上下文检索过程。通过将文件、抽象语法树和自然语言文本编码为类型化节点和五种通用边类型的知识图谱，Prometheus实现了多语言支持。借助Neo4j进行图持久化，Prometheus能够在大型代码库上进行高效、结构化的推理。

Prometheus集成DeepSeek-V3模型，在SWE-bench Lite和SWE-bench Multilingual基准测试中分别解决了28.67%和13.7%的问题，每次问题解决的平均API成本仅为$0.23和$0.38。值得注意的是，Prometheus成功解决了10个先前未处理的独特问题，并且是首个在七种编程语言中均展示出色效果的系统。此外，Prometheus还具备处理LangChain和OpenHands仓库中真实GitHub问题的能力。

我们已将Prometheus开源，项目地址为：https://github.com/Pantheon-temple/Prometheus

> Language model (LM) agents, such as SWE-agent and OpenHands, have made progress toward automated issue resolution. However, existing approaches are often limited to Python-only issues and rely on pre-constructed containers in SWE-bench with reproduced issues, restricting their applicability to real-world and work for multi-language repositories. We present Prometheus, designed to resolve real-world issues beyond benchmark settings. Prometheus is a multi-agent system that transforms an entire code repository into a unified knowledge graph to guide context retrieval for issue resolution. Prometheus encodes files, abstract syntax trees, and natural language text into a graph of typed nodes and five general edge types to support multiple programming languages. Prometheus uses Neo4j for graph persistence, enabling scalable and structured reasoning over large codebases. Integrated by the DeepSeek-V3 model, Prometheus resolves 28.67% and 13.7% of issues on SWE-bench Lite and SWE-bench Multilingual, respectively, with an average API cost of $0.23 and $0.38 per issue. Prometheus resolves 10 unique issues not addressed by prior work and is the first to demonstrate effectiveness across seven programming languages. Moreover, it shows the ability to resolve real-world GitHub issues in the LangChain and OpenHands repositories. We have open-sourced Prometheus at: https://github.com/Pantheon-temple/Prometheus

[Arxiv](https://arxiv.org/abs/2507.19942)