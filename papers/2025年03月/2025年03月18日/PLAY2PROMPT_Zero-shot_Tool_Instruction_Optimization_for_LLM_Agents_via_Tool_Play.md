# PLAY2PROMPT：借助工具交互，实现LLM智能体的零样本工具指令优化

发布时间：2025年03月18日

`LLM应用` `人工智能` `软件工程`

> PLAY2PROMPT: Zero-shot Tool Instruction Optimization for LLM Agents via Tool Play

# 摘要

> 大型语言模型（LLMs）与专用工具的结合日益紧密，但实际应用中仍面临文档缺失或质量低下的零-shot工具使用需求。现有方法多依赖人工干预或标注数据，难以满足真正的零-shot场景要求。为此，我们提出了一种名为PLAY2PROMPT的自动化框架，通过系统性地探索工具的输入输出行为，无需任何标注数据即可完善工具文档并生成使用示例。这些示例不仅为模型推理提供指导，还能用于进一步优化工具应用。实验结果表明，PLAY2PROMPT显著提升了开放与封闭模型在零-shot工具使用上的表现，为领域工具的集成提供了一个高效可扩展的解决方案。


> Large language models (LLMs) are increasingly integrated with specialized external tools, yet many tasks demand zero-shot tool usage with minimal or noisy documentation. Existing solutions rely on manual rewriting or labeled data for validation, making them inapplicable in true zero-shot settings. To address these challenges, we propose PLAY2PROMPT, an automated framework that systematically "plays" with each tool to explore its input-output behaviors. Through this iterative trial-and-error process, PLAY2PROMPT refines tool documentation and generates usage examples without any labeled data. These examples not only guide LLM inference but also serve as validation to further enhance tool utilization. Extensive experiments on real-world tasks demonstrate that PLAY2PROMPT significantly improves zero-shot tool performance across both open and closed models, offering a scalable and effective solution for domain-specific tool integration.

[Arxiv](https://arxiv.org/abs/2503.14432)