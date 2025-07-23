# 永不落空：自适应HyDE检索，助力提升LLM开发者支持

发布时间：2025年07月22日

`RAG` `软件开发` `编程帮助`

> Never Come Up Empty: Adaptive HyDE Retrieval for Improving LLM Developer Support

# 摘要

> 大型语言模型（LLMs）在帮助开发者解答代码相关问题方面表现出色，但其生成不可靠答案的风险依然存在。为解决这一问题，检索增强生成（RAG）方法被提出，旨在降低LLMs的幻觉风险。然而，由于设计选择的多样性，设计高效的RAG流水线仍然具有挑战性。在本研究中，我们构建了一个包含300多万个Java和Python相关Stack Overflow帖子及其被接受答案的检索语料库，并探索了多种RAG流水线设计，评估其生成准确可靠回答的能力。具体而言，我们（1）设计并评估了7种不同的RAG流水线和63种变体，用于回答有历史相似匹配的问题；（2）通过在检索过程中自动降低相似度阈值，解决那些没有相近历史匹配的新问题，从而增加发现部分相关上下文的机会，提升对未见情况的覆盖率。我们的研究发现，结合假设性文档嵌入（HyDE）与完整答案上下文的RAG流水线，在检索和回答Stack Overflow问题的相似内容方面表现最佳。最后，我们将最优RAG流水线应用于4个开源LLMs，并与零-shot性能进行对比。结果显示，采用我们最优RAG流水线的RAG在所有模型上均优于零-shot基线，以LLM作为评判标准时，在有用性、准确性和细节方面均获得了更高的分数。这些发现表明，我们的最优RAG流水线能够稳健地提升各类开发者查询的回答质量，包括不同LLMs下既有的和全新的问题。

> Large Language Models (LLMs) have shown promise in assisting developers with code-related questions; however, LLMs carry the risk of generating unreliable answers. To address this, Retrieval-Augmented Generation (RAG) has been proposed to reduce the unreliability (i.e., hallucinations) of LLMs. However, designing effective pipelines remains challenging due to numerous design choices. In this paper, we construct a retrieval corpus of over 3 million Java and Python related Stack Overflow posts with accepted answers, and explore various RAG pipeline designs to answer developer questions, evaluating their effectiveness in generating accurate and reliable responses. More specifically, we (1) design and evaluate 7 different RAG pipelines and 63 pipeline variants to answer questions that have historically similar matches, and (2) address new questions without any close prior matches by automatically lowering the similarity threshold during retrieval, thereby increasing the chance of finding partially relevant context and improving coverage for unseen cases. We find that implementing a RAG pipeline combining hypothetical-documentation-embedding (HyDE) with the full-answer context performs best in retrieving and answering similarcontent for Stack Overflow questions. Finally, we apply our optimal RAG pipeline to 4 open-source LLMs and compare the results to their zero-shot performance. Our findings show that RAG with our optimal RAG pipeline consistently outperforms zero-shot baselines across models, achieving higher scores for helpfulness, correctness, and detail with LLM-as-a-judge. These findings demonstrate that our optimal RAG pipelines robustly enhance answer quality for a wide range of developer queries including both previously seen and novel questions across different LLMs

[Arxiv](https://arxiv.org/abs/2507.16754)