# ModelForge: 借助生成式AI优化安全协议开发流程

发布时间：2025年06月08日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLM）来自动将自然语言协议规范转换为形式化表示，用于安全协议的验证。通过微调LLM生成CPSA协议定义，ModelForge简化了安全协议开发中的形式化方法，属于LLM的实际应用。` `协议开发`

> ModelForge: Using GenAI to Improve the Development of Security Protocols

# 摘要

> 形式化方法可用于验证安全协议，但自然语言协议规范向形式化表示的转换复杂性往往阻碍了其采用。本文介绍了ModelForge，一款能够自动将协议规范转换为密码协议形状分析器（CPSA）适用格式的创新工具。通过借助自然语言处理（NLP）和生成式人工智能（GenAI）的最新进展，ModelForge能够处理协议规范并生成CPSA协议定义。这种方法减少了手动操作的需求，使形式化分析更加易于使用。我们通过微调大型语言模型（LLM）来生成CPSA协议定义，评估了ModelForge的表现，并将其与其它流行的LLM进行了对比。评估结果显示，ModelForge始终能够生成高质量的输出，在语法准确性上表现出色，尽管在处理某些协议细节时仍需进一步优化。这项工作的贡献包括设计一种旨在简化安全协议开发中形式化方法采用的翻译工具的架构和概念验证。

> Formal methods can be used for verifying security protocols, but their adoption can be hindered by the complexity of translating natural language protocol specifications into formal representations. In this paper, we introduce ModelForge, a novel tool that automates the translation of protocol specifications for the Cryptographic Protocol Shapes Analyzer (CPSA). By leveraging advances in Natural Language Processing (NLP) and Generative AI (GenAI), ModelForge processes protocol specifications and generates a CPSA protocol definition. This approach reduces the manual effort required, making formal analysis more accessible. We evaluate ModelForge by fine-tuning a large language model (LLM) to generate protocol definitions for CPSA, comparing its performance with other popular LLMs. The results from our evaluation show that ModelForge consistently produces quality outputs, excelling in syntactic accuracy, though some refinement is needed to handle certain protocol details. The contributions of this work include the architecture and proof of concept for a translating tool designed to simplify the adoption of formal methods in the development of security protocols.

[Arxiv](https://arxiv.org/abs/2506.07010)