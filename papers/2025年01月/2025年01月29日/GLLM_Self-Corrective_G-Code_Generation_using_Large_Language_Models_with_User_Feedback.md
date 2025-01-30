# GLLM: 基于大型语言模型与用户反馈的自我修正G代码生成

发布时间：2025年01月29日

`LLM应用

**理由**：该论文描述了一个利用大型语言模型（LLMs）来自动生成CNC加工G代码的工具GLLM。它通过微调模型、使用检索增强生成（RAG）机制以及自校正代码生成方法等技术，解决了手动编写G代码的难题。这些内容主要涉及LLM在实际应用中的使用，因此分类为LLM应用。` `制造业` `数控加工`

> GLLM: Self-Corrective G-Code Generation using Large Language Models with User Feedback

# 摘要

> 本文介绍了一种名为GLLM的创新工具，它利用大型语言模型（LLMs）从自然语言指令自动生成用于CNC加工的G代码。GLLM通过弥合人类可读任务描述与机器可执行代码之间的鸿沟，解决了手动编写G代码的难题。该系统集成了经过微调的StarCoder-3B模型，并通过领域特定数据和检索增强生成（RAG）机制进行了优化。GLLM采用先进的提示策略和自校正代码生成方法，确保生成的G代码在语法和语义上的准确性。其架构包含强大的验证机制，如语法检查、G代码验证以及基于Hausdorff距离的功能评估。通过这些技术，GLLM旨在降低CNC编程门槛，让没有编程经验的用户也能轻松上手，同时确保G代码生成的高精度和可靠性。

> This paper introduces GLLM, an innovative tool that leverages Large Language Models (LLMs) to automatically generate G-code from natural language instructions for Computer Numerical Control (CNC) machining. GLLM addresses the challenges of manual G-code writing by bridging the gap between human-readable task descriptions and machine-executable code. The system incorporates a fine-tuned StarCoder-3B model, enhanced with domain-specific training data and a Retrieval-Augmented Generation (RAG) mechanism. GLLM employs advanced prompting strategies and a novel self-corrective code generation approach to ensure both syntactic and semantic correctness of the generated G-code. The architecture includes robust validation mechanisms, including syntax checks, G-code-specific verifications, and functional correctness evaluations using Hausdorff distance. By combining these techniques, GLLM aims to democratize CNC programming, making it more accessible to users without extensive programming experience while maintaining high accuracy and reliability in G-code generation.

[Arxiv](https://arxiv.org/abs/2501.17584)