# CDE-Mapper：借助检索增强型语言模型，实现临床数据元素与受控词汇表的精准映射

发布时间：2025年05月07日

`LLM应用` `数据整合`

> CDE-Mapper: Using Retrieval-Augmented Language Models for Linking Clinical Data Elements to Controlled Vocabularies

# 摘要

> 临床数据元素 (CDEs) 的标准化旨在确保不同医疗系统之间患者信息的一致性和全面性。然而，现有方法在处理具有不同表示形式和复杂结构的 CDEs 时常常表现不佳，这阻碍了临床研究中的数据整合和互操作性。我们推出了 CDE-Mapper，一个创新性框架，结合检索增强生成方法与大型语言模型，实现将 CDEs 自动链接到受控词汇表。我们的模块化方法通过查询分解管理不同复杂度的 CDEs，将专家定义的规则整合到提示工程中，并结合上下文学习与多个检索器组件解决术语歧义。此外，我们提出了一种通过人工反馈验证的知识库，能够在实现未来应用中准确的概念链接的同时，最大限度地降低计算成本。在四个多样化的数据集上，CDE-Mapper 的平均准确率比基线方法提高了 7.2%。这项工作展示了先进语言模型在提升数据整合能力方面的潜力，并为临床决策支持系统和研究能力的显著提升提供了支持。

> The standardization of clinical data elements (CDEs) aims to ensure consistent and comprehensive patient information across various healthcare systems. Existing methods often falter when standardizing CDEs of varying representation and complex structure, impeding data integration and interoperability in clinical research. We introduce CDE-Mapper, an innovative framework that leverages Retrieval-Augmented Generation approach combined with Large Language Models to automate the linking of CDEs to controlled vocabularies. Our modular approach features query decomposition to manage varying levels of CDEs complexity, integrates expert-defined rules within prompt engineering, and employs in-context learning alongside multiple retriever components to resolve terminological ambiguities. In addition, we propose a knowledge reservoir validated by a human-in-loop approach, achieving accurate concept linking for future applications while minimizing computational costs. For four diverse datasets, CDE-Mapper achieved an average of 7.2\% higher accuracy improvement compared to baseline methods. This work highlights the potential of advanced language models in improving data harmonization and significantly advancing capabilities in clinical decision support systems and research.

[Arxiv](https://arxiv.org/abs/2505.04365)