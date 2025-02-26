# 言简意赅：语用学在检索增强生成中的应用

发布时间：2025年02月24日

`RAG` `问答系统` `公共卫生`

> Say Less, Mean More: Leveraging Pragmatics in Retrieval-Augmented Generation

# 摘要

> 我们提出了一种简单且无需监督的方法，通过在检索增强生成（RAG）框架（如密集段落检索~\cite{karpukhin2020densepassageretrievalopendomain}）中注入实用原则，来提升检索到的上下文的实用性。具体而言，我们的方法首先从RAG检索到的文档池中识别出与当前问题最相关的句子，确保这些句子覆盖了输入问题中涉及的所有主题且不超出范围，然后在这些句子的上下文中进行突出显示，并在不以任何其他方式截断或修改上下文的前提下，将这些句子提供给大型语言模型。我们在三个问答任务（ARC-Challenge、PubHealth 和 PopQA）上使用五种不同的大型语言模型进行了实验，结果表明，这一简单的方法带来了显著且一致的改进。与传统的RAG系统相比，它在PubHealth任务上的相对准确率提升了高达19.7%，在ARC-Challenge任务上提升了10%。

> We propose a simple, unsupervised method that injects pragmatic principles in retrieval-augmented generation (RAG) frameworks such as Dense Passage Retrieval~\cite{karpukhin2020densepassageretrievalopendomain} to enhance the utility of retrieved contexts. Our approach first identifies which sentences in a pool of documents retrieved by RAG are most relevant to the question at hand, cover all the topics addressed in the input question and no more, and then highlights these sentences within their context, before they are provided to the LLM, without truncating or altering the context in any other way. We show that this simple idea brings consistent improvements in experiments on three question answering tasks (ARC-Challenge, PubHealth and PopQA) using five different LLMs. It notably enhances relative accuracy by up to 19.7\% on PubHealth and 10\% on ARC-Challenge compared to a conventional RAG system.

[Arxiv](https://arxiv.org/abs/2502.17839)