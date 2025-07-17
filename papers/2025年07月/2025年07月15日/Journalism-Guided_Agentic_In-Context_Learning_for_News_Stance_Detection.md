# 基于新闻引导的智能体上下文学习用于新闻立场检测

发布时间：2025年07月15日

`Agent` `新闻推荐` `媒体分析`

> Journalism-Guided Agentic In-Context Learning for News Stance Detection

# 摘要

> 随着在线新闻消费的蓬勃发展，个性化推荐系统已成为数字新闻生态中不可或缺的一部分。然而，这些系统在未能纳入多元观点的情况下，可能加剧过滤气泡和政治极化的现象。而立场检测——即识别文本对特定议题的立场——则为我们提供了一种解决方案，它不仅能够实现观点感知的推荐，还能通过数据驱动的方式分析媒体偏见。然而，现有的立场检测研究大多局限于短文本和高资源语言。为了解决这些局限，我们推出了	extsc{K-News-Stance}，这是首个用于文章级别立场检测的韩语数据集，包含2,000篇新闻文章，涉及47个社会问题，涵盖了2,000篇文章级别的立场标注和19,650个段落级别的立场标注。我们还提出了	extsc{JoA-ICL}，这是一个	extbf{Jo}urnalism-guided 	extbf{A}gentic 	extbf{I}n-	extbf{C}ontext 	extbf{L}earning框架，利用语言模型代理预测关键结构段落（如导语、引语）的立场，然后聚合这些预测结果以推断整篇文章的立场。实验结果表明，	extsc{JoA-ICL}在性能上优于现有的立场检测方法，充分展现了段落级别代理在捕捉长篇新闻文章整体立场方面的优势。两个案例研究进一步证明了它在促进新闻推荐中的观点多样性以及揭示媒体偏见模式方面的广泛应用前景。

> As online news consumption grows, personalized recommendation systems have become integral to digital journalism. However, these systems risk reinforcing filter bubbles and political polarization by failing to incorporate diverse perspectives. Stance detection -- identifying a text's position on a target -- can help mitigate this by enabling viewpoint-aware recommendations and data-driven analyses of media bias. Yet, existing stance detection research remains largely limited to short texts and high-resource languages. To address these gaps, we introduce \textsc{K-News-Stance}, the first Korean dataset for article-level stance detection, comprising 2,000 news articles with article-level and 19,650 segment-level stance annotations across 47 societal issues. We also propose \textsc{JoA-ICL}, a \textbf{Jo}urnalism-guided \textbf{A}gentic \textbf{I}n-\textbf{C}ontext \textbf{L}earning framework that employs a language model agent to predict the stances of key structural segments (e.g., leads, quotes), which are then aggregated to infer the overall article stance. Experiments show that \textsc{JoA-ICL} outperforms existing stance detection methods, highlighting the benefits of segment-level agency in capturing the overall position of long-form news articles. Two case studies further demonstrate its broader utility in promoting viewpoint diversity in news recommendations and uncovering patterns of media bias.

[Arxiv](https://arxiv.org/abs/2507.11049)