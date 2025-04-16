# 法律文件的多向量检索：结合引用与内容嵌入

发布时间：2025年04月09日

`RAG` `法律文本处理`

> Poly-Vector Retrieval: Reference and Content Embeddings for Legal Documents

# 摘要

> 检索增强生成（RAG）通过结合大型语言模型（LLMs）与检索机制，成为生成上下文准确答案的有效方法。然而，在法律领域，用户常通过规范的标签或别名（如“宪法第5条”或“消费者保护法典（CDC）”）引用法律条款，而非内容本身，这给传统RAG方法带来了挑战，因其仅依赖文本语义嵌入。此外，法律文本中充斥着显式的交叉引用（如“根据第34条”），这些交叉引用充当指向其他条款的指针。这两种情况都使传统RAG方法难以检索到必要的引用内容。本文提出了一种多向量检索方法，为每个法律条款分配多个嵌入：一个捕获内容（全文），另一个捕获标签（标识符或正式名称），并可选地附加嵌入捕获替代名称。受弗雷格对意义与指称区分的启发，该方法将标签、标识符和引用标记视为刚性指示符，而内容嵌入则承载语义实质。实验结果表明，多向量检索在基于标签的查询中显著提升了检索准确性，并在处理内部和外部交叉引用方面展现出潜力，同时保持了纯语义查询的性能。本研究探讨了在向量嵌入中明确区分指称与内容的哲学和实际意义，并提出了将此方法扩展到更广泛法律数据集及其他具有显式引用标识符领域的未来研究方向。

> Retrieval-Augmented Generation (RAG) has emerged as an effective paradigm for generating contextually accurate answers by integrating Large Language Models (LLMs) with retrieval mechanisms. However, in legal contexts, users frequently reference norms by their labels or nicknames (e.g., Article 5 of the Constitution or Consumer Defense Code (CDC)), rather than by their content, posing challenges for traditional RAG approaches that rely solely on semantic embeddings of text. Furthermore, legal texts themselves heavily rely on explicit cross-references (e.g., "pursuant to Article 34") that function as pointers. Both scenarios pose challenges for traditional RAG approaches that rely solely on semantic embeddings of text, often failing to retrieve the necessary referenced content. This paper introduces Poly-Vector Retrieval, a method assigning multiple distinct embeddings to each legal provision: one embedding captures the content (the full text), another captures the label (the identifier or proper name), and optionally additional embeddings capture alternative denominations. Inspired by Frege's distinction between Sense and Reference, this poly-vector retrieval approach treats labels, identifiers and reference markers as rigid designators and content embeddings as carriers of semantic substance. Experiments on the Brazilian Federal Constitution demonstrate that Poly-Vector Retrieval significantly improves retrieval accuracy for label-centric queries and potential to resolve internal and external cross-references, without compromising performance on purely semantic queries. The study discusses philosophical and practical implications of explicitly separating reference from content in vector embeddings and proposes future research directions for applying this approach to broader legal datasets and other domains characterized by explicit reference identifiers.

[Arxiv](https://arxiv.org/abs/2504.10508)