# 关于具有 RAG 系统的异构数据的会话式问答中的证据情境化和反事实归因

发布时间：2024年12月18日

`RAG` `问答系统`

> Evidence Contextualization and Counterfactual Attribution for Conversational QA over Heterogeneous Data with RAG Systems

# 摘要

> 检索增强生成（RAG）是通过对话式问答（ConvQA）与企业自有数据交互的核心。在 RAG 系统中，检索器会依据问题从集合里获取段落，接着将其纳入大型语言模型（LLM）的提示中以生成自然语言（NL）答案。然而，当下的一些 RAG 系统存在两个缺陷：（一）检索出的段落往往包含原始文本且缺乏恰当的文档语境，对检索和回答质量产生不利影响；（二）用于解释答案生成的归因策略通常仅依赖于答案与检索段落之间的相似度，因此只能给出看似合理却非因果性的解释。在本研究中，我们展示了 RAGONITE 这一 RAG 系统，它通过以下方式解决了上述问题：（一）利用源元数据和周边文本对证据进行情境化处理；（二）计算反事实归因，这是一种因果解释方法，其中证据对答案的贡献由原始响应与删除该证据后所得答案的相似度来确定。为评估我们的提议，我们发布了新的基准 ConfQuestions，其中包含 300 个手工创建的对话问题，每个问题都有英语和德语版本，还附有真实的 URL、完整的问题以及来自 215 个公共 Confluence 页面的答案，这些页面是具有异构元素的典型企业维基空间。在 ConfQuestions 上使用 RAGONITE 进行的实验表明了我们想法的可行性：情境化提升了 RAG 性能，反事实归因能有效地解释 RAG 答案。

> Retrieval Augmented Generation (RAG) works as a backbone for interacting with an enterprise's own data via Conversational Question Answering (ConvQA). In a RAG system, a retriever fetches passages from a collection in response to a question, which are then included in the prompt of a large language model (LLM) for generating a natural language (NL) answer. However, several RAG systems today suffer from two shortcomings: (i) retrieved passages usually contain their raw text and lack appropriate document context, negatively impacting both retrieval and answering quality; and (ii) attribution strategies that explain answer generation usually rely only on similarity between the answer and the retrieved passages, thereby only generating plausible but not causal explanations. In this work, we demonstrate RAGONITE, a RAG system that remedies the above concerns by: (i) contextualizing evidence with source metadata and surrounding text; and (ii) computing counterfactual attribution, a causal explanation approach where the contribution of an evidence to an answer is determined by the similarity of the original response to the answer obtained by removing that evidence. To evaluate our proposals, we release a new benchmark ConfQuestions, with 300 hand-created conversational questions, each in English and German, coupled with ground truth URLs, completed questions, and answers from 215 public Confluence pages, that are typical of enterprise wiki spaces with heterogeneous elements. Experiments with RAGONITE on ConfQuestions show the viability of our ideas: contextualization improves RAG performance, and counterfactual attribution is effective at explaining RAG answers.

[Arxiv](https://arxiv.org/abs/2412.10571)