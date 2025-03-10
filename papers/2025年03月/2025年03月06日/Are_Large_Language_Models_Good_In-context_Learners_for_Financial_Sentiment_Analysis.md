# 大型语言模型在金融情感分析中的上下文学习能力如何？

发布时间：2025年03月06日

`LLM应用` `金融AI`

> Are Large Language Models Good In-context Learners for Financial Sentiment Analysis?

# 摘要

> 近年来，拥有数百亿参数的大型语言模型（LLMs）在无需针对特定领域数据进行微调的情况下，在各领域中展现出超越传统方法的强大能力。然而，在金融AI领域的核心任务——金融情感分析（FSA）中，这些模型常常面临复杂金融术语、主观情感表达以及模糊倾向性描述等多重挑战。本文的核心问题是：LLMs能否成为金融情感分析中的优秀上下文学习者？这一问题的答案将揭示LLMs是否能通过泛化金融文档与情感配对的上下文演示，来应对这些挑战。特别值得注意的是，鉴于在金融特定数据上对这些模型进行微调的难度（甚至可以说是不可能的），这一问题显得尤为重要。据我们所知，这是第一篇探索金融情感分析中上下文学习的论文，涵盖了几乎所有现代LLMs（包括近期发布的DeepSeek V3）以及多种上下文样本选择方法。通过全面的实验，我们验证了LLMs在金融情感分析任务中的上下文学习能力。

> Recently, large language models (LLMs) with hundreds of billions of parameters have demonstrated the emergent ability, surpassing traditional methods in various domains even without fine-tuning over domain-specific data. However, when it comes to financial sentiment analysis (FSA)$unicode{x2013}$a fundamental task in financial AI$unicode{x2013}$these models often encounter various challenges, such as complex financial terminology, subjective human emotions, and ambiguous inclination expressions. In this paper, we aim to answer the fundamental question: whether LLMs are good in-context learners for FSA? Unveiling this question can yield informative insights on whether LLMs can learn to address the challenges by generalizing in-context demonstrations of financial document-sentiment pairs to the sentiment analysis of new documents, given that finetuning these models on finance-specific data is difficult, if not impossible at all. To the best of our knowledge, this is the first paper exploring in-context learning for FSA that covers most modern LLMs (recently released DeepSeek V3 included) and multiple in-context sample selection methods. Comprehensive experiments validate the in-context learning capability of LLMs for FSA.

[Arxiv](https://arxiv.org/abs/2503.04873)