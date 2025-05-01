# 经济高效的LLM方法，助力打击在线市场中的野生动植物非法交易

发布时间：2025年04月29日

`LLM应用` `野生动物保护` `电子商务`

> A Cost-Effective LLM-based Approach to Identify Wildlife Trafficking in Online Marketplaces

# 摘要

> 野生动物非法交易仍是全球性的重大问题，严重影响着生物多样性、生态稳定和公共健康。尽管各方都在努力打击这一非法交易，但电子商务平台的兴起却使野生动物制品的销售变得更加容易，对濒危和受威胁物种的野外种群施加了新的压力。然而，这些平台的使用也带来了新的机遇：当犯罪分子在网上销售野生动物制品时，他们会留下活动的数字痕迹，这些痕迹可以为研究非法交易活动及其可能的破坏方式提供线索。难点在于发现这些数字痕迹。在线 marketplace 上充斥着琳琅满目的商品广告，从中识别出与野生动物相关的广告犹如大海捞针。学习分类器可以实现广告的自动化识别，但创建分类器需要耗费大量时间和成本进行数据标注，这限制了对多样化广告和研究问题的支持。本文聚焦野生动物非法交易数据分析中的数据科学管道的关键挑战：为用于筛选相关数据的分类器生成高质量标注数据。尽管大型语言模型（LLMs）可以直接对广告进行标注，但大规模应用这种方法的成本过于高昂。我们提出了一种经济高效的策略，利用LLMs为少量数据生成伪标签，再基于这些标签创建专门的分类模型。我们的创新方法能够自动收集多样化且具有代表性的样本进行标注，同时大幅降低标注成本。实验结果表明，我们的分类器实现了高达95%的F1分数，在成本更低的情况下超越了LLMs的表现。我们通过真实案例展示了本方法在支持野生动物非法交易多维度分析中的有效性。


> Wildlife trafficking remains a critical global issue, significantly impacting biodiversity, ecological stability, and public health. Despite efforts to combat this illicit trade, the rise of e-commerce platforms has made it easier to sell wildlife products, putting new pressure on wild populations of endangered and threatened species. The use of these platforms also opens a new opportunity: as criminals sell wildlife products online, they leave digital traces of their activity that can provide insights into trafficking activities as well as how they can be disrupted. The challenge lies in finding these traces. Online marketplaces publish ads for a plethora of products, and identifying ads for wildlife-related products is like finding a needle in a haystack. Learning classifiers can automate ad identification, but creating them requires costly, time-consuming data labeling that hinders support for diverse ads and research questions. This paper addresses a critical challenge in the data science pipeline for wildlife trafficking analytics: generating quality labeled data for classifiers that select relevant data. While large language models (LLMs) can directly label advertisements, doing so at scale is prohibitively expensive. We propose a cost-effective strategy that leverages LLMs to generate pseudo labels for a small sample of the data and uses these labels to create specialized classification models. Our novel method automatically gathers diverse and representative samples to be labeled while minimizing the labeling costs. Our experimental evaluation shows that our classifiers achieve up to 95% F1 score, outperforming LLMs at a lower cost. We present real use cases that demonstrate the effectiveness of our approach in enabling analyses of different aspects of wildlife trafficking.

[Arxiv](https://arxiv.org/abs/2504.21211)