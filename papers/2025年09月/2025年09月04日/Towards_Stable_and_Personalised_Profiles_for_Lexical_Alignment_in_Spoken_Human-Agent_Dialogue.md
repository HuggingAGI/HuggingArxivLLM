# 迈向口语人机对话中词汇对齐的稳定个性化特征模型

发布时间：2025年09月04日

`Agent` `基础理论`

> Towards Stable and Personalised Profiles for Lexical Alignment in Spoken Human-Agent Dialogue

# 摘要

> 词汇对齐——即对话中说话者逐渐使用相似词汇——被认为是成功交流的关键因素。然而，尽管大型语言模型（LLMs）近年发展迅速，其在对话智能体中的应用却仍有待深入研究。为推动人机对话中的词汇对齐，本研究首先借鉴对话智能体的个性化策略，探究构建稳定、个性化的词汇档案，将其作为词汇对齐的基础。具体而言，研究团队调整了用于构建档案的转录口语数据量，以及每个词性（POS）类别下档案包含的项目数量，并通过召回率、覆盖率和余弦相似度指标，对档案性能进行了跨时间评估。结果显示，基于10分钟转录语音构建的精简档案表现最佳——其中形容词和连词各5项，副词、名词、代词、动词各10项——在性能与数据效率间实现了最优平衡。综上，本研究为构建稳定、个性化的词汇档案提供了实用指导，同时兼顾了最小数据需求，为对话智能体的词汇对齐策略奠定了基础。

> Lexical alignment, where speakers start to use similar words across conversation, is known to contribute to successful communication. However, its implementation in conversational agents remains underexplored, particularly considering the recent advancements in large language models (LLMs). As a first step towards enabling lexical alignment in human-agent dialogue, this study draws on strategies for personalising conversational agents and investigates the construction of stable, personalised lexical profiles as a basis for lexical alignment. Specifically, we varied the amounts of transcribed spoken data used for construction as well as the number of items included in the profiles per part-of-speech (POS) category and evaluated profile performance across time using recall, coverage, and cosine similarity metrics. It was shown that smaller and more compact profiles, created after 10 min of transcribed speech containing 5 items for adjectives, 5 items for conjunctions, and 10 items for adverbs, nouns, pronouns, and verbs each, offered the best balance in both performance and data efficiency. In conclusion, this study offers practical insights into constructing stable, personalised lexical profiles, taking into account minimal data requirements, serving as a foundational step toward lexical alignment strategies in conversational agents.

[Arxiv](https://arxiv.org/abs/2509.04104)