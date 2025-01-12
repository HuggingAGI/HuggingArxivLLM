# RAG-Check: 多模态检索增强生成性能评估

发布时间：2025年01月07日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）在多模态环境下的应用，特别是如何通过引入外部知识来优化大型语言模型（LLMs）的响应生成，并减少幻觉现象。论文提出了一个新的框架，通过两个性能指标（相关性评分和正确性评分）来评估多模态RAG的可靠性，并进行了实验验证。因此，这篇论文的核心内容与RAG密切相关，应归类为RAG。` `信息检索`

> RAG-Check: Evaluating Multimodal Retrieval Augmented Generation Performance

# 摘要

> 检索增强生成（RAG）通过引入外部知识来优化大型语言模型（LLMs）的响应生成，有效减少了幻觉现象。然而，多模态RAG可能会带来新的幻觉来源：（i）检索过程可能从数据库中选取不相关的片段（如文档、图像）作为原始上下文，（ii）检索到的图像通过视觉语言模型（VLMs）转化为文本上下文，或被多模态语言模型（MLLMs）如GPT-4o直接使用，这可能导致幻觉。为此，我们提出了一种新框架，通过两个性能指标评估多模态RAG的可靠性：（i）相关性评分（RS），衡量检索条目与查询的相关性，（ii）正确性评分（CS），评估生成响应的准确性。我们使用ChatGPT生成的数据库和人类评估样本训练了RS和CS模型，结果显示两者在测试数据上的准确率均达到约88%。此外，我们还构建了一个包含5000个样本的人类注释数据库，用于评估检索片段的相关性和响应声明的正确性。实验表明，我们的RS模型在检索中比CLIP更符合人类偏好的频率高出20%，而CS模型在约91%的情况下与人类偏好一致。最后，我们利用RS和CS评估了多种RAG系统的选择和生成性能。

> Retrieval-augmented generation (RAG) improves large language models (LLMs) by using external knowledge to guide response generation, reducing hallucinations. However, RAG, particularly multi-modal RAG, can introduce new hallucination sources: (i) the retrieval process may select irrelevant pieces (e.g., documents, images) as raw context from the database, and (ii) retrieved images are processed into text-based context via vision-language models (VLMs) or directly used by multi-modal language models (MLLMs) like GPT-4o, which may hallucinate. To address this, we propose a novel framework to evaluate the reliability of multi-modal RAG using two performance measures: (i) the relevancy score (RS), assessing the relevance of retrieved entries to the query, and (ii) the correctness score (CS), evaluating the accuracy of the generated response. We train RS and CS models using a ChatGPT-derived database and human evaluator samples. Results show that both models achieve ~88% accuracy on test data. Additionally, we construct a 5000-sample human-annotated database evaluating the relevancy of retrieved pieces and the correctness of response statements. Our RS model aligns with human preferences 20% more often than CLIP in retrieval, and our CS model matches human preferences ~91% of the time. Finally, we assess various RAG systems' selection and generation performances using RS and CS.

[Arxiv](https://arxiv.org/abs/2501.03995)