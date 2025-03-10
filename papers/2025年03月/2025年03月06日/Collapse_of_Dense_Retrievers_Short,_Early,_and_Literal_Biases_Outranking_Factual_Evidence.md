# 密集检索器失效：简短、早期和字面偏见主导事实依据

发布时间：2025年03月06日

`RAG` `信息检索`

> Collapse of Dense Retrievers: Short, Early, and Literal Biases Outranking Factual Evidence

# 摘要

> 密集检索模型在信息检索（IR）领域广泛应用，例如在检索增强生成（RAG）系统中。作为这些系统的关键第一步，其健壮性至关重要，直接关系到系统的成败。本研究通过重新利用关系抽取数据集（如 Re-DocRED），设计了受控实验，量化了启发式偏见（例如偏好较短文档）对 Dragon+ 和 Contriever 等检索器的影响。

研究发现，检索器存在显著的脆弱性：它们往往依赖于浅层模式，如过度优先处理文档开头、偏好较短文档、重复实体和字面匹配。此外，检索器往往忽视文档是否包含查询的答案，缺乏深层次的语义理解。更令人担忧的是，当多种偏见叠加时，模型会出现灾难性的性能下降，在有偏见的无答案文档中选择包含答案文档的情况不足3%。

此外，我们还展示了这些偏见对下游应用（如 RAG）的直接影响。检索偏好的文档可能会误导大语言模型，导致性能下降34%以上，甚至不如不提供任何文档的情况。


> Dense retrieval models are commonly used in Information Retrieval (IR) applications, such as Retrieval-Augmented Generation (RAG). Since they often serve as the first step in these systems, their robustness is critical to avoid failures. In this work, by repurposing a relation extraction dataset (e.g. Re-DocRED), we design controlled experiments to quantify the impact of heuristic biases, such as favoring shorter documents, in retrievers like Dragon+ and Contriever. Our findings reveal significant vulnerabilities: retrievers often rely on superficial patterns like over-prioritizing document beginnings, shorter documents, repeated entities, and literal matches. Additionally, they tend to overlook whether the document contains the query's answer, lacking deep semantic understanding. Notably, when multiple biases combine, models exhibit catastrophic performance degradation, selecting the answer-containing document in less than 3% of cases over a biased document without the answer. Furthermore, we show that these biases have direct consequences for downstream applications like RAG, where retrieval-preferred documents can mislead LLMs, resulting in a 34% performance drop than not providing any documents at all.

[Arxiv](https://arxiv.org/abs/2503.05037)