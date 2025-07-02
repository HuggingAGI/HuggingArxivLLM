# 基于 AST 的 LLM 代码合成方法，针对 SVRF

发布时间：2025年06月30日

`LLM应用` `半导体` `软件工程`

> An AST-guided LLM Approach for SVRF Code Synthesis

# 摘要

> 标准验证规则格式 (SVRF) 在半导体领域（如 DRC、LVS 和 OPC）至关重要，但随着工艺节点进步，复杂设计规则让传统开发方法失效，暴露出专业知识缺口。本文提出结合 AST 嵌入与 RAG 的新方法，提升 SVRF 代码合成，通过结构验证和领域见解确保准确性和减少错误。

我们评估了 T5 型模型，并提出 SVRF 专用评分框架，补充传统指标。AST 提供严格结构验证，RAG 融入领域知识，优化代码生成流程。

在 740 个 DRC 规则的基准测试中，我们的方法使代码生成准确率提升 40%。结合行业知识与先进策略，优化 SVRF 开发，提升效率。用户可加速设计迭代，减少手动修正，显著提高生产力。


> Standard Verification Rule Format (SVRF) is essential for semiconductor applications like Design Rule Check (DRC), Layout Versus Schematic (LVS), and Optical Proximity Correction (OPC) and it faces challenges as advancing nodes create complex design rules that renders traditional SVRF development ineffective and highlight an expertise gap. This paper introduces a novel methodology integrating Abstract Syntax Tree (AST) embedding and Retrieval-Augmented Generation (RAG) for enhanced SVRF code synthesis, ensuring semantic accuracy and error minimization through structural validation with domain-specific insights for precise code generation.
  We evaluate different T5-based models and propose an innovative SVRF-specific scoring framework that complements standard metrics like BLEU and ROUGE-L. In our approach, AST provides rigorous structural validation, while RAG infuses relevant domain knowledge, effectively enhancing the code generation workflow.
  Testing on a comprehensive benchmark of 740 DRC rule implementations, our methodology demonstrates up to a 40\% improvement in code generation accuracy compared to basic text-based fine-tuning process. This fusion of industry expertise with advanced coding strategies not only optimizes SVRF development under limited dataset constraints but also creates a more intuitive and efficient coding environment. Consequently, users can rapidly iterate through design cycles, reduce manual error correction, and significantly improve overall productivity.

[Arxiv](https://arxiv.org/abs/2507.00352)