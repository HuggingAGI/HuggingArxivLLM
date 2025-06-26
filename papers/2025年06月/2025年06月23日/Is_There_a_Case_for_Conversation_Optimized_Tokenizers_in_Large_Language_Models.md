# 大型语言模型是否需要专门针对对话优化的分词器？」

发布时间：2025年06月23日

`LLM应用` `人工智能` `计算机科学`

> Is There a Case for Conversation Optimized Tokenizers in Large Language Models?

# 摘要

> 大型语言模型 (LLMs) 的计算和能源成本因模型规模扩大和数亿用户的广泛应用而急剧攀升。LLM 的单位成本是每个 token 的计算量，因此分词器在模型效率中至关重要，经过优化以尽量减少训练语料库中的 token 数量。聊天机器人作为 LLMs 最受欢迎的应用之一，其用户输入和回复的分词效果尤为关键，这些文本往往与训练语料库不同。于是，我们提出优化分词器以提升聊天机器人对话效率。本文利用公开的聊天机器人对话语料库，探索不同分词器的优化潜力，重新设计词汇表并评估其性能。结果显示，经过优化的分词器可使聊天对话中的 token 数量减少 5%-10%，显著节约能源，同时对原训练语料库的分词效率影响微乎其微，甚至略有提升。

> The computational and energy costs of Large Language Models (LLMs) have increased exponentially driven by the growing model sizes and the massive adoption of LLMs by hundreds of millions of users. The unit cost of an LLM is the computation of a token. Therefore, the tokenizer plays an important role in the efficiency of a model, and they are carefully optimized to minimize the number of tokens for the text in their training corpus. One of the most popular applications of LLMs are chatbots that interact with users. A key observation is that, for those chatbots, what is important is the performance of the tokenizer in the user text input and the chatbot responses. Those are most likely different from the text in the training corpus. So, a question that immediately arises is whether there is a potential benefit in optimizing tokenizers for chatbot conversations. In this paper, this idea is explored for different tokenizers by using a publicly available corpus of chatbot conversations to redesign their vocabularies and evaluate their performance in this domain. The results show that conversation-optimized tokenizers consistently reduce the number of tokens in chatbot dialogues, which can lead to meaningful energy savings, in the range of 5% to 10% while having minimal or even slightly positive impact on tokenization efficiency for the original training corpus.

[Arxiv](https://arxiv.org/abs/2506.18674)