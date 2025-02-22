# LLMs 是否提供与生成代码相似的链接？基于 Gemini 和 Bing CoPilot 的研究

发布时间：2025年01月21日

`LLM应用

**解释**：这篇论文主要研究了大型语言模型（LLMs）在软件开发任务中的应用，特别是代码生成和来源信息的问题。论文通过实证研究评估了基于LLM的助手（如Bing CoPilot和Google Gemini）生成的代码片段与提供的链接的相关性。这属于LLM在实际应用中的表现和问题，因此分类为LLM应用。` `软件开发` `代码生成`

> Do LLMs Provide Links to Code Similar to what they Generate? A Study with Gemini and Bing CoPilot

# 摘要

> 大型语言模型（LLMs）正被广泛应用于软件开发任务，例如生成代码片段以解决特定问题。然而，与从网络复用代码不同，LLMs在提供代码来源信息方面存在局限，这可能对可信度和法律后果产生重大影响。尽管基于LLM的助手会提供与生成代码“相关”的外部链接，但这些链接的相关性尚不明确。本文通过实证研究，评估了Bing CoPilot和Google Gemini生成的243和194个代码片段（涵盖六种编程语言）在多大程度上源自这些助手提供的链接。研究结合了自动化代码相似性评估与详尽的手动分析，结果表明，基于LLM的助手提供的链接既有相关也有不相关的，且性质各异。具体而言，Bing CoPilot的66%链接和Google Gemini的28%链接是相关的，但基于LLM的助手仍面临严重的“来源债务”问题。

> Large Language Models (LLMs) are currently used for various software development tasks, including generating code snippets to solve specific problems. Unlike reuse from the Web, LLMs are limited in providing provenance information about the generated code, which may have important trustworthiness and legal consequences. While LLM-based assistants may provide external links that are "related" to the generated code, we do not know how relevant such links are. This paper presents the findings of an empirical study assessing the extent to which 243 and 194 code snippets, across six programming languages, generated by Bing CoPilot and Google Gemini, likely originate from the links provided by these two LLM-based assistants. The study leverages automated code similarity assessments with thorough manual analysis. The study's findings indicate that the LLM-based assistants provide a mix of relevant and irrelevant links having a different nature. Specifically, although 66% of the links from Bing CoPilot and 28% from Google Gemini are relevant, LLMs-based assistants still suffer from serious "provenance debt".

[Arxiv](https://arxiv.org/abs/2501.12134)