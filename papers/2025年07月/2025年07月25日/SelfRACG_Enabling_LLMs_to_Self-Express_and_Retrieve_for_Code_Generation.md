# SelfRACG：让 LLMs 实现自我表达与检索，助力代码生成

发布时间：2025年07月25日

`RAG` `软件工程` `人工智能`

> SelfRACG: Enabling LLMs to Self-Express and Retrieve for Code Generation

# 摘要

> 现有的检索增强的代码生成（RACG）方法通常借助外部检索模块获取语义相似的代码片段，用于生成后续代码。然而，即使是连续的代码片段，内容也常因逻辑推进而产生差异，导致内容断层。这种断层使得基于内容匹配的 	extit{外部} 检索模块无法准确捕捉 LLMs 生成下一个代码片段所需的信息，从而影响 RACG 的性能。因此，我们提出了 	extbf{SelfRACG}，一种全新的范式，使大型语言模型（LLMs）能够 	extbf{自我} 表达其信息需求，从而提升 	extbf{RACG} 的效果。具体而言，SelfRACG 包含一个信息需求表达模块和一个两阶段的信息需求引导训练策略，旨在鼓励 LLMs 主动表达其信息需求。通过大量实验，我们发现 SelfRACG 能够检索到与 LLMs 自身信息需求更匹配的外部知识，从而在生成性能上显著优于传统的 RACG 方法。

> Existing retrieval-augmented code generation (RACG) methods typically use an external retrieval module to fetch semantically similar code snippets used for generating subsequent fragments. However, even for consecutive code fragments, the content often diverges due to logical progression, resulting in a content gap. This gap undermines the performance of current RACG methods, as \textit{external} retrieval modules based on content matching fail to infer the specific information need of LLMs to generate the next code fragment. Therefore, we propose \textbf{SelfRACG}, a novel paradigm that enables large language models (LLMs) to \textbf{Self}-express their information needs to enhance \textbf{RACG}. Specifically, SelfRACG includes an information need expression module and a two-stage information need-guided training strategy, which encourages LLMs to express their information need. Extensive experiments demonstrate that SelfRACG can retrieve external knowledge that better aligns with the LLM's own information needs, resulting in superior generation performance compared to vanilla RACG.

[Arxiv](https://arxiv.org/abs/2507.19033)