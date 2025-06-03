# 模式：通用信息抽取的参数化工具

发布时间：2025年06月01日

`LLM应用` `信息抽取` `文本处理`

> Schema as Parameterized Tools for Universal Information Extraction

# 摘要

> 通用信息抽取（UIE）主要基于大型语言模型采用抽取式生成方法，通常以预定义模式（如JSON或表格）输出结构化信息。然而，面对大量模式选择时，UIE在基于上下文学习范式中的适应性不足。本文提出了一种名为Schema as Parameterized Tools（SPT）的统一自适应文本到结构生成框架。该框架创新性地将预定义模式视为参数化工具，用于工具选择和参数填充，重新定义了大型语言模型的工具调用能力。具体而言，SPT通过模式检索、模式填充或模式生成三种方式，统一处理闭合、开放和按需信息抽取任务。实验结果表明，SPT能够自适应地处理四种不同信息抽取任务，展现出卓越的模式检索与选择性能。与LoRA基线和现有领先UIE系统相比，SPT在提取性能上达到可比水平，同时 trainable parameters 数量大幅减少。

> Universal information extraction (UIE) primarily employs an extractive generation approach with large language models (LLMs), typically outputting structured information based on predefined schemas such as JSON or tables. UIE suffers from a lack of adaptability when selecting between predefined schemas and on-the-fly schema generation within the in-context learning paradigm, especially when there are numerous schemas to choose from. In this paper, we propose a unified adaptive text-to-structure generation framework, called Schema as Parameterized Tools (SPT), which reimagines the tool-calling capability of LLMs by treating predefined schemas as parameterized tools for tool selection and parameter filling. Specifically, our SPT method can be applied to unify closed, open, and on-demand IE tasks by adopting Schema Retrieval by fetching the relevant schemas from a predefined pool, Schema Filling by extracting information and filling slots as with tool parameters, or Schema Generation by synthesizing new schemas with uncovered cases. Experiments show that the SPT method can handle four distinct IE tasks adaptively, delivering robust schema retrieval and selection performance. SPT also achieves comparable extraction performance to LoRA baselines and current leading UIE systems with significantly fewer trainable parameters.

[Arxiv](https://arxiv.org/abs/2506.01276)