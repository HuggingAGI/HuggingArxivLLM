# LLMs引导的代码生成：复杂代码任务的多智能体框架

发布时间：2025年01月11日

`Agent

理由：这篇论文提出了一种“引导式代码生成”智能体框架，旨在通过结构化的方法提升大型语言模型（LLMs）在代码生成任务中的表现。该框架通过智能体的方式引导LLMs进行代码生成，弥补其在长序列推理和上下文理解上的不足。因此，这篇论文的核心内容涉及智能体的设计和应用，属于Agent分类。` `软件开发` `代码生成`

> Guided Code Generation with LLMs: A Multi-Agent Framework for Complex Code Tasks

# 摘要

> # 摘要
大型语言模型（LLMs）在代码生成任务中表现出色，但在处理复杂、长上下文的编程挑战和展示复杂组合推理能力方面仍有明显不足。本文提出了一种创新的“引导式代码生成”智能体框架，通过精细化的方法应对这些挑战。该框架充分发挥LLMs在模糊搜索和近似信息检索上的优势，同时弥补其在长序列推理和长上下文理解上的短板。基于OpenAI的HumanEval基准和Meta的Llama 3.1 8B模型（int4精度）的实验结果显示，与直接的一次性生成相比，解决方案的准确性提升了23.79%。研究表明，结构化的引导式代码生成方法能显著提升LLMs在软件开发中的实用性，并有效克服其在组合推理和上下文处理上的固有局限。

> Large Language Models (LLMs) have shown remarkable capabilities in code generation tasks, yet they face significant limitations in handling complex, long-context programming challenges and demonstrating complex compositional reasoning abilities. This paper introduces a novel agentic framework for ``guided code generation'' that tries to address these limitations through a deliberately structured, fine-grained approach to code generation tasks. Our framework leverages LLMs' strengths as fuzzy searchers and approximate information retrievers while mitigating their weaknesses in long sequential reasoning and long-context understanding. Empirical evaluation using OpenAI's HumanEval benchmark with Meta's Llama 3.1 8B model (int4 precision) demonstrates a 23.79\% improvement in solution accuracy compared to direct one-shot generation. Our results indicate that structured, guided approaches to code generation can significantly enhance the practical utility of LLMs in software development while overcoming their inherent limitations in compositional reasoning and context handling.

[Arxiv](https://arxiv.org/abs/2501.06625)