# # 语义解析框架：端到端时间归一化

发布时间：2025年07月08日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLMs）生成可执行代码，并将其应用于时间转换任务中的数据增强。通过构建基于LLMs的自动数据增强流水线，研究人员展示了LLMs在生成代码和提高模型性能方面的应用潜力，属于LLM的应用领域。` `信息检索` `问答系统`

> A Semantic Parsing Framework for End-to-End Time Normalization

# 摘要

> 时间转换是将自然语言中的时间表达转化为机器可读形式的关键任务，它为信息检索、问答系统和临床决策支持等应用提供了重要支持。然而，传统基于ISO-TimeML框架的系统在表达能力和复杂时间表达处理上存在局限，尤其在处理组合性、事件相对性和多跨度时间表达时表现不足。本研究提出了一种基于SCATE框架的时间归一化新方法，该框架通过符号和组合运算符定义时间语义。我们开发了完全可执行的SCATE Python库，并证明大型语言模型（LLMs）能够生成可执行的SCATE代码。借助这一能力，我们构建了一条基于LLMs的自动数据增强流水线，用于生成大规模标注数据，并在代码级别进行验证。实验结果表明，基于增强数据训练的小规模本地部署模型不仅性能强劲，甚至超越了其大型语言模型的性能，从而实现了准确、实用且可解释的时间转换。

> Time normalization is the task of converting natural language temporal expressions into machine-readable representations. It underpins many downstream applications in information retrieval, question answering, and clinical decision-making. Traditional systems based on the ISO-TimeML schema limit expressivity and struggle with complex constructs such as compositional, event-relative, and multi-span time expressions. In this work, we introduce a novel formulation of time normalization as a code generation task grounded in the SCATE framework, which defines temporal semantics through symbolic and compositional operators. We implement a fully executable SCATE Python library and demonstrate that large language models (LLMs) can generate executable SCATE code. Leveraging this capability, we develop an automatic data augmentation pipeline using LLMs to synthesize large-scale annotated data with code-level validation. Our experiments show that small, locally deployable models trained on this augmented data can achieve strong performance, outperforming even their LLM parents and enabling practical, accurate, and interpretable time normalization.

[Arxiv](https://arxiv.org/abs/2507.06450)