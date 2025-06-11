# 长上下文问答中的高效上下文选择：无需调参，无需迭代，只需自适应-$k$

发布时间：2025年06月10日

`RAG

这篇论文专注于改进检索增强生成（RAG）方法，提出了一种自适应检索策略，用于优化问答任务中的上下文规模，因此属于RAG类别。` `问答系统` `信息检索`

> Efficient Context Selection for Long-Context QA: No Tuning, No Iteration, Just Adaptive-$k$

# 摘要

> 检索增强生成（RAG）和长上下文语言模型（LCLMs）为解决大型语言模型（LLMs）在开放领域问答（QA）中的上下文限制问题提供了有效途径。然而，如何确定最优的外部上下文检索规模仍是一个待解决的难题：固定检索规模可能带来浪费token或遗漏关键证据的风险。现有的自适应方法，如Self-RAG和Self-Route，通过迭代式LLM提示在事实性问答上表现优异，但在聚合性问答上却面临挑战，因为最优上下文规模既未知又可变。我们提出了一种名为Adaptive-$k$检索的简单而有效的方法，它能够在单次通过中，根据查询与候选段落之间相似度分数的分布，自适应地选择段落数量。该方法无需模型微调、额外的LLM推理或修改现有的检索器-阅读器管道。在事实性和聚合性问答基准测试中，Adaptive-$k$检索不仅能够匹配甚至超越固定$k$基线的表现，同时仅使用全上下文输入10分之一的token，却仍能检索到70%的相关段落。实验表明，Adaptive-$k$检索在五个长上下文语言模型和两个嵌入模型上均提高了问答准确性，证明动态调整上下文规模能够显著提升问答任务的效率和准确性。

> Retrieval-augmented generation (RAG) and long-context language models (LCLMs) both address context limitations of LLMs in open-domain question answering (QA). However, optimal external context to retrieve remains an open problem: fixing the retrieval size risks either wasting tokens or omitting key evidence. Existing adaptive methods like Self-RAG and Self-Route rely on iterative LLM prompting and perform well on factoid QA, but struggle with aggregation QA, where the optimal context size is both unknown and variable. We present Adaptive-$k$ retrieval, a simple and effective single-pass method that adaptively selects the number of passages based on the distribution of the similarity scores between the query and the candidate passages. It does not require model fine-tuning, extra LLM inferences or changes to existing retriever-reader pipelines. On both factoid and aggregation QA benchmarks, Adaptive-$k$ matches or outperforms fixed-$k$ baselines while using up to 10x fewer tokens than full-context input, yet still retrieves 70% of relevant passages. It improves accuracy across five LCLMs and two embedding models, highlighting that dynamically adjusting context size leads to more efficient and accurate QA.

[Arxiv](https://arxiv.org/abs/2506.08479)