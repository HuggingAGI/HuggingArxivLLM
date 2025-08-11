# PAIRS: 通过参数化验证的自适应信息检索与选择实现高效 RAG

发布时间：2025年08月05日

`RAG` `问答系统` `信息检索`

> PAIRS: Parametric-Verified Adaptive Information Retrieval and Selection for Efficient RAG

# 摘要

> 检索增强生成（RAG）已成为提升大型语言模型（LLMs）外部知识应用的核心技术。然而，现有的RAG系统面临两大关键挑战：（1）对于那些仅凭LLM的参数化知识即可解决的简单问题，系统仍然低效地为每个查询检索信息；（2）当查询包含稀疏信息信号时，系统存在检索到无关文档的风险。为了解决这些问题，我们引入了参数化验证的自适应信息检索与选择框架（PAIRS），这是一个无需训练的框架，能够整合参数化知识与检索知识，自适应地决定是否进行检索以及如何选择外部信息。

具体而言，PAIRS采用了双路径生成机制：首先，LLM会同时生成直接答案和基于自动生成的伪上下文的增强答案。当这些输出结果一致时，PAIRS完全跳过外部检索，显著提升了RAG系统的效率。对于结果不一致的情况，PAIRS会启动双路径检索（DPR）流程，该流程由原始查询和自动生成的上下文信号共同引导，并通过自适应信息选择（AIS）模块，基于对两者的加权相似度进行文档筛选。这一简单而有效的方案不仅能通过消除不必要的检索提升效率，还能通过上下文引导的检索和自适应信息选择提高准确性。

在六个问答（QA）基准测试中的实验结果表明，PAIRS将检索成本降低了约25%（仅对75%的查询触发检索），同时仍提高了准确性——相比先前的基线模型，平均精确匹配（EM）提升了+1.1%，平均F1值提升了+1.0%。

> Retrieval-Augmented Generation (RAG) has become a cornerstone technique for enhancing large language models (LLMs) with external knowledge. However, current RAG systems face two critical limitations: (1) they inefficiently retrieve information for every query, including simple questions that could be resolved using the LLM's parametric knowledge alone, and (2) they risk retrieving irrelevant documents when queries contain sparse information signals. To address these gaps, we introduce Parametric-verified Adaptive Information Retrieval and Selection (PAIRS), a training-free framework that integrates parametric and retrieved knowledge to adaptively determine whether to retrieve and how to select external information. Specifically, PAIRS employs a dual-path generation mechanism: First, the LLM produces both a direct answer and a context-augmented answer using self-generated pseudo-context. When these outputs converge, PAIRS bypasses external retrieval entirely, dramatically improving the RAG system's efficiency. For divergent cases, PAIRS activates a dual-path retrieval (DPR) process guided by both the original query and self-generated contextual signals, followed by an Adaptive Information Selection (AIS) module that filters documents through weighted similarity to both sources. This simple yet effective approach can not only enhance efficiency by eliminating unnecessary retrievals but also improve accuracy through contextually guided retrieval and adaptive information selection. Experimental results on six question-answering (QA) benchmarks show that PAIRS reduces retrieval costs by around 25% (triggering for only 75% of queries) while still improving accuracy-achieving +1.1% EM and +1.0% F1 over prior baselines on average.

[Arxiv](https://arxiv.org/abs/2508.04057)