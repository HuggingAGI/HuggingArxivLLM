# # 摘要
NeoQA：基于生成新闻事件的证据式问答系统

发布时间：2025年05月09日

`RAG` `问答系统`

> NeoQA: Evidence-based Question Answering with Generated News Events

# 摘要

> 评估大型语言模型中的检索增强生成（RAG）颇具挑战性，因为基准测试很容易过时。最初需要检索的问题可能会随着新模型在预训练过程中纳入更多近期信息，变得可以通过预训练知识直接回答，这使得区分基于证据的推理与单纯记忆变得困难。我们提出了NeoQA（面向训练后问答的新闻事件基准），旨在解决这一问题。为了构建NeoQA，我们生成了虚构新闻事件和实体的时间线、知识库、新闻文章以及问答对，以此防止大型语言模型利用预训练知识，确保训练数据中不存在任何先验证据。我们提议将我们的数据集作为评估基于证据问答的新平台，因为它要求大型语言模型仅根据检索到的证据生成回答，并且仅在有足够证据时进行回答。NeoQA支持在各种证据场景下进行受控评估，包括存在缺失或误导性细节的情况。我们的研究发现，大型语言模型难以区分问题与证据之间的微妙不匹配，并且在关键信息缺失时会采用捷径推理，这凸显了基于证据推理的关键局限性。

> Evaluating Retrieval-Augmented Generation (RAG) in large language models (LLMs) is challenging because benchmarks can quickly become stale. Questions initially requiring retrieval may become answerable from pretraining knowledge as newer models incorporate more recent information during pretraining, making it difficult to distinguish evidence-based reasoning from recall. We introduce NeoQA (News Events for Out-of-training Question Answering), a benchmark designed to address this issue. To construct NeoQA, we generated timelines and knowledge bases of fictional news events and entities along with news articles and Q\&A pairs to prevent LLMs from leveraging pretraining knowledge, ensuring that no prior evidence exists in their training data. We propose our dataset as a new platform for evaluating evidence-based question answering, as it requires LLMs to generate responses exclusively from retrieved evidence and only when sufficient evidence is available. NeoQA enables controlled evaluation across various evidence scenarios, including cases with missing or misleading details. Our findings indicate that LLMs struggle to distinguish subtle mismatches between questions and evidence, and suffer from short-cut reasoning when key information required to answer a question is missing from the evidence, underscoring key limitations in evidence-based reasoning.

[Arxiv](https://arxiv.org/abs/2505.05949)