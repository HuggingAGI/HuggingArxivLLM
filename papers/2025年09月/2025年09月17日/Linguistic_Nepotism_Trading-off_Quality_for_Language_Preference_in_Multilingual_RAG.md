# 语言偏袒：多语言RAG中为语言偏好牺牲质量

发布时间：2025年09月17日

`RAG` `基础理论`

> Linguistic Nepotism: Trading-off Quality for Language Preference in Multilingual RAG

# 摘要

> 多语言检索增强生成（mRAG）系统让语言模型能够跨语言回答知识密集型查询，并生成带引用支持的回答。尽管这类系统已问世，但一个尚未解决的问题是：不同文档语言的混合是否会以非预期方式影响生成内容与引用行为。为此，我们提出一种控制方法，通过模型内部机制测量语言偏好，同时保持文档相关性等其他因素恒定。在八种语言与六个开源模型的实验中，我们发现：当查询为英文时，模型会优先引用英文来源；这种偏见在低资源语言场景及上下文中间位置的文档中更为显著。更关键的是，模型有时会为了迎合语言偏好而牺牲文档相关性，这说明引用选择并非总是由信息量单独决定。研究结果揭示了语言模型如何利用多语言上下文并影响引用行为。

> Multilingual Retrieval-Augmented Generation (mRAG) systems enable language models to answer knowledge-intensive queries with citation-supported responses across languages. While such systems have been proposed, an open questions is whether the mixture of different document languages impacts generation and citation in unintended ways. To investigate, we introduce a controlled methodology using model internals to measure language preference while holding other factors such as document relevance constant. Across eight languages and six open-weight models, we find that models preferentially cite English sources when queries are in English, with this bias amplified for lower-resource languages and for documents positioned mid-context. Crucially, we find that models sometimes trade-off document relevance for language preference, indicating that citation choices are not always driven by informativeness alone. Our findings shed light on how language models leverage multilingual context and influence citation behavior.

[Arxiv](https://arxiv.org/abs/2509.13930)