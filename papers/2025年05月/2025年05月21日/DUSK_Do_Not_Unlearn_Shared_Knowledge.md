# # DUSK：保留共享知识，拒绝遗忘

发布时间：2025年05月21日

`LLM应用

论文摘要：大型语言模型（LLMs）在现实世界中的广泛应用引发担忧，未经授权的版权内容或敏感数据可能被滥用。机器遗忘技术旨在移除特定数据，同时保留其他信息。然而，现有评估往往假设遗忘和保留的数据完全独立，忽视了现实中它们可能共享内容的情况。例如，一篇新闻报道需被遗忘，尽管同一事件可能在其他来源（如维基百科）有事实描述。理想遗忘应移除新闻的具体表述，同时保留公开事实。为此，我们推出DUSK基准，专门评估现实数据重叠场景下的遗忘方法。DUSK构建了描述相同事实但风格各异的文档集，部分信息共享，其余内容独特。当某个集合被指定为遗忘对象时，优秀方法应移除其独特内容，同时保留共享事实。我们定义了七个评估指标，衡量遗忘方法的选择性移除能力。对九种最新遗忘方法的评估显示，现有技术在擦除深层语境知识方面存在关键局限，同时难以保护共享内容。我们公开DUSK作为基准，支持开发更精准可靠的遗忘技术，服务于现实应用。` `数据隐私` `数据处理`

> DUSK: Do Not Unlearn Shared Knowledge

# 摘要

> 大型语言模型（LLMs）在现实世界中的广泛应用引发担忧，未经授权的版权内容或敏感数据可能被滥用。机器遗忘技术旨在移除特定数据，同时保留其他信息。然而，现有评估往往假设遗忘和保留的数据完全独立，忽视了现实中它们可能共享内容的情况。例如，一篇新闻报道需被遗忘，尽管同一事件可能在其他来源（如维基百科）有事实描述。理想遗忘应移除新闻的具体表述，同时保留公开事实。为此，我们推出DUSK基准，专门评估现实数据重叠场景下的遗忘方法。DUSK构建了描述相同事实但风格各异的文档集，部分信息共享，其余内容独特。当某个集合被指定为遗忘对象时，优秀方法应移除其独特内容，同时保留共享事实。我们定义了七个评估指标，衡量遗忘方法的选择性移除能力。对九种最新遗忘方法的评估显示，现有技术在擦除深层语境知识方面存在关键局限，同时难以保护共享内容。我们公开DUSK作为基准，支持开发更精准可靠的遗忘技术，服务于现实应用。

> Large language models (LLMs) are increasingly deployed in real-world applications, raising concerns about the unauthorized use of copyrighted or sensitive data. Machine unlearning aims to remove such 'forget' data while preserving utility and information from the 'retain' set. However, existing evaluations typically assume that forget and retain sets are fully disjoint, overlooking realistic scenarios where they share overlapping content. For instance, a news article may need to be unlearned, even though the same event, such as an earthquake in Japan, is also described factually on Wikipedia. Effective unlearning should remove the specific phrasing of the news article while preserving publicly supported facts. In this paper, we introduce DUSK, a benchmark designed to evaluate unlearning methods under realistic data overlap. DUSK constructs document sets that describe the same factual content in different styles, with some shared information appearing across all sets and other content remaining unique to each. When one set is designated for unlearning, an ideal method should remove its unique content while preserving shared facts. We define seven evaluation metrics to assess whether unlearning methods can achieve this selective removal. Our evaluation of nine recent unlearning methods reveals a key limitation: while most can remove surface-level text, they often fail to erase deeper, context-specific knowledge without damaging shared content. We release DUSK as a public benchmark to support the development of more precise and reliable unlearning techniques for real-world applications.

[Arxiv](https://arxiv.org/abs/2505.15209)