# SmartNote：基于LLM的个性化的发布说明生成工具，简单有效

发布时间：2025年05月23日

`LLM应用

摘要中详细描述了如何利用大型语言模型（LLMs）来生成高质量的发布说明文档，属于将LLM技术应用于具体的实际任务，因此归类为LLM应用。` `软件工程` `文档生成`

> SmartNote: An LLM-Powered, Personalised Release Note Generator That Just Works

# 摘要

> 发布说明文档是软件新版本变更的重要记录。然而，编写发布说明往往让开发者感到枯燥甚至头疼。因此，研究者和实践者开发了多种工具来自动化生成发布说明。但这些工具普遍存在两大问题：一是未能针对项目领域和目标受众进行个性化调整，导致相关性和简洁性不足；二是适用性有限，通常需要大幅调整工作流程并投入大量精力，给开发者带来负担。

尽管自然语言处理领域取得显著进展，大型语言模型（LLMs）在代码和文本相关任务中表现优异，但目前还没有研究探索将LLMs应用于自动化发布说明生成。为此，我们提出了SmartNote——一种新颖且广泛应用的发布说明生成方法。SmartNote利用LLM技术，通过聚合变更信息并结合代码、提交和拉取请求的详细信息，生成高质量的上下文个性化发布说明。它对提交进行分类和评分，从而生成结构清晰、重点突出的简洁发布说明。

我们的手动和自动评估显示，SmartNote在完整性、清晰度、简洁性和组织性这四个关键指标上，均优于或可与DeepRelease、Conventional Changelog以及项目的原始发布说明相媲美。在两种评估中，SmartNote的完整性和组织性表现最佳，而在人工评估中，其清晰度也排名第一。进一步评估表明，SmartNote在上下文感知和适用性方面同样表现出色。

> The release note is a crucial document outlining changes in new software versions. Yet, many developers view the process of writing software release notes as a tedious and dreadful task. Consequently, numerous tools have been developed by researchers and practitioners to automate the generation of software release notes. However, these tools fail to consider project domain and target audience for personalisation, limiting their relevance and conciseness. Additionally, they suffer from limited applicability, often necessitating significant workflow adjustments and adoption efforts, hindering practical use and stressing developers. Despite recent advancements in natural language processing and the proven capabilities of large language models in various code and text-related tasks, there are no existing studies investigating the integration and utilisation of LLMs in automated release note generation. Therefore, we propose SmartNote, a novel and widely applicable release note generation approach that produces high-quality, contextually personalised release notes using LLM technology. SmartNote aggregates changes and uses an LLM to describe and summarise the changes using code, commit, and pull request details. It categorises and scores commits to generate structured and concise release notes of prioritised changes. Our human and automatic evaluations reveal that SmartNote outperforms or achieves comparable performance to DeepRelease, Conventional Changelog, and the projects'original release notes across four quality metrics: completeness, clarity, conciseness, and organisation. In both evaluations, SmartNote ranked first for completeness and organisation, while clarity ranked first in the human evaluation. A further evaluation demonstrates that SmartNote is effective in terms of context awareness and applicability.

[Arxiv](https://arxiv.org/abs/2505.17977)