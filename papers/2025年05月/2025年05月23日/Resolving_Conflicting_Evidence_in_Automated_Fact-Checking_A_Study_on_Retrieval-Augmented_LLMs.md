# 应对自动事实核查中的矛盾证据：一项关于检索增强型LLM的探讨

发布时间：2025年05月23日

`RAG` `事实核查` `信息检索`

> Resolving Conflicting Evidence in Automated Fact-Checking: A Study on Retrieval-Augmented LLMs

# 摘要

> 配备检索机制的大型语言模型（LLMs）在事实核查任务中通过整合外部知识展现出了巨大潜力。然而，面对来自不同可信度来源的相互矛盾证据时，其可靠性会显著下降。本文首次系统性地评估了在存在相互矛盾证据的情况下，检索增强生成（RAG）模型的事实核查能力。为了支持这项研究，我们推出了	extbf{CONFACT}（	extbf{Con}flicting Evidence for 	extbf{Fact}-Checking）数据集（可在https://github.com/zoeyyes/CONFACT获取），这是一个包含问题与来自各种来源的相互矛盾信息的新颖数据集。通过大量实验，我们发现先进RAG方法在解决因媒体来源可信度差异引发的冲突方面存在关键漏洞。为应对这些挑战，我们在检索和生成阶段探究了整合媒体背景信息的策略。研究结果表明，有效整合来源可信度显著增强了RAG模型在解决相互矛盾证据和提升事实核查性能方面的能力。

> Large Language Models (LLMs) augmented with retrieval mechanisms have demonstrated significant potential in fact-checking tasks by integrating external knowledge. However, their reliability decreases when confronted with conflicting evidence from sources of varying credibility. This paper presents the first systematic evaluation of Retrieval-Augmented Generation (RAG) models for fact-checking in the presence of conflicting evidence. To support this study, we introduce \textbf{CONFACT} (\textbf{Con}flicting Evidence for \textbf{Fact}-Checking) (Dataset available at https://github.com/zoeyyes/CONFACT), a novel dataset comprising questions paired with conflicting information from various sources. Extensive experiments reveal critical vulnerabilities in state-of-the-art RAG methods, particularly in resolving conflicts stemming from differences in media source credibility. To address these challenges, we investigate strategies to integrate media background information into both the retrieval and generation stages. Our results show that effectively incorporating source credibility significantly enhances the ability of RAG models to resolve conflicting evidence and improve fact-checking performance.

[Arxiv](https://arxiv.org/abs/2505.17762)