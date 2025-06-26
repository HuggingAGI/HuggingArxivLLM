# # Is There a Case for Conversation Optimized Tokenizers in Large Language Models?
大型语言模型中，是否需要对话优化的分词器？

发布时间：2025年06月23日

`LLM应用` `人工智能` `聊天机器人`

> Is There a Case for Conversation Optimized Tokenizers in Large Language Models?

# 摘要

> 大型语言模型（LLMs）的计算和能源成本呈指数级增长，主要源于模型规模的扩大和数亿用户的广泛应用。LLMs的单位成本计算基于一个token，因此分词器对模型效率至关重要，它们经过精心优化，以尽量减少训练语料库中的token数量。聊天机器人作为LLMs最常见的应用之一，其用户输入文本和回复的分词效果至关重要，这些文本很可能与训练语料库不同。因此，优化分词器以提升聊天机器人对话效果的想法值得探讨。本文针对不同分词器，使用公开的聊天机器人对话语料库，重新设计其词汇表，并评估其性能。结果显示，经过对话优化的分词器能显著减少聊天机器人对话中的token数量，实现5%到10%的能源节约，同时对原始训练语料库的分词效率影响微乎其微，甚至略有提升。

> The computational and energy costs of Large Language Models (LLMs) have increased exponentially driven by the growing model sizes and the massive adoption of LLMs by hundreds of millions of users. The unit cost of an LLM is the computation of a token. Therefore, the tokenizer plays an important role in the efficiency of a model, and they are carefully optimized to minimize the number of tokens for the text in their training corpus. One of the most popular applications of LLMs are chatbots that interact with users. A key observation is that, for those chatbots, what is important is the performance of the tokenizer in the user text input and the chatbot responses. Those are most likely different from the text in the training corpus. So, a question that immediately arises is whether there is a potential benefit in optimizing tokenizers for chatbot conversations. In this paper, this idea is explored for different tokenizers by using a publicly available corpus of chatbot conversations to redesign their vocabularies and evaluate their performance in this domain. The results show that conversation-optimized tokenizers consistently reduce the number of tokens in chatbot dialogues, which can lead to meaningful energy savings, in the range of 5% to 10% while having minimal or even slightly positive impact on tokenization efficiency for the original training corpus.

[Arxiv](https://arxiv.org/abs/2506.18674)