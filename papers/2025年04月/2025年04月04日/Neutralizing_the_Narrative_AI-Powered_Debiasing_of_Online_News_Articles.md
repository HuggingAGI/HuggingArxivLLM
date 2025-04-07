# # 摘要  
中和叙事：AI驱动的在线新闻去偏见化  
最近，大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现。

发布时间：2025年04月04日

`LLM应用` `人工智能`

> Neutralizing the Narrative: AI-Powered Debiasing of Online News Articles

# 摘要

> 新闻报道中的偏见对公众认知有着重要影响，特别是在犯罪、政治和社会议题方面。传统的偏见检测方法主要依赖人工审核，存在主观解读和扩展性限制。我们提出了一种基于先进大型语言模型（LLMs）的AI驱动框架，特别是GPT-4o、GPT-4o Mini、Gemini Pro、Gemini Flash、Llama 8B和Llama 3B，系统性地识别和缓解新闻文章中的偏见。为此，我们构建了一个包含超过30,000篇与犯罪相关的文章的数据集，这些文章来自五个政治立场不同的新闻来源，时间跨度为十年（2013-2023）。我们的方法采用两阶段策略：首先通过LLM对段落级别的偏见内容进行评分和解释，并通过人工评估进行验证以建立真实基准；其次使用GPT-4o Mini进行迭代去偏，通过自动化重新评估和人工审核进行验证。实证结果表明，GPT-4o Mini在偏见检测中具有更高的准确性和去偏效果。此外，我们的分析揭示了媒体偏见在时间、地域上的变化，与社会政治动态和现实事件相关。本研究为偏见缓解提供了可扩展的计算方法，推动了新闻报道中的公平性和问责制。

> Bias in news reporting significantly impacts public perception, particularly regarding crime, politics, and societal issues. Traditional bias detection methods, predominantly reliant on human moderation, suffer from subjective interpretations and scalability constraints. Here, we introduce an AI-driven framework leveraging advanced large language models (LLMs), specifically GPT-4o, GPT-4o Mini, Gemini Pro, Gemini Flash, Llama 8B, and Llama 3B, to systematically identify and mitigate biases in news articles. To this end, we collect an extensive dataset consisting of over 30,000 crime-related articles from five politically diverse news sources spanning a decade (2013-2023). Our approach employs a two-stage methodology: (1) bias detection, where each LLM scores and justifies biased content at the paragraph level, validated through human evaluation for ground truth establishment, and (2) iterative debiasing using GPT-4o Mini, verified by both automated reassessment and human reviewers. Empirical results indicate GPT-4o Mini's superior accuracy in bias detection and effectiveness in debiasing. Furthermore, our analysis reveals temporal and geographical variations in media bias correlating with socio-political dynamics and real-world events. This study contributes to scalable computational methodologies for bias mitigation, promoting fairness and accountability in news reporting.

[Arxiv](https://arxiv.org/abs/2504.03520)