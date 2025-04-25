# SCRAG: 基于社交计算的检索增强生成方法，用于社交媒体环境中的社区响应预测

发布时间：2025年04月18日

`RAG` `社交媒体` `公共关系`

> SCRAG: Social Computing-Based Retrieval Augmented Generation for Community Response Forecasting in Social Media Environments

# 摘要

> 本文提出了一种名为SCRAG的预测框架，该框架受社会计算启发，旨在预测社区对真实或假设的社交媒体帖子的反应。SCRAG的应用场景广泛，包括帮助公关专家优化信息传播策略、为公众人物和意见领袖预测社会反应，以及在公众情感预测、危机管理和社交媒体假设分析等领域提供支持。尽管大型语言模型（LLMs）在生成连贯且语境丰富的文本方面表现卓越，但其依赖静态训练数据以及易受幻觉影响的特性，使其在动态社交媒体环境中的反应预测能力受到限制。SCRAG通过将LLMs与基于社会计算的检索增强生成（RAG）技术相结合，成功克服了这些挑战。具体而言，SCRAG通过检索（i）目标社区的历史响应，捕捉其意识形态、语义和情感特征；以及（ii）来自新闻文章等外部知识源，注入时效性背景信息。这些信息被综合用于预测目标社区对新帖子或叙述的反应。在X平台（前Twitter）上进行的六个场景实验中，使用多种嵌入模型和LLMs进行测试，结果显示关键评估指标平均提升了10%以上。一个具体案例进一步验证了SCRAG在捕捉多样化意识形态和细微差别方面的有效性。我们的研究为需要准确洞察社区反应的应用场景提供了一个强大的社会计算工具。


> This paper introduces SCRAG, a prediction framework inspired by social computing, designed to forecast community responses to real or hypothetical social media posts. SCRAG can be used by public relations specialists (e.g., to craft messaging in ways that avoid unintended misinterpretations) or public figures and influencers (e.g., to anticipate social responses), among other applications related to public sentiment prediction, crisis management, and social what-if analysis. While large language models (LLMs) have achieved remarkable success in generating coherent and contextually rich text, their reliance on static training data and susceptibility to hallucinations limit their effectiveness at response forecasting in dynamic social media environments. SCRAG overcomes these challenges by integrating LLMs with a Retrieval-Augmented Generation (RAG) technique rooted in social computing. Specifically, our framework retrieves (i) historical responses from the target community to capture their ideological, semantic, and emotional makeup, and (ii) external knowledge from sources such as news articles to inject time-sensitive context. This information is then jointly used to forecast the responses of the target community to new posts or narratives. Extensive experiments across six scenarios on the X platform (formerly Twitter), tested with various embedding models and LLMs, demonstrate over 10% improvements on average in key evaluation metrics. A concrete example further shows its effectiveness in capturing diverse ideologies and nuances. Our work provides a social computing tool for applications where accurate and concrete insights into community responses are crucial.

[Arxiv](https://arxiv.org/abs/2504.16947)