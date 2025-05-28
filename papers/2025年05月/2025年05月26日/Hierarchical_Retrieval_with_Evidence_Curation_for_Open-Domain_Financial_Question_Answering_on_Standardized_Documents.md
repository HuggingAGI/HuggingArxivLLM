# 层次化检索与证据整理：应用于标准化文档的开放域金融问答

发布时间：2025年05月26日

`RAG` `问答系统`

> Hierarchical Retrieval with Evidence Curation for Open-Domain Financial Question Answering on Standardized Documents

# 摘要

> 基于RAG的LLMs在金融领域的知识密集型任务中表现优异，但标准化文件（如SEC申报文件）通常具有相似的格式，包含重复的模板文本和表格结构。这种相似性导致传统RAG方法难以区分近重复文本，引发重复检索，损害准确性和完整性。为此，我们提出了分层检索结合证据整理（HiREC）框架。我们的方法通过分层检索减少相似文本间的混淆，首先检索相关文档，然后从中提取最相关的段落。证据整理过程剔除不相关的段落，并在必要时自动生成补充查询以收集缺失信息。为了验证我们的方法，我们构建并发布了一个大规模开放领域金融（LOFin）问答基准数据集，包含145,897份SEC文件和1,595个问答对。我们的代码和数据可在https://github.com/deep-over/LOFin-bench-HiREC获取。

> Retrieval-augmented generation (RAG) based large language models (LLMs) are widely used in finance for their excellent performance on knowledge-intensive tasks. However, standardized documents (e.g., SEC filing) share similar formats such as repetitive boilerplate texts, and similar table structures. This similarity forces traditional RAG methods to misidentify near-duplicate text, leading to duplicate retrieval that undermines accuracy and completeness. To address these issues, we propose the Hierarchical Retrieval with Evidence Curation (HiREC) framework. Our approach first performs hierarchical retrieval to reduce confusion among similar texts. It first retrieve related documents and then selects the most relevant passages from the documents. The evidence curation process removes irrelevant passages. When necessary, it automatically generates complementary queries to collect missing information. To evaluate our approach, we construct and release a Large-scale Open-domain Financial (LOFin) question answering benchmark that includes 145,897 SEC documents and 1,595 question-answer pairs. Our code and data are available at https://github.com/deep-over/LOFin-bench-HiREC.

[Arxiv](https://arxiv.org/abs/2505.20368)