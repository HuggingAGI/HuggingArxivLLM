# RGAR：基于生成式增强的检索，用于事实感知的医疗问答系统

发布时间：2025年02月18日

`RAG` `问答系统`

> RGAR: Recurrence Generation-augmented Retrieval for Factual-aware Medical Question Answering

# 摘要

> 医疗问答系统需要广泛获取专业的概念知识。目前主流的检索增强生成（RAG）方法通过大规模语料库检索获取专业知识，并利用这些知识指导通用大型语言模型（LLM）生成答案。然而，现有检索方法常常忽视事实知识的重要性，这限制了检索到的概念知识的相关性，也限制了其在实际场景中的应用，例如基于电子健康记录（EHRs）的临床决策。本文提出了一种名为RGAR的循环生成增强检索框架，能够从双源数据（即EHRs和语料库）中检索出相关事实和概念知识，并让它们相互作用、相互优化。通过在三个事实感知的医疗问答基准测试中的广泛评估，RGAR在医疗RAG系统中确立了新的最先进性能。值得注意的是，采用RGAR框架的Llama-3.1-8B-Instruct模型在性能上超越了规模更大且经过RAG增强的GPT-3.5模型。我们的研究结果表明，提取事实知识用于检索能够显著提升生成质量，这一优势在多个实验中得到了一致验证。

> Medical question answering requires extensive access to specialized conceptual knowledge. The current paradigm, Retrieval-Augmented Generation (RAG), acquires expertise medical knowledge through large-scale corpus retrieval and uses this knowledge to guide a general-purpose large language model (LLM) for generating answers. However, existing retrieval approaches often overlook the importance of factual knowledge, which limits the relevance of retrieved conceptual knowledge and restricts its applicability in real-world scenarios, such as clinical decision-making based on Electronic Health Records (EHRs). This paper introduces RGAR, a recurrence generation-augmented retrieval framework that retrieves both relevant factual and conceptual knowledge from dual sources (i.e., EHRs and the corpus), allowing them to interact and refine each another. Through extensive evaluation across three factual-aware medical question answering benchmarks, RGAR establishes a new state-of-the-art performance among medical RAG systems. Notably, the Llama-3.1-8B-Instruct model with RGAR surpasses the considerably larger, RAG-enhanced GPT-3.5. Our findings demonstrate the benefit of extracting factual knowledge for retrieval, which consistently yields improved generation quality.

[Arxiv](https://arxiv.org/abs/2502.13361)