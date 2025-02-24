# CODEPROMPTZIP：为编程任务中的基于语言模型的检索增强生成设计的特定代码提示压缩方法

发布时间：2025年02月19日

`RAG` `软件开发` `编程工具`

> CODEPROMPTZIP: Code-specific Prompt Compression for Retrieval-Augmented Generation in Coding Tasks with LMs

# 摘要

> 检索增强生成（RAG）通过整合检索到的代码示例来提升编码任务的表现。然而，过长的提示（通常超过数万个token）带来了语言模型（LM）上下文窗口限制和高计算成本的挑战。现有的提示压缩技术主要集中在自然语言领域，缺乏针对代码的定制化解决方案。为了解决这一差距，我们提出了CodePromptZip框架，该框架通过在将代码示例整合到RAG工作流之前对其进行压缩来优化性能。我们的框架采用类型感知、优先级驱动的策略构建训练样本，用于训练代码压缩模型。通过程序分析，我们识别出token类型（例如，标识符）并进行消融分析，根据其对任务性能的影响排序移除优先级。然后，我们使用这些样本训练一个小型LM作为压缩器，使其能够根据指定的压缩比例灵活地进行压缩，同时尽量减少性能下降。特别地，压缩器还增强了复制机制，允许直接从原始代码片段中复制token。实验结果表明，CodePromptZip超越了基于熵和蒸馏的最先进基线，在Assertion Generation、Bugs2Fix和Code Suggestion任务上分别比最佳基线提升了23.4%、28.7%和8.7%。

> Retrieval-Augmented Generation (RAG) enhances coding tasks by incorporating retrieved code examples into prompts. However, lengthy prompts, often exceeding tens of thousands of tokens, introduce challenges related to limited context windows of language models (LMs) and high computational costs. Existing prompt compression techniques focus on natural language, lacking tailored solutions for code. To address the gap, we propose CodePromptZip, a framework that compresses code examples before integrating into RAG workflows. Our framework employs a type-aware, priority-driven strategy to construct training samples for training code compression model. By using program analysis, we identify token types (e.g., Identifier) and perform ablation analysis to rank their removal priorities based on their impact on task performance. We then train a small LM as the compressor on these samples, enabling flexible compression conditioned on specified ratios while minimizing performance degradation. Specially, the compressor is augmented with a copy mechanism, allowing tokens to be directly copied from the original code snippets. Evaluation results show that CodePromptZip surpasses SOTA entropy-based and distillation-based baselines, improving by 23.4%, 28.7%, and 8.7% over the best baseline for Assertion Generation, Bugs2Fix, and Code Suggestion, respectively.

[Arxiv](https://arxiv.org/abs/2502.14925)