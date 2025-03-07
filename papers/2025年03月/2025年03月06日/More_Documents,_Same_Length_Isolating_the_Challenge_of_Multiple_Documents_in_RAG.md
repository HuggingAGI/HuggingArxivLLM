# 更多文档，相同长度：RAG中的多文档挑战解析

发布时间：2025年03月06日

`RAG` `问答系统`

> More Documents, Same Length: Isolating the Challenge of Multiple Documents in RAG

# 摘要

> 检索增强生成（RAG）为大型语言模型（LLMs）提供相关文档。尽管之前的研究指出，检索大量文档可能会降低性能效果，但他们并未单独研究文档数量对性能的影响，同时控制上下文长度不变。我们在源自多跳问答任务的自定义数据集上评估了各种语言模型。我们保持上下文长度和相关信息的位置不变，同时改变文档数量，发现增加RAG设置中的文档数量对LLMs提出了重大挑战。此外，我们的结果表明，处理多个文档与处理长上下文是两个独立的挑战。我们还提供了数据集和代码：https://github.com/shaharl6000/MoreDocsSameLen 。


> Retrieval-augmented generation (RAG) provides LLMs with relevant documents. Although previous studies noted that retrieving many documents can degrade performance, they did not isolate how the quantity of documents affects performance while controlling for context length. We evaluate various language models on custom datasets derived from a multi-hop QA task. We keep the context length and position of relevant information constant while varying the number of documents, and find that increasing the document count in RAG settings poses significant challenges for LLMs. Additionally, our results indicate that processing multiple documents is a separate challenge from handling long contexts. We also make the datasets and code available: https://github.com/shaharl6000/MoreDocsSameLen .

[Arxiv](https://arxiv.org/abs/2503.04388)