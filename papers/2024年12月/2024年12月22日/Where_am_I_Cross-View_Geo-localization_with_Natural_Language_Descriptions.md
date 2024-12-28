# 我身处何方？利用自然语言描述的跨视图地理定位

发布时间：2024年12月22日

`其他` `地理定位` `行人导航`

> Where am I? Cross-View Geo-localization with Natural Language Descriptions

# 摘要

> 跨视图地理定位通过将街景图像与带有地理标签的卫星图像或 OSM 相匹配，来确定街景图像的位置。然而，多数研究聚焦于图像到图像的检索，较少关注文本引导的检索，而这对于行人导航和应急响应等应用至关重要。在本项工作中，我们引入了一个带有自然语言描述的跨视图地理定位新任务，旨在依据场景文本检索对应的卫星图像或 OSM 数据库。为支撑此任务，我们通过从多个城市收集跨视图数据，并运用一种借助大型多模态模型注释能力来生成含定位细节的高质量场景文本描述的场景文本生成方法，构建了 CVG-Text 数据集。另外，我们提出了一种新颖的基于文本的检索定位方法 CrossText2Loc，它将召回率提升了 10%，并展现出卓越的长文本检索能力。在可解释性方面，它不但提供相似性分数，还给出检索理由。更多信息可在 https://yejy53.github.io/CVG-Text/ 查阅。

> Cross-view geo-localization identifies the locations of street-view images by matching them with geo-tagged satellite images or OSM. However, most studies focus on image-to-image retrieval, with fewer addressing text-guided retrieval, a task vital for applications like pedestrian navigation and emergency response. In this work, we introduce a novel task for cross-view geo-localization with natural language descriptions, which aims to retrieve corresponding satellite images or OSM database based on scene text. To support this task, we construct the CVG-Text dataset by collecting cross-view data from multiple cities and employing a scene text generation approach that leverages the annotation capabilities of Large Multimodal Models to produce high-quality scene text descriptions with localization details.Additionally, we propose a novel text-based retrieval localization method, CrossText2Loc, which improves recall by 10% and demonstrates excellent long-text retrieval capabilities. In terms of explainability, it not only provides similarity scores but also offers retrieval reasons. More information can be found at https://yejy53.github.io/CVG-Text/.

[Arxiv](https://arxiv.org/abs/2412.17007)