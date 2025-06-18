# InsertRank：大语言模型基于 BM25 评分提升列表重排序能力。

发布时间：2025年06月16日

`LLM应用` `信息检索`

> InsertRank: LLMs can reason over BM25 scores to Improve Listwise Reranking

# 摘要

> 大型语言模型（LLMs）在信息检索领域取得了长足进步，尤其在重排序任务中表现突出，这得益于其强大的泛化和知识迁移能力。与此同时，基于LLMs的聊天界面提升了用户期望，促使用户提出更复杂的查询，这些查询需要通过文档推理而非简单的关键词匹配或语义相似性来实现检索。尽管一些研究尝试利用LLMs的推理能力对这类查询进行重排序，但仍有较大的改进空间。在此背景下，我们提出了InsertRank——一种基于LLMs的重排序器，它在重排序过程中利用BM25得分等词汇信号，进一步提升检索性能。InsertRank在涵盖12个不同领域的推理基准测试BRIGHT，以及涵盖8种不同任务的医学推理检索基准测试R2MED上均展现了更优的检索效果。我们进行了全面的评估和多项消融实验，结果表明InsertRank在包括GPT、Gemini和Deepseek等多个LLMs家族中均能显著提升检索效果。InsertRank在Deepseek-R1模型下，于BRIGHT基准测试中取得37.5分，R2MED基准测试中取得51.1分，超越了此前的方法。

> Large Language Models (LLMs) have demonstrated significant strides across various information retrieval tasks, particularly as rerankers, owing to their strong generalization and knowledge-transfer capabilities acquired from extensive pretraining. In parallel, the rise of LLM-based chat interfaces has raised user expectations, encouraging users to pose more complex queries that necessitate retrieval by ``reasoning'' over documents rather than through simple keyword matching or semantic similarity. While some recent efforts have exploited reasoning abilities of LLMs for reranking such queries, considerable potential for improvement remains. In that regards, we introduce InsertRank, an LLM-based reranker that leverages lexical signals like BM25 scores during reranking to further improve retrieval performance. InsertRank demonstrates improved retrieval effectiveness on -- BRIGHT, a reasoning benchmark spanning 12 diverse domains, and R2MED, a specialized medical reasoning retrieval benchmark spanning 8 different tasks. We conduct an exhaustive evaluation and several ablation studies and demonstrate that InsertRank consistently improves retrieval effectiveness across multiple families of LLMs, including GPT, Gemini, and Deepseek models. %In addition, we also conduct ablation studies on normalization by varying the scale of the BM25 scores, and positional bias by shuffling the order of the documents. With Deepseek-R1, InsertRank achieves a score of 37.5 on the BRIGHT benchmark. and 51.1 on the R2MED benchmark, surpassing previous methods.

[Arxiv](https://arxiv.org/abs/2506.14086)