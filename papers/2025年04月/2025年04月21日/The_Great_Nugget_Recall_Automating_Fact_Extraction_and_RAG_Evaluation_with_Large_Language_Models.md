# # 金块召回计划：用大型语言模型实现自动事实抽取与RAG评估

发布时间：2025年04月21日

`RAG` `信息检索`

> The Great Nugget Recall: Automating Fact Extraction and RAG Evaluation with Large Language Models

# 摘要

> 大语言模型（LLMs）极大提升了信息检索生成系统（RAG）的能力。然而，RAG系统的评估仍然是持续进步的关键障碍。在本研究中，我们提出了一个经过人工标注验证的自动评估框架，以应对这一挑战。我们认为，原子事实评估法为评估RAG系统提供了坚实的基础。这一方法最初于2003年为TREC问答（QA）赛道开发，通过评估优秀答案中应包含的基本事实来衡量系统性能。我们的工作重点在于"重构"这一方法，具体表现为AutoNuggetizer框架，该框架专门利用大语言模型自动创建原子事实（nuggets）并将其自动分配到系统答案中。在TREC 2024 RAG赛道的背景下，我们将完全自动化的评估方法与人工或半人工创建原子事实并手动分配给系统答案的策略进行了对比。基于大规模社区评估的结果，我们发现完全自动化的原子事实评估得分与基于人工评估的变体在运行级别上具有高度一致性。当独立自动化原子事实分配等框架组件时，一致性更强。这表明我们的评估框架在努力与质量之间提供了权衡，可用于指导未来RAG系统的发展。然而，仍需进一步研究以完善我们的方法，特别是在建立稳健的主题级别一致性以有效诊断系统故障方面。

> Large Language Models (LLMs) have significantly enhanced the capabilities of information access systems, especially with retrieval-augmented generation (RAG). Nevertheless, the evaluation of RAG systems remains a barrier to continued progress, a challenge we tackle in this work by proposing an automatic evaluation framework that is validated against human annotations. We believe that the nugget evaluation methodology provides a solid foundation for evaluating RAG systems. This approach, originally developed for the TREC Question Answering (QA) Track in 2003, evaluates systems based on atomic facts that should be present in good answers. Our efforts focus on "refactoring" this methodology, where we describe the AutoNuggetizer framework that specifically applies LLMs to both automatically create nuggets and automatically assign nuggets to system answers. In the context of the TREC 2024 RAG Track, we calibrate a fully automatic approach against strategies where nuggets are created manually or semi-manually by human assessors and then assigned manually to system answers. Based on results from a community-wide evaluation, we observe strong agreement at the run level between scores derived from fully automatic nugget evaluation and human-based variants. The agreement is stronger when individual framework components such as nugget assignment are automated independently. This suggests that our evaluation framework provides tradeoffs between effort and quality that can be used to guide the development of future RAG systems. However, further research is necessary to refine our approach, particularly in establishing robust per-topic agreement to diagnose system failures effectively.

[Arxiv](https://arxiv.org/abs/2504.15068)