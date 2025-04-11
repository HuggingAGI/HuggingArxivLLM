# FairEval：评测基于LLM的推荐公平性，兼顾个性意识

发布时间：2025年04月10日

`LLM应用` `推荐系统` `社会公平`

> FairEval: Evaluating Fairness in LLM-Based Recommendations with Personality Awareness

# 摘要

> 大型语言模型（LLMs）的最新进展使其在推荐系统（RecLLMs）中得到应用，但关于不同人口统计和心理用户维度下的公平性问题仍存担忧。为此，我们引入了FairEval，一个全新的评估框架，用于系统性地评估基于LLM的推荐中的公平性。FairEval将人格特质与性别、种族和年龄等八种敏感的人口统计属性相结合，从而能够全面评估用户级别的偏见。我们对包括ChatGPT 4o和Gemini 1.5 Flash在内的模型在音乐和电影推荐方面进行了评估。结果显示，FairEval的公平性指标PAFS在ChatGPT 4o上达到了0.9969，在Gemini 1.5 Flash上更是高达0.9997，差异达到了34.79%。这些结果凸显了提示敏感性稳健性的重要性，并支持构建更加包容的推荐系统。

> Recent advances in Large Language Models (LLMs) have enabled their application to recommender systems (RecLLMs), yet concerns remain regarding fairness across demographic and psychological user dimensions. We introduce FairEval, a novel evaluation framework to systematically assess fairness in LLM-based recommendations. FairEval integrates personality traits with eight sensitive demographic attributes,including gender, race, and age, enabling a comprehensive assessment of user-level bias. We evaluate models, including ChatGPT 4o and Gemini 1.5 Flash, on music and movie recommendations. FairEval's fairness metric, PAFS, achieves scores up to 0.9969 for ChatGPT 4o and 0.9997 for Gemini 1.5 Flash, with disparities reaching 34.79 percent. These results highlight the importance of robustness in prompt sensitivity and support more inclusive recommendation systems.

[Arxiv](https://arxiv.org/abs/2504.07801)