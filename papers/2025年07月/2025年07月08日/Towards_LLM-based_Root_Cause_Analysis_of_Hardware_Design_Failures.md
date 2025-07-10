# # 基于LLM的硬件设计故障根本原因分析研究

发布时间：2025年07月08日

`LLM应用

摘要讨论了大型语言模型在硬件设计和安全性分析中的应用，特别是如何辅助解释设计问题和缺陷，属于LLM的实际应用。` `硬件设计` `硬件工程`

> Towards LLM-based Root Cause Analysis of Hardware Design Failures

# 摘要

> 大型语言模型（LLMs）的进步为开发支持数字硬件设计的工具带来了新机遇。本研究探讨了LLMs如何辅助解释在综合与仿真过程中揭示的设计问题和缺陷的根本原因，这是LLMs在硬件设计和硬件安全性分析中广泛应用的关键里程碑。我们的研究发现令人鼓舞的结果：在包含34种不同缺陷场景的语料库中，OpenAI的o3-mini推理模型在pass@5评分标准下准确率达到100%，其他先进模型和配置通常也能实现超过80%的性能，甚至在结合检索增强生成时超过90%。

> With advances in large language models (LLMs), new opportunities have emerged to develop tools that support the digital hardware design process. In this work, we explore how LLMs can assist with explaining the root cause of design issues and bugs that are revealed during synthesis and simulation, a necessary milestone on the pathway towards widespread use of LLMs in the hardware design process and for hardware security analysis. We find promising results: for our corpus of 34 different buggy scenarios, OpenAI's o3-mini reasoning model reached a correct determination 100% of the time under pass@5 scoring, with other state of the art models and configurations usually achieving more than 80% performance and more than 90% when assisted with retrieval-augmented generation.

[Arxiv](https://arxiv.org/abs/2507.06512)