# LLM辅助的Web应用功能需求生成：以四个流行LLM在食堂管理系统中的应用为案例

发布时间：2025年05月23日

`LLM应用

理由：这篇论文探讨了大型语言模型在软件工程中的具体应用，特别是评估它们在生成功能规范方面的能力。它属于应用层面的研究，因此归类为LLM应用。` `软件工程` `软件开发`

> LLM assisted web application functional requirements generation: A case study of four popular LLMs over a Mess Management System

# 摘要

> 大型语言模型（LLMs）在软件工程领域发挥着重要作用，帮助开发者在软件开发的各个阶段生成所需工件。本文通过案例研究，对比了GPT、Claude、Gemini和DeepSeek四款流行LLM在为Web应用程序（Mess Management System）生成功能规范的表现。这些功能规范涵盖用例、业务规则和协作工作流。研究从句法和语义正确性、一致性、非歧义性和完整性等方面，对比了LLM生成的规范与参考规范的差异。结果显示，四款LLM均能生成句法语义正确且非歧义性较高的工件，但完整性存在一定差异。Claude和Gemini成功生成所有参考用例，其中Claude的用例规范最为完整但略显冗余。工作流规范方面亦有相似表现。然而，四款LLM在业务规则生成上均面临挑战，DeepSeek虽生成最多参考规则，但完整性不足。总体而言，Claude生成的规范工件更完整，而Gemini的规范则更为精确。

> Like any other discipline, Large Language Models (LLMs) have significantly impacted software engineering by helping developers generate the required artifacts across various phases of software development. This paper presents a case study comparing the performance of popular LLMs GPT, Claude, Gemini, and DeepSeek in generating functional specifications that include use cases, business rules, and collaborative workflows for a web application, the Mess Management System. The study evaluated the quality of LLM generated use cases, business rules, and collaborative workflows in terms of their syntactic and semantic correctness, consistency, non ambiguity, and completeness compared to the reference specifications against the zero-shot prompted problem statement. Our results suggested that all four LLMs can specify syntactically and semantically correct, mostly non-ambiguous artifacts. Still, they may be inconsistent at times and may differ significantly in the completeness of the generated specification. Claude and Gemini generated all the reference use cases, with Claude achieving the most complete but somewhat redundant use case specifications. Similar results were obtained for specifying workflows. However, all four LLMs struggled to generate relevant Business Rules, with DeepSeek generating the most reference rules but with less completeness. Overall, Claude generated more complete specification artifacts, while Gemini was more precise in the specifications it generated.

[Arxiv](https://arxiv.org/abs/2505.18019)