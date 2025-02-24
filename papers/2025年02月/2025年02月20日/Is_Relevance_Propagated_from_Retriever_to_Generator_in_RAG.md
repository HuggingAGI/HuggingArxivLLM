# # RAG中相关性是否从检索器传递到生成器？
在RAG模型中，相关性是否能够从检索器传递到生成器？

发布时间：2025年02月20日

`RAG` `信息检索`

> Is Relevance Propagated from Retriever to Generator in RAG?

# 摘要

> 检索增强生成（RAG）是一种将外部知识（通常以文档集合形式）整合到大型语言模型（LLM）提示中的框架，旨在提升下游任务（如问答）的性能。与标准检索任务专注于最大化文档相关性不同，RAG系统的目标是最大化文档的总效用，即这些文档作为LLM上下文信息是否能改善下游任务。现有研究主要关注RAG上下文在知识密集型语言任务（KILT）中的相关性，这种相关性通常体现为答案包含。然而，在我们的工作中，相关性对应于信息检索任务中查询与文档的主题重叠。我们通过信息检索测试集合实证研究发现：由主题相关文档组成的RAG上下文能带来更好的下游性能。实验结果表明：(a) 相关性与效用呈微弱正相关；(b) 随着上下文规模增加（k-shot中k值更高），相关性减弱；(c) 更有效的检索模型通常能带来更好的RAG性能。

> Retrieval Augmented Generation (RAG) is a framework for incorporating external knowledge, usually in the form of a set of documents retrieved from a collection, as a part of a prompt to a large language model (LLM) to potentially improve the performance of a downstream task, such as question answering. Different from a standard retrieval task's objective of maximising the relevance of a set of top-ranked documents, a RAG system's objective is rather to maximise their total utility, where the utility of a document indicates whether including it as a part of the additional contextual information in an LLM prompt improves a downstream task. Existing studies investigate the role of the relevance of a RAG context for knowledge-intensive language tasks (KILT), where relevance essentially takes the form of answer containment. In contrast, in our work, relevance corresponds to that of topical overlap between a query and a document for an information seeking task. Specifically, we make use of an IR test collection to empirically investigate whether a RAG context comprised of topically relevant documents leads to improved downstream performance. Our experiments lead to the following findings: (a) there is a small positive correlation between relevance and utility; (b) this correlation decreases with increasing context sizes (higher values of k in k-shot); and (c) a more effective retrieval model generally leads to better downstream RAG performance.

[Arxiv](https://arxiv.org/abs/2502.15025)