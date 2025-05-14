# # TrumorGPT：基于图的检索增强型大型语言模型用于事实核查

发布时间：2025年05月11日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLM）在健康领域事实核查中的应用，特别是通过结合检索增强生成（RAG）来解决幻觉问题和数据更新问题。论文的重点在于LLM的应用和其在特定领域的解决方案，因此归类为LLM应用。`

> TrumorGPT: Graph-Based Retrieval-Augmented Large Language Model for Fact-Checking

# 摘要

> 在这个社交媒体时代，虚假信息和谣言的迅速传播引发了信息疫情，虚假信息对社会构成了重大威胁。为应对这一问题，我们推出了TrumorGPT，一款专为健康领域事实核查设计的新型生成式人工智能解决方案。TrumorGPT的独特之处在于它能辨别“trumors”——那些看似谣言却最终被证实为真的健康信息，从而帮助区分无端猜测与事实依据，为健康谣言的核实提供重要工具。

TrumorGPT采用带有少量样本学习的大型语言模型（LLM），通过语义健康知识图谱的构建和语义推理进行事实核查。它还集成了基于图的检索增强生成（GraphRAG），有效解决了LLMs常见的幻觉问题以及静态训练数据的局限性。GraphRAG通过接入定期更新的语义健康知识图谱，获取最新的医疗新闻和健康信息，确保TrumorGPT的事实核查基于最新数据。

通过广泛的医疗数据集进行评估，TrumorGPT在公共卫生声明的事实核查方面表现出色。它在各类平台间有效开展事实核查的能力，标志着在对抗健康类 misinformation 的斗争中迈出了重要一步，提升了数字信息时代的信任与准确性。

> In the age of social media, the rapid spread of misinformation and rumors has led to the emergence of infodemics, where false information poses a significant threat to society. To combat this issue, we introduce TrumorGPT , a novel generative artificial intelligence solution designed for fact-checking in the health domain. TrumorGPT aims to distinguish "trumors", which are health-related rumors that turn out to be true, providing a crucial tool in differentiating between mere speculation and verified facts. This framework leverages a large language model (LLM) with few-shot learning for semantic health knowledge graph construction and semantic reasoning. TrumorGPT incorporates graph-based retrieval-augmented generation (GraphRAG) to address the hallucination issue common in LLMs and the limitations of static training data. GraphRAG involves accessing and utilizing information from regularly updated semantic health knowledge graphs that consist of the latest medical news and health information, ensuring that fact-checking by TrumorGPT is based on the most recent data. Evaluating with extensive healthcare datasets, TrumorGPT demonstrates superior performance in fact-checking for public health claims. Its ability to effectively conduct fact-checking across various platforms marks a critical step forward in the fight against health-related misinformation, enhancing trust and accuracy in the digital information age.

[Arxiv](https://arxiv.org/abs/2505.07891)