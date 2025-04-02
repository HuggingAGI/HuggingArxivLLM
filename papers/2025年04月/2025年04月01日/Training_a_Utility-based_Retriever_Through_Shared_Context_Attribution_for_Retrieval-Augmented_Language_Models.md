# 通过共享上下文归属，训练一个用于检索增强语言模型的基于效用的检索器。

发布时间：2025年04月01日

`RAG` `信息检索`

> Training a Utility-based Retriever Through Shared Context Attribution for Retrieval-Augmented Language Models

# 摘要

> 检索增强型语言模型（RALMs）的性能提升得益于检索器提供的外部知识。然而，检索器主要关注语义相关性，这可能并不总是对生成任务有效。因此，基于效用的检索作为一种有前景的主题应运而生，优先考虑对下游任务提供有效益的段落。然而，由于理解不足，准确捕捉段落效用仍是一个未被探索的领域。本研究提出了一种名为SCARLet的框架，用于在RALMs中训练基于效用的检索器，该框架整合了多任务泛化和篇章交互两大关键要素。首先，SCARLet构建了一个共享上下文，在此基础上合成各类任务的训练数据。这有助于缓解因上下文差异带来的语义偏差，使检索器能够专注于学习任务特定效用，从而实现更好的任务泛化。其次，SCARLet采用基于扰动的归因方法，估算共享上下文中的篇章级效用，这反映了篇章间的交互作用，提供了更为精准的反馈。我们在涵盖各类任务的十个数据集上评估了我们的方法，包括领域内和跨领域测试，结果显示，通过SCARLet训练的检索器能够持续提升RALMs的整体性能。

> Retrieval-Augmented Language Models boost task performance, owing to the retriever that provides external knowledge. Although crucial, the retriever primarily focuses on semantics relevance, which may not always be effective for generation. Thus, utility-based retrieval has emerged as a promising topic, prioritizing passages that provides valid benefits for downstream tasks. However, due to insufficient understanding, capturing passage utility accurately remains unexplored. This work proposes SCARLet, a framework for training utility-based retrievers in RALMs, which incorporates two key factors, multi-task generalization and inter-passage interaction. First, SCARLet constructs shared context on which training data for various tasks is synthesized. This mitigates semantic bias from context differences, allowing retrievers to focus on learning task-specific utility for better task generalization. Next, SCARLet uses a perturbation-based attribution method to estimate passage-level utility for shared context, which reflects interactions between passages and provides more accurate feedback. We evaluate our approach on ten datasets across various tasks, both in-domain and out-of-domain, showing that retrievers trained by SCARLet consistently improve the overall performance of RALMs.

[Arxiv](https://arxiv.org/abs/2504.00573)