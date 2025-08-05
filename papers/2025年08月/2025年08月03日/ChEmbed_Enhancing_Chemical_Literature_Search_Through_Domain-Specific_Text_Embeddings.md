# ChEmbed: 基于领域特定文本嵌入的化学文献搜索增强

发布时间：2025年08月03日

`RAG`

> ChEmbed: Enhancing Chemical Literature Search Through Domain-Specific Text Embeddings

# 摘要

> 在化学领域，检索增强生成（RAG）系统 heavily依赖于对化学文献的准确检索。然而，通用文本嵌入模型 frequently fail to adequately represent complex chemical terminologies，导致检索质量 suboptimal。专门针对化学文献检索的嵌入模型尚未开发，导致 performance gap显著。为了解决这一挑战，我们引入了ChEmbed，这是一个在包含PubChem、Semantic Scholar和ChemRxiv语料库的化学特定文本数据集上进行微调的领域适应型文本嵌入模型系列。为了创建有效的训练数据，我们利用大型语言模型 synthetically generate queries，得到了约170万个高质量的查询-段落对。此外，我们通过在tokenizer中添加900个化学专用tokens到之前未使用的插槽，显著减少了化学实体（如IUPAC名称）的片段化。ChEmbed还保持了8192-token的上下文长度，与通常具有512或2048-token上下文长度的许多其他开源嵌入模型相比，能够更高效地检索更长的段落。在我们新引入的ChemRxiv检索基准上进行评估，ChEmbed优于最先进的通用嵌入模型，将nDCG@10从0.82提高到0.91（+9 pp）。ChEmbed代表了一种实用、轻量级且可重复的嵌入解决方案，能够有效提高化学文献检索的效果。


> Retrieval-Augmented Generation (RAG) systems in chemistry heavily depend on accurate and relevant retrieval of chemical literature. However, general-purpose text embedding models frequently fail to adequately represent complex chemical terminologies, resulting in suboptimal retrieval quality. Specialized embedding models tailored to chemical literature retrieval have not yet been developed, leaving a substantial performance gap. To address this challenge, we introduce ChEmbed, a domain-adapted family of text embedding models fine-tuned on a dataset comprising chemistry-specific text from the PubChem, Semantic Scholar, and ChemRxiv corpora. To create effective training data, we employ large language models to synthetically generate queries, resulting in approximately 1.7 million high-quality query-passage pairs. Additionally, we augment the tokenizer by adding 900 chemically specialized tokens to previously unused slots, which significantly reduces the fragmentation of chemical entities, such as IUPAC names. ChEmbed also maintains a 8192-token context length, enabling the efficient retrieval of longer passages compared to many other open-source embedding models, which typically have a context length of 512 or 2048 tokens. Evaluated on our newly introduced ChemRxiv Retrieval benchmark, ChEmbed outperforms state-of-the-art general embedding models, raising nDCG@10 from 0.82 to 0.91 (+9 pp). ChEmbed represents a practical, lightweight, and reproducible embedding solution that effectively improves retrieval for chemical literature search.

[Arxiv](https://arxiv.org/abs/2508.01643)