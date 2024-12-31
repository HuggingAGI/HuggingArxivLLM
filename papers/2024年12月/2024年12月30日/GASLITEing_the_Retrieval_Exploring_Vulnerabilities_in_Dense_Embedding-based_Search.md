# GASLITE 化检索：探寻基于密集嵌入的搜索中的脆弱之处

发布时间：2024年12月30日

`RAG` `信息安全`

> GASLITEing the Retrieval: Exploring Vulnerabilities in Dense Embedding-based Search

# 摘要

> 基于密集嵌入的文本检索——即通过深度学习编码从语料库中检索相关段落——已成为一种强大的手段，达成了顶尖的搜索结果，还推动了检索增强生成（RAG）的运用。不过，和其他搜索方法类似，基于嵌入的检索可能易受搜索引擎优化（SEO）攻击，攻击者会通过向语料库引入对抗性段落来推广恶意内容。为切实评估并深入了解此类系统对SEO的敏感性，本研究提出了GASLITE攻击，这是一种遵循数学原理的基于梯度的搜索方法，用于生成对抗性段落，无需依赖语料库内容或修改模型。值得注意的是，GASLITE生成的段落（1）携带攻击者选定的信息，同时（2）在插入语料库时，对于选定的查询分布能实现高检索排名。我们借助GASLITE广泛评估检索器的稳健性，在不同威胁模型下测试了九个先进模型，同时聚焦于针对特定概念（比如公众人物）查询的现实攻击者。我们发现，在所有设定中，GASLITE始终以≥140％的成功率优于基线。特别是，使用GASLITE的攻击者只需付出极小的努力就能操纵搜索结果——通过注入微不足道的对抗性段落（≤语料库的0.0001％），就能让这些段落在针对大多数评估模型的61-100％的未见过的特定概念查询的前10个结果中现身。通过考察检索器稳健性的差异，我们确定了可能致使模型对SEO敏感的关键因素，包括嵌入空间几何中的特定属性。

> Dense embedding-based text retrieval$unicode{x2013}$retrieval of relevant passages from corpora via deep learning encodings$unicode{x2013}$has emerged as a powerful method attaining state-of-the-art search results and popularizing the use of Retrieval Augmented Generation (RAG). Still, like other search methods, embedding-based retrieval may be susceptible to search-engine optimization (SEO) attacks, where adversaries promote malicious content by introducing adversarial passages to corpora. To faithfully assess and gain insights into the susceptibility of such systems to SEO, this work proposes the GASLITE attack, a mathematically principled gradient-based search method for generating adversarial passages without relying on the corpus content or modifying the model. Notably, GASLITE's passages (1) carry adversary-chosen information while (2) achieving high retrieval ranking for a selected query distribution when inserted to corpora. We use GASLITE to extensively evaluate retrievers' robustness, testing nine advanced models under varied threat models, while focusing on realistic adversaries targeting queries on a specific concept (e.g., a public figure). We found GASLITE consistently outperformed baselines by $\geq$140% success rate, in all settings. Particularly, adversaries using GASLITE require minimal effort to manipulate search results$unicode{x2013}$by injecting a negligible amount of adversarial passages ($\leq$0.0001% of the corpus), they could make them visible in the top-10 results for 61-100% of unseen concept-specific queries against most evaluated models. Inspecting variance in retrievers' robustness, we identify key factors that may contribute to models' susceptibility to SEO, including specific properties in the embedding space's geometry.

[Arxiv](https://arxiv.org/abs/2412.20953)