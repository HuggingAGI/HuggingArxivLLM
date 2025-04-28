# # 基于可追溯RFC文档解释的网络协议解析器验证方法

发布时间：2025年04月24日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）来解决网络协议实现的正确性验证问题，特别是针对oracle问题和可追溯性问题。论文提出了一种基于LLMs的解决方案，将结构化的RFC文档转换为形式化的协议消息规范，并利用这些规范作为准oracle来验证协议解析器。研究结果表明，这种方法在检测协议实现缺陷方面优于现有方案，展示了LLMs在软件验证中的实际应用。因此，这篇论文属于LLM应用类别。` `软件工程`

> Validating Network Protocol Parsers with Traceable RFC Document Interpretation

# 摘要

> 网络协议实现的正确性验证面临两大挑战：oracle 问题和可追溯性问题。前者关乎如何判定协议实现存在缺陷，尤其是当缺陷无明显症状时；后者则帮助开发者定位实现与协议规范的偏差，从而便于修复。与仅关注单一问题的现有研究不同，本研究同时应对这两个挑战，并提出了一种基于大型语言模型（LLMs）的有效解决方案。我们的核心发现是，网络协议通常附带结构化的 RFC 文档，这些文档可借助 LLMs 转换为形式化的协议消息规范。尽管这些规范可能因 LLMs 的生成特性而存在误差，但它们可用作准 oracle 验证协议解析器，同时验证结果又能逐步优化 oracle。由于 oracle 源自文档，我们发现的任何协议实现缺陷均可追溯至文档，从而解决了可追溯性问题。我们通过 C、Python 和 Go 编写的九种网络协议及其实现对方法进行了全面评估。结果显示，我们的方法优于现有最佳方案，已检测到 69 个缺陷，其中 36 个已确认。这表明，基于自然语言规范实现软件验证的全自动化的时代即将到来，这一过程曾被视为主要依赖人工分析规范文档并推导测试预期输出。

> Validating the correctness of network protocol implementations is highly challenging due to the oracle and traceability problems. The former determines when a protocol implementation can be considered buggy, especially when the bugs do not cause any observable symptoms. The latter allows developers to understand how an implementation violates the protocol specification, thereby facilitating bug fixes. Unlike existing works that rarely take both problems into account, this work considers both and provides an effective solution using recent advances in large language models (LLMs). Our key observation is that network protocols are often released with structured specification documents, a.k.a. RFC documents, which can be systematically translated to formal protocol message specifications via LLMs. Such specifications, which may contain errors due to the hallucination of LLMs, are used as a quasi-oracle to validate protocol parsers, while the validation results in return gradually refine the oracle. Since the oracle is derived from the document, any bugs we find in a protocol implementation can be traced back to the document, thus addressing the traceability problem. We have extensively evaluated our approach using nine network protocols and their implementations written in C, Python, and Go. The results show that our approach outperforms the state-of-the-art and has detected 69 bugs, with 36 confirmed. The project also demonstrates the potential for fully automating software validation based on natural language specifications, a process previously considered predominantly manual due to the need to understand specification documents and derive expected outputs for test inputs.

[Arxiv](https://arxiv.org/abs/2504.18050)