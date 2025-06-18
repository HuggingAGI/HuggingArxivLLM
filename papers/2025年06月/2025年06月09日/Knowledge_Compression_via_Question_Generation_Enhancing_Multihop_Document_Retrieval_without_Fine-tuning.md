# # 通过问题生成压缩知识：无需微调的多跳文档检索提升

发布时间：2025年06月09日

`RAG` `信息检索`

> Knowledge Compression via Question Generation: Enhancing Multihop Document Retrieval without Fine-tuning

# 摘要

> 本研究提出了一种无需微调或传统分块的基于问题的知识编码方法，显著提升了增强检索生成（RAG）系统的性能。通过生成覆盖词汇和语义空间的问题来编码文本内容，并结合自定义句法重排序方法，我们创建了高效的检索线索。在对109篇科学论文进行单跳检索时，我们的方法实现了0.84的Recall@3指标，比传统分块方法高出60%。我们还引入了"论文卡片"——300字符以内的简洁论文摘要，这些摘要显著增强了BM25检索能力，在简化技术查询下将MRR@3从0.56提升至0.85。针对多跳任务，我们的重排序方法在LongBench 2WikiMultihopQA数据集上与LLaMA2-Chat-7B结合使用，实现了0.52的F1分数，超越了分块方法（0.328）和微调基线（0.412）。这种方法不仅无需微调，减少了检索延迟，还支持直观的问题驱动知识访问，并将向量存储需求降低了80%，从而成为一种可扩展且高效的RAG替代方案。

> This study presents a question-based knowledge encoding approach that improves retrieval-augmented generation (RAG) systems without requiring fine-tuning or traditional chunking. We encode textual content using generated questions that span the lexical and semantic space, creating targeted retrieval cues combined with a custom syntactic reranking method.
  In single-hop retrieval over 109 scientific papers, our approach achieves a Recall@3 of 0.84, outperforming traditional chunking methods by 60 percent. We also introduce "paper-cards", concise paper summaries under 300 characters, which enhance BM25 retrieval, increasing MRR@3 from 0.56 to 0.85 on simplified technical queries.
  For multihop tasks, our reranking method reaches an F1 score of 0.52 with LLaMA2-Chat-7B on the LongBench 2WikiMultihopQA dataset, surpassing chunking and fine-tuned baselines which score 0.328 and 0.412 respectively.
  This method eliminates fine-tuning requirements, reduces retrieval latency, enables intuitive question-driven knowledge access, and decreases vector storage demands by 80%, positioning it as a scalable and efficient RAG alternative.

[Arxiv](https://arxiv.org/abs/2506.13778)