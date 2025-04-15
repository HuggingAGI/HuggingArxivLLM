# # GeoNav：赋能多语言大型语言模型，赋予其显式地理空间推理能力，实现语言目标空中导航

发布时间：2025年04月13日

`Agent

理由：这篇论文探讨了无人机导航中的智能体设计，专注于多模态智能体GeoNav在复杂环境中的应用，属于智能体（Agent）的研究范畴。` `无人机` `地理信息系统`

> GeoNav: Empowering MLLMs with Explicit Geospatial Reasoning Abilities for Language-Goal Aerial Navigation

# 摘要

> 基于语言目标的空中导航是具身AI中的重要挑战，要求无人机根据文本描述在复杂环境中准确定位目标。现有方法多基于室内导航迁移而来，受限于视野范围、语义歧义及缺乏结构化空间推理，难以有效扩展。为此，我们提出GeoNav——一个具备地理空间感知的多模态智能体，助力实现长距离导航。GeoNav采用三阶段策略：地标导航、目标搜索和精准定位，模仿人类从粗到细的空间推理方式。为支持这种推理，它动态构建两类地理空间记忆。第一类是全局性的认知地图，融合文本地理知识与视觉线索，形成自顶向下的标注化表征，用于快速导航至地标区域。第二类是局部的场景图，刻画街区、地标与物体间的层次化空间关系，用于精确目标定位。基于此结构化表征，GeoNav采用多模态空间感知链式推理机制，赋予模型跨阶段的高效可解释决策能力。在CityNav基准测试中，GeoNav的成功率较现有最优方法提升12.53%，显著提升导航效率，即便在困难任务中亦然。消融实验凸显各模块价值，证实地理空间表征和从粗到细的推理策略对提升无人机导航能力至关重要。

> Language-goal aerial navigation is a critical challenge in embodied AI, requiring UAVs to localize targets in complex environments such as urban blocks based on textual specification. Existing methods, often adapted from indoor navigation, struggle to scale due to limited field of view, semantic ambiguity among objects, and lack of structured spatial reasoning. In this work, we propose GeoNav, a geospatially aware multimodal agent to enable long-range navigation. GeoNav operates in three phases-landmark navigation, target search, and precise localization-mimicking human coarse-to-fine spatial strategies. To support such reasoning, it dynamically builds two different types of spatial memory. The first is a global but schematic cognitive map, which fuses prior textual geographic knowledge and embodied visual cues into a top-down, annotated form for fast navigation to the landmark region. The second is a local but delicate scene graph representing hierarchical spatial relationships between blocks, landmarks, and objects, which is used for definite target localization. On top of this structured representation, GeoNav employs a spatially aware, multimodal chain-of-thought prompting mechanism to enable multimodal large language models with efficient and interpretable decision-making across stages. On the CityNav urban navigation benchmark, GeoNav surpasses the current state-of-the-art by up to 12.53% in success rate and significantly improves navigation efficiency, even in hard-level tasks. Ablation studies highlight the importance of each module, showcasing how geospatial representations and coarse-to-fine reasoning enhance UAV navigation.

[Arxiv](https://arxiv.org/abs/2504.09587)