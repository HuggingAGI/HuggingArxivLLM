# 跨越链条：连接大型语言模型与知识库，实现复杂问答的突破

发布时间：2025年05月20日

`RAG` `知识图谱` `问答系统`

> Beyond Chains: Bridging Large Language Models and Knowledge Bases in Complex Question Answering

# 摘要

> 知识图谱问答（KBQA）旨在利用知识图谱中的结构化知识回答自然语言问题。仅依赖LLM的方法虽然具有良好的泛化能力，但存在知识过时、幻觉以及缺乏透明性等问题。基于知识图谱的链式RAG方法通过引入外部知识库解决了这些问题，但受限于缺乏规划和逻辑结构化，仅适用于简单的链式结构问题。受语义解析方法启发，我们提出了PDRR：一个包含预测、分解、检索和推理四个阶段的框架。我们的方法首先预测问题类型并将问题分解为结构化的三元组，然后从知识库中检索相关信息，并将LLM作为代理引导其推理并完成分解后的三元组。实验结果表明，PDRR在各种LLM模型上均优于现有方法，并在链式结构和非链式复杂问题上均取得了更优性能。


> Knowledge Base Question Answering (KBQA) aims to answer natural language questions using structured knowledge from KBs. While LLM-only approaches offer generalization, they suffer from outdated knowledge, hallucinations, and lack of transparency. Chain-based KG-RAG methods address these issues by incorporating external KBs, but are limited to simple chain-structured questions due to the absence of planning and logical structuring. Inspired by semantic parsing methods, we propose PDRR: a four-stage framework consisting of Predict, Decompose, Retrieve, and Reason. Our method first predicts the question type and decomposes the question into structured triples. Then retrieves relevant information from KBs and guides the LLM as an agent to reason over and complete the decomposed triples. Experimental results demonstrate that PDRR consistently outperforms existing methods across various LLM backbones and achieves superior performance on both chain-structured and non-chain complex questions.

[Arxiv](https://arxiv.org/abs/2505.14099)