# 提升通用文本嵌入中的否定感知能力：一种高效的数据与计算方法

发布时间：2025年04月01日

`LLM应用`

> Enhancing Negation Awareness in Universal Text Embeddings: A Data-efficient and Computational-efficient Approach

# 摘要

> 否定在自然语言处理的多个任务中扮演着重要角色，例如自然语言推理和情感分析任务。然而，像BERT、ELMo、RoBERTa或XLNet这样的上下文文本嵌入模型在准确理解否定方面仍面临挑战。近期在通用文本嵌入方面的进展虽然在各种任务中展现出更强的性能，但这些模型的否定感知能力仍因评估基准的偏见而不明朗。本研究深入分析了前沿通用文本嵌入模型的否定感知能力，发现这些模型在理解否定方面存在显著不足，常常将否定文本对误判为语义相似。为解决不同任务中对主题与否定信息等语义信息权衡的冲突，我们提出了一种无需修改文本嵌入模型参数的数据高效且计算高效的嵌入重新加权方法。该方法不仅能在简单和复杂的否定理解任务上显著提升文本嵌入模型的否定感知能力，还能显著增强基于大型语言模型的任务特定高维通用文本嵌入的否定感知能力。

> Negation plays an important role in various natural language processing tasks such as Natural Language Inference and Sentiment Analysis tasks. Numerous prior studies have found that contextual text embedding models such as BERT, ELMO, RoBERTa or XLNet face challenges in accurately understanding negation. Recent advancements in universal text embeddings have demonstrated superior performance over contextual text embeddings in various tasks. However, due to the bias in popular evaluation benchmarks, the negation awareness capacity of these models remains unclear. To bridge the gap in existing literature, an in-depth analysis is initiated in this work to study the negation awareness of cutting-edge universal text embedding models. Our findings reveal a significant lack of negation awareness in these models, often interpreting negated text pairs as semantically similar. To efficiently deal with the conflict that different tasks need different trade-offs between topic and negation information among other semantic information, a data-efficient and computational-efficient embedding re-weighting method is proposed without modifying the parameters of text embedding models. The proposed solution is able to improve text embedding models' negation awareness significantly on both simple negation understanding task and complex negation understanding task. Furthermore, the proposed solution can also significantly improve the negation awareness of Large Language Model based task-specific high dimensional universal text embeddings.

[Arxiv](https://arxiv.org/abs/2504.00584)