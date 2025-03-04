# SAGE：面向RAG的精准检索框架

发布时间：2025年03月03日

`RAG

这篇论文主要讨论了检索增强生成（RAG）方法在问答任务中的改进，提出了一种新的框架SAGE来克服现有RAG方法的限制，因此应归类到RAG类别中。` `问答系统`

> SAGE: A Framework of Precise Retrieval for RAG

# 摘要

> 检索增强生成（RAG）在特定语料库内的问答任务中表现卓越。然而，RAG在问答任务中仍存在诸多失败案例。这些失败不仅源于大型语言模型（LLMs）的局限性，主要还在于以下两个限制导致LLMs检索到不准确的信息：(1) 当前RAG方法在语料库分割时未考虑语义，导致问题与分割后的段落相关性受损，难以找到相关上下文。(2) 检索上下文时存在权衡：检索较少上下文可能遗漏重要信息，而检索较多上下文则可能引入无关内容。
    本文提出了一种名为SAGE的RAG框架，以克服上述限制。首先，针对语义分割问题，我们建议训练一个语义分割模型，将语料库分割为语义完整的块。其次，我们设计了一个块选择算法，基于相关性分数递减速度动态选择块，确保仅检索到最相关的块。第三，我们建议让LLMs评估检索到的块是否过多或过少，并相应调整上下文数量，以进一步确保检索准确性。实验表明，SAGE在问答质量上平均比基线模型高出61.25%。此外，通过避免检索噪声上下文，SAGE降低了LLM推理中的token消耗成本，并在成本效率上平均提升了49.41%。此外，我们的工作为提升RAG性能提供了宝贵见解。

> Retrieval-augmented generation (RAG) has demonstrated significant proficiency in conducting question-answering (QA) tasks within a specified corpus. Nonetheless, numerous failure instances of RAG in QA still exist. These failures are not solely attributable to the limitations of Large Language Models (LLMs); instead, they predominantly arise from the retrieval of inaccurate information for LLMs due to two limitations: (1) Current RAG methods segment the corpus without considering semantics, making it difficult to find relevant context due to impaired correlation between questions and the segments. (2) There is a trade-off between missing essential context with fewer context retrieved and getting irrelevant context with more context retrieved.
  In this paper, we introduce a RAG framework (SAGE), to overcome these limitations. First, to address the segmentation issue without considering semantics, we propose to train a semantic segmentation model. This model is trained to segment the corpus into semantically complete chunks. Second, to ensure that only the most relevant chunks are retrieved while the irrelevant ones are ignored, we design a chunk selection algorithm to dynamically select chunks based on the decreasing speed of the relevance score, leading to a more relevant selection. Third, to further ensure the precision of the retrieved chunks, we propose letting LLMs assess whether retrieved chunks are excessive or lacking and then adjust the amount of context accordingly. Experiments show that SAGE outperforms baselines by 61.25% in the quality of QA on average. Moreover, by avoiding retrieving noisy context, SAGE lowers the cost of the tokens consumed in LLM inference and achieves a 49.41% enhancement in cost efficiency on average. Additionally, our work offers valuable insights for boosting RAG.

[Arxiv](https://arxiv.org/abs/2503.01713)