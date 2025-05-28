# 长上下文扩展：多智能体驱动的问题协作实现分而治之

发布时间：2025年05月26日

`Agent` `信息检索`

> Long Context Scaling: Divide and Conquer via Multi-Agent Question-driven Collaboration

# 摘要

> 处理长上下文已成为现代大型语言模型（LLMs）的关键能力。现有基于代理的分治方法在处理长上下文时存在三大局限：累积延迟过高、信息损失加剧以及破坏文本依赖关系。针对这些问题，我们提出了一种结合问题驱动工作流和动态分割的新型多代理框架XpandA（Expand-Agent），以实现更高效的长上下文处理。XpandA的三大创新点包括：1）动态文本分割技术，能够自适应调节上下文窗口填充率，适应不同长度的输入序列；2）问题引导的知识更新协议，通过集中共享内存构建跨分区的一致性知识；3）基于问题-信息对的状态追踪，选择性重放特定分区以解决倒序结构问题。我们在长度从1k到1M的多个长上下文基准测试中验证了XpandA的性能，结果显示XpandA不仅能够处理超长序列，而且在提升LLMs的长上下文能力方面表现出显著优势，相比全上下文、RAG和传统基于代理的方法，性能提升了20%，推理速度更是提升了1.5倍。

> Processing long contexts has become a critical capability for modern large language models (LLMs). Existing works leverage agent-based divide-and-conquer methods for processing long contexts. But these methods face crucial limitations, including prohibitive accumulated latency and amplified information loss from excessive agent invocations, and the disruption of inherent textual dependencies by immoderate partitioning. In this paper, we propose a novel multi-agent framework XpandA (Expand-Agent) coupled with question-driven workflow and dynamic partitioning for robust long-context processing. XpandA overcomes these limitations through: 1) dynamic partitioning of long texts, which adaptively modulates the filling rate of context windows for input sequences of vastly varying lengths; 2) question-guided protocol to update flat information ensembles within centralized shared memory, constructing consistent inter-agent knowledge across partitions; and 3) selectively replaying specific partitions based on the state-tracking of question-information couples to promote the resolution of inverted-order structures across partitions (e.g., flashbacks). We perform a comprehensive evaluation of XpandA on multiple long-context benchmarks with length varying from 1k to 1M, demonstrating XpandA's feasibility for processing ultra-long sequences and its significant effectiveness in enhancing the long-context capabilities of various LLMs by achieving 20\% improvements and 1.5x inference speedup over baselines of full-context, RAG and previous agent-based methods.

[Arxiv](https://arxiv.org/abs/2505.20625)