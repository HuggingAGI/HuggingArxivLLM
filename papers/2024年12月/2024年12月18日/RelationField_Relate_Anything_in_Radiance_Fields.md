# RelationField：于辐射场中关联一切

发布时间：2024年12月18日

`LLM应用` `3D 场景` `计算机视觉`

> RelationField: Relate Anything in Radiance Fields

# 摘要

> 神经辐射场作为新兴的 3D 场景表示，近来甚至能通过从视觉语言模型提炼开放词汇特征来学习场景理解的特性。然而，当下的方法主要聚焦于以对象为核心的表示，支持对象分割或检测，对象间语义关系的理解却大多未被探究。为弥补这一差距，我们提出了 RelationField，这是首个直接从神经辐射场提取对象间关系的方法。RelationField 将对象间关系表示为神经辐射场内的射线对，有效拓展其公式以涵盖隐式关系查询。为让 RelationField 学会复杂、开放词汇的关系，从多模态 LLM 中提炼关系知识。为评估 RelationField，我们解决了开放词汇 3D 场景图生成任务和关系引导的实例分割，在这两项任务中均达成了最先进的性能。详见项目网站 https://relationfield.github.io 。

> Neural radiance fields are an emerging 3D scene representation and recently even been extended to learn features for scene understanding by distilling open-vocabulary features from vision-language models. However, current method primarily focus on object-centric representations, supporting object segmentation or detection, while understanding semantic relationships between objects remains largely unexplored. To address this gap, we propose RelationField, the first method to extract inter-object relationships directly from neural radiance fields. RelationField represents relationships between objects as pairs of rays within a neural radiance field, effectively extending its formulation to include implicit relationship queries. To teach RelationField complex, open-vocabulary relationships, relationship knowledge is distilled from multi-modal LLMs. To evaluate RelationField, we solve open-vocabulary 3D scene graph generation tasks and relationship-guided instance segmentation, achieving state-of-the-art performance in both tasks. See the project website at https://relationfield.github.io.

[Arxiv](https://arxiv.org/abs/2412.13652)