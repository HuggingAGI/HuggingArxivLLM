# QBD-RankedDataGen：生成定制排序数据集，提升文档检索搜索效果，通过LLM重排序技术降低人工投入。

发布时间：2025年05月07日

`LLM应用`

> QBD-RankedDataGen: Generating Custom Ranked Datasets for Improving Query-By-Document Search Using LLM-Reranking with Reduced Human Effort

# 摘要

> ## 查询式文档检索（QBD）问题

查询式文档检索（Query-By-Document, QBD）问题是一种信息检索问题，其中查询本身是一份文档，检索出的候选文档与查询文档相匹配，通常在特定领域或特定查询方式下进行。这一问题在专利匹配、法律或合规案例检索以及学术文献综述等方面具有重要意义。

现有的检索方法，包括基于关键词的搜索和文档嵌入技术，可以通过优化特定领域的数据集来提升QBD搜索性能。然而，创建这些特定领域的数据集往往成本高昂且耗时。

我们的研究提出了一种生成定制化QBD搜索数据集的流程，并对比了一系列适用于此问题的方法，我们将其命名为QBD-RankedDatagen。我们从成本、速度以及与领域专家的人机交互界面三个方面，对所提出的方法进行了比较分析。

我们比较的方法利用了大型语言模型（LLMs），这些模型能够整合领域专家的输入，生成文档评分和排名，同时提供供人工审核的解释说明。我们提出的流程和方法可以显著减少在定制化领域创建数据集所需的人力投入，同时仍能获取足够的专业知识以优化检索模型。

我们在文本检索会议（TREC）的QBD数据集上评估了我们的方法，并使用生成的数据对BM25模型的参数进行了微调，该模型被广泛应用于如OpenSearch等工业级搜索引擎中。


> The Query-By-Document (QBD) problem is an information retrieval problem where the query is a document, and the retrieved candidates are documents that match the query document, often in a domain or query specific manner. This can be crucial for tasks such as patent matching, legal or compliance case retrieval, and academic literature review. Existing retrieval methods, including keyword search and document embeddings, can be optimized with domain-specific datasets to improve QBD search performance. However, creating these domain-specific datasets is often costly and time-consuming. Our work introduces a process to generate custom QBD-search datasets and compares a set of methods to use in this problem, which we refer to as QBD-RankedDatagen. We provide a comparative analysis of our proposed methods in terms of cost, speed, and the human interface with the domain experts. The methods we compare leverage Large Language Models (LLMs) which can incorporate domain expert input to produce document scores and rankings, as well as explanations for human review. The process and methods for it that we present can significantly reduce human effort in dataset creation for custom domains while still obtaining sufficient expert knowledge for tuning retrieval models. We evaluate our methods on QBD datasets from the Text Retrieval Conference (TREC) and finetune the parameters of the BM25 model -- which is used in many industrial-strength search engines like OpenSearch -- using the generated data.

[Arxiv](https://arxiv.org/abs/2505.04732)