# # 分层LLM提示优化新闻推荐

发布时间：2025年04月29日

`LLM应用` `新闻推荐`

> Enhancing News Recommendation with Hierarchical LLM Prompting

# 摘要

> 个性化新闻推荐系统常因依赖浅层表征（如文章标题和摘要）而难以有效捕捉用户偏好的复杂性。为解决这一难题，我们提出了一种名为PNR-LLM的创新方法，即用于个性化新闻推荐的大型语言模型。PNR-LLM通过利用LLMs的生成能力，丰富新闻标题和摘要，从而提升推荐质量。其核心模块“News Enrichment via LLMs”可从文章中提取更深层的语义信息和相关实体，将浅层内容转化为更丰富的表示。我们还设计了一种注意力机制，用于聚合增强的语义和实体级别数据，形成统一的用户和新闻嵌入，从而实现更精准的用户-新闻匹配。在MIND数据集上的大量实验表明，PNR-LLM显著优于现有最先进的基线方法。此外，我们的数据增强模块具有通用性，实证结果表明将其应用于多个现有模型可进一步提升性能，充分验证了我们的设计优势。

> Personalized news recommendation systems often struggle to effectively capture the complexity of user preferences, as they rely heavily on shallow representations, such as article titles and abstracts. To address this problem, we introduce a novel method, namely PNR-LLM, for Large Language Models for Personalized News Recommendation. Specifically, PNR-LLM harnesses the generation capabilities of LLMs to enrich news titles and abstracts, and consequently improves recommendation quality. PNR-LLM contains a novel module, News Enrichment via LLMs, which generates deeper semantic information and relevant entities from articles, transforming shallow contents into richer representations. We further propose an attention mechanism to aggregate enriched semantic- and entity-level data, forming unified user and news embeddings that reveal a more accurate user-news match. Extensive experiments on MIND datasets show that PNR-LLM outperforms state-of-the-art baselines. Moreover, the proposed data enrichment module is model-agnostic, and we empirically show that applying our proposed module to multiple existing models can further improve their performance, verifying the advantage of our design.

[Arxiv](https://arxiv.org/abs/2504.20452)