# 基于LLM的推荐：知识图谱检索增强生成

发布时间：2025年01月04日

`RAG

理由：这篇论文主要讨论了如何利用检索增强生成（RAG）技术来改进基于大型语言模型（LLM）的推荐系统。具体来说，作者提出了一个名为K-RagRec的框架，通过整合外部知识图谱（KG）的结构信息来增强推荐生成过程。这种方法属于RAG的范畴，因为它涉及到利用外部知识源来增强LLM的能力，并且特别强调了知识图谱在检索过程中的作用。因此，这篇论文应被分类为RAG。` `推荐系统` `知识图谱`

> Knowledge Graph Retrieval-Augmented Generation for LLM-based Recommendation

# 摘要

> 推荐系统在我们的日常生活中扮演着越来越重要的角色，帮助解决各种用户导向的在线服务中的信息过载问题。大型语言模型（LLMs）的崛起带来了显著成就，展现了其在下一代推荐系统开发中的潜力。然而，基于LLM的推荐系统仍面临一些固有局限，如幻觉问题和缺乏最新及领域特定知识。最近，检索增强生成（RAG）通过利用外部知识源来增强LLM的理解和生成能力，引起了广泛关注。但普通RAG方法常引入噪声并忽略知识中的结构关系，限制了其在基于LLM的推荐中的效果。为此，我们提出从知识图谱（KG）中检索高质量和最新的结构信息来增强推荐。具体而言，我们开发了一个名为K-RagRec的检索增强框架，通过整合外部KG的结构信息来优化推荐生成过程。大量实验验证了我们方法的有效性。

> Recommender systems have become increasingly vital in our daily lives, helping to alleviate the problem of information overload across various user-oriented online services. The emergence of Large Language Models (LLMs) has yielded remarkable achievements, demonstrating their potential for the development of next-generation recommender systems. Despite these advancements, LLM-based recommender systems face inherent limitations stemming from their LLM backbones, particularly issues of hallucinations and the lack of up-to-date and domain-specific knowledge. Recently, Retrieval-Augmented Generation (RAG) has garnered significant attention for addressing these limitations by leveraging external knowledge sources to enhance the understanding and generation of LLMs. However, vanilla RAG methods often introduce noise and neglect structural relationships in knowledge, limiting their effectiveness in LLM-based recommendations. To address these limitations, we propose to retrieve high-quality and up-to-date structure information from the knowledge graph (KG) to augment recommendations. Specifically, our approach develops a retrieval-augmented framework, termed K-RagRec, that facilitates the recommendation generation process by incorporating structure information from the external KG. Extensive experiments have been conducted to demonstrate the effectiveness of our proposed method.

[Arxiv](https://arxiv.org/abs/2501.02226)