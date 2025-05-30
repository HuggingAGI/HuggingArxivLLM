# 优化多语言社交媒体分析：基于方面的评论分析

发布时间：2025年05月28日

`LLM应用` `社交媒体`

> Improving Multilingual Social Media Insights: Aspect-based Comment Analysis

# 摘要

> 社交媒体帖子的自由性和零散观点、话题的特性，为评论聚类、摘要及观点分析等NLP任务带来了显著挑战。我们提出了一种基于粒度级别的方法，通过从单条评论中提取方面术语来引导模型注意力。具体而言，我们采用多语言大型语言模型，通过监督微调实现评论方面术语生成（CAT-G），并借助DPO使模型预测更符合人类预期。我们通过两项NLP任务验证了该方法在提升社交媒体话语理解方面的有效性。此外，本文还提供了首个涵盖英语、中文、马来语和印尼语的多语言CAT-G测试集，为不同语言水平的LLM性能比较分析提供了可能。

> The inherent nature of social media posts, characterized by the freedom of language use with a disjointed array of diverse opinions and topics, poses significant challenges to downstream NLP tasks such as comment clustering, comment summarization, and social media opinion analysis. To address this, we propose a granular level of identifying and generating aspect terms from individual comments to guide model attention. Specifically, we leverage multilingual large language models with supervised fine-tuning for comment aspect term generation (CAT-G), further aligning the model's predictions with human expectations through DPO. We demonstrate the effectiveness of our method in enhancing the comprehension of social media discourse on two NLP tasks. Moreover, this paper contributes the first multilingual CAT-G test set on English, Chinese, Malay, and Bahasa Indonesian. As LLM capabilities vary among languages, this test set allows for a comparative analysis of performance across languages with varying levels of LLM proficiency.

[Arxiv](https://arxiv.org/abs/2505.23037)