# _verbose列表操作（VLO）：超越长上下文，揭开LLM推理盲点_

发布时间：2025年06月05日

`LLM理论` `人工智能`

> Verbose ListOps (VLO): Beyond Long Context -- Unmasking LLM's Reasoning Blind Spots

# 摘要

> 大型语言模型（LLMs）在提取文本事实方面表现出色，但在处理嵌套叙事推理时却显得力不从心。现有长上下文和多跳问答基准测试未能充分检验这一能力，要么缺乏现实的干扰项，要么未能分离上下文长度与推理复杂度，从而掩盖了LLMs的一个根本性局限。我们引入了Verbose ListOps，这是一个全新的基准测试，它通过程序将ListOps计算转换为冗长但连贯的故事。这种设计独特地迫使模型进行嵌套推理问题的内部计算和状态管理，同时隐藏中间结果，并提供了对叙事规模和推理难度的精细控制。虽然像LongReason（2025）这样的基准测试推动了多跳问答问题上下文大小的合成扩展方法，但Verbose ListOps精准地揭示了LLMs的一个弱点：在语义相关但具有干扰性的叙事中，难以管理嵌套子推理的状态。我们的实验表明，领先的大模型（如OpenAI o4、Gemini 2.5 Pro）在Verbose ListOps上的性能在适度长度（约10k token）的叙事下迅速下降，尽管它们能够轻松解决原始的ListOps方程。解决这一缺陷对于现实世界中的文本理解至关重要，这需要识别关键推理点、追踪概念性中间结果并筛选无关信息。Verbose ListOps及其可扩展的生成框架，因此超越了简单的上下文窗口扩展，实现了有针对性的推理能力提升；这是迈向自动化全球知识工作的关键一步。

> Large Language Models (LLMs), whilst great at extracting facts from text, struggle with nested narrative reasoning. Existing long context and multi-hop QA benchmarks inadequately test this, lacking realistic distractors or failing to decouple context length from reasoning complexity, masking a fundamental LLM limitation. We introduce Verbose ListOps, a novel benchmark that programmatically transposes ListOps computations into lengthy, coherent stories. This uniquely forces internal computation and state management of nested reasoning problems by withholding intermediate results, and offers fine-grained controls for both narrative size \emph{and} reasoning difficulty. Whilst benchmarks like LongReason (2025) advance approaches for synthetically expanding the context size of multi-hop QA problems, Verbose ListOps pinpoints a specific LLM vulnerability: difficulty in state management for nested sub-reasoning amongst semantically-relevant, distracting narrative. Our experiments show that leading LLMs (e.g., OpenAI o4, Gemini 2.5 Pro) collapse in performance on Verbose ListOps at modest (~10k token) narrative lengths, despite effortlessly solving raw ListOps equations. Addressing this failure is paramount for real-world text interpretation which requires identifying key reasoning points, tracking conceptual intermediate results, and filtering irrelevant information. Verbose ListOps, and its extensible generation framework thus enables targeted reasoning enhancements beyond mere context-window expansion; a critical step to automating the world's knowledge work.

[Arxiv](https://arxiv.org/abs/2506.04907)