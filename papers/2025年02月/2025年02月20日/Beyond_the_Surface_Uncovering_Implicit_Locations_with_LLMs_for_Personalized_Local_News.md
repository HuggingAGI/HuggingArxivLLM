# # 深入表面之下：借助大语言模型挖掘潜在位置信息，打造个性化本地新闻

发布时间：2025年02月20日

`LLM应用

摘要讨论了大型语言模型在新闻推荐系统中的应用，特别是用于本地文章分类，属于实际应用层面的研究。` `推荐系统`

> Beyond the Surface: Uncovering Implicit Locations with LLMs for Personalized Local News

# 摘要

> 新闻推荐系统通过个性化主页内容来提升用户互动，但内容类型、编辑立场和地理焦点等因素会影响推荐效果。地方报纸在报道中力求平衡各地覆盖，但识别本地文章颇具挑战，因为它们通常依赖于俚语或地标等隐含的地理位置线索。

    传统方法如命名实体识别（NER）和知识图谱用于推断地理位置，但大型语言模型（LLMs）为这一领域带来了新的可能性，同时也引发了对准确性和可解释性的担忧。

    本文探讨了在Taboola的“为您推荐的主页”系统中使用LLMs进行本地文章分类，并将其与传统方法进行了对比。研究发现：（1）知识图谱能增强NER模型识别隐含地理位置的能力；（2）LLMs在分类效果上优于传统方法；（3）LLMs无需依赖知识图谱即可有效识别本地内容。

    离线评估显示LLMs在隐含地理位置分类上表现优异，而线上A/B测试则显示本地文章浏览量显著增加。一个集成LLM的地理位置分类系统实现了本地文章分发量27%的增长，既保持了报纸的品牌特色，又提升了主页个性化水平。
    

> News recommendation systems personalize homepage content to boost engagement, but factors like content type, editorial stance, and geographic focus impact recommendations. Local newspapers balance coverage across regions, yet identifying local articles is challenging due to implicit location cues like slang or landmarks.
  Traditional methods, such as Named Entity Recognition (NER) and Knowledge Graphs, infer locations, but Large Language Models (LLMs) offer new possibilities while raising concerns about accuracy and explainability.
  This paper explores LLMs for local article classification in Taboola's "Homepage For You" system, comparing them to traditional techniques. Key findings: (1) Knowledge Graphs enhance NER models' ability to detect implicit locations, (2) LLMs outperform traditional methods, and (3) LLMs can effectively identify local content without requiring Knowledge Graph integration.
  Offline evaluations showed LLMs excel at implicit location classification, while online A/B tests showed a significant increased in local views. A scalable pipeline integrating LLM-based location classification boosted local article distribution by 27%, preserving newspapers' brand identity and enhancing homepage personalization.

[Arxiv](https://arxiv.org/abs/2502.14660)