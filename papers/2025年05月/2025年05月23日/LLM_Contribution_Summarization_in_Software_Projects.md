# # LLM 在软件项目中的贡献探索

发布时间：2025年05月23日

`LLM应用

理由：这篇论文展示了大型语言模型（LLM）在教育领域中的具体应用，特别是在自动评估学生在团队项目中的代码贡献方面。它详细描述了工具的设计、实现和评估，属于LLM的实际应用案例。` `软件开发`

> LLM Contribution Summarization in Software Projects

# 摘要

> # 摘要
本篇创新实践论文介绍了一款自动化工具，用于总结基于项目课程中个体的代码贡献，这些课程涉及外部客户。真实的行业项目通过将学生沉浸于外部客户定义的真实问题中，提供了宝贵的学习机会。然而，这些项目的开放性和高度可变性使得教师和助教难以及时提供详细反馈。本文旨在解决在团队项目中自动、客观评估个体贡献的需求。

在本文中，我们介绍了一款工具，该工具利用大型语言模型（LLM）自动总结从版本控制仓库中提取的代码贡献。该工具预处理并结构化仓库数据，并使用PyDriller来分离个体贡献。其独特之处在于将LLM提示工程与自动化的仓库分析相结合，从而在提供定期、信息丰富的更新的同时，减轻手动评分的负担。

该工具在两个学期中被评估，涉及一个为期三周的全日制软件开发冲刺项目，共有65名学生参与。每周为团队提供总结，学生和教师的反馈均表明该工具在评分和指导方面具有整体实用性。该工具报告的活动在很大程度上反映了学生实际执行的操作，但在检测学生贡献方面存在一些遗漏。这些总结被教师视为有用工具，有助于跟上项目进展。

> This full paper in innovative practice provides an automated tool to summarize individual code contributions in project-based courses with external clients. Real industry projects offer valuable learning opportunities by immersing students in authentic problems defined by external clients. However, the open-ended and highly variable scope of these projects makes it challenging for instructors and teaching assistants to provide timely and detailed feedback. This paper addresses the need for an automated and objective approach to evaluate individual contributions within team projects. In this paper, we present a tool that leverages a large language model (LLM) to automatically summarize code contributions extracted from version control repositories. The tool preprocesses and structures repository data, and uses PyDriller to isolate individual contributions. Its uniqueness lies in the combination of LLM prompt engineering with automated repository analysis, thus reducing the manual grading burden while providing regular and informative updates. The tool was assessed over two semesters during a three-week, full-time software development sprint involving 65 students. Weekly summaries were provided to teams, and both student and faculty feedback indicated the tool's overall usefulness in informing grading and guidance. The tool reports, in large proportion, activities that were in fact performed by the student, with some failure to detect students' contribution. The summaries were considered by the instructors as a useful potential tool to keep up with the projects.

[Arxiv](https://arxiv.org/abs/2505.17710)