# # 代码注释对大型语言模型理解遗留代码的影响
代码注释如何影响大型语言模型理解遗留代码的能力是一个值得深入探讨的课题。研究这一问题，我们可以为提升LLM的代码分析能力提供有价值的见解，特别是在处理复杂代码结构时。

发布时间：2025年04月23日

`LLM应用` `软件工程` `软件维护`

> Impact of Comments on LLM Comprehension of Legacy Code

# 摘要

> 大型语言模型（LLMs）凭借在软件工程任务中的卓越表现和对现代编程语言的深刻理解，正被越来越多地应用于软件工程和维护领域。然而，LLMs 对遗留语言代码的理解能力仍是一个研究空白，这一问题在缺乏或包含不准确文档的现实遗留系统中尤为突出。为了客观评估 LLM 对遗留语言的理解能力，我们需要一个高效且定量的评估方法。我们采用多选题问答（MCQA），一种新兴的 LLM 评估方法，来评估 LLM 对遗留代码的理解以及注释普及程度和不准确注释的影响。本研究介绍了文档对 LLM 理解遗留代码影响的初步发现，并为未来工作制定了战略性目标。

> Large language models (LLMs) have been increasingly integrated into software engineering and maintenance tasks due to their high performance with software engineering tasks and robust understanding of modern programming languages. However, the ability of LLMs to comprehend code written with legacy languages remains a research gap challenged by real-world legacy systems lacking or containing inaccurate documentation that may impact LLM comprehension. To assess LLM comprehension of legacy languages, there is a need for objective LLM evaluation. In order to objectively measure LLM comprehension of legacy languages, we need an efficient, quantitative evaluation method. We leverage multiple-choice question answering (MCQA), an emerging LLM evaluation methodology, to evaluate LLM comprehension of legacy code and the impact of comment prevalence and inaccurate comments. In this work, we present preliminary findings on the impact of documentation on LLM comprehension of legacy code and outline strategic objectives for future work.

[Arxiv](https://arxiv.org/abs/2506.11007)