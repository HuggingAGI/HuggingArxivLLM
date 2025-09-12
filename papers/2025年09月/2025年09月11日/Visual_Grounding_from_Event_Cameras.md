# 事件相机的视觉定位

发布时间：2025年09月11日

`其他` `交通运输`

> Visual Grounding from Event Cameras

# 摘要

> 事件相机能以微秒级精度捕捉亮度变化，即便在运动模糊和复杂光照条件下也依然可靠，为建模高度动态场景带来显著优势。但它们与自然语言理解的融合却鲜少受到关注，这在多模态感知领域留下了空白。为此，我们提出Talk2Event——首个基于事件数据的语言驱动目标定位大规模基准数据集。该数据集基于真实驾驶场景构建，包含5567个场景、13458个标注目标以及3万余条经过严格验证的指代表达式。每条表达式均包含四种结构化属性——外观、状态、与观察者的关系及与周围物体的关系，可清晰捕捉空间、时间及关系线索。这种以属性为核心的设计支持可解释的组合式定位，能将分析从简单的目标识别提升到动态环境中的上下文推理层面。我们期望Talk2Event能成为推动多模态与时间感知能力发展的基石，其应用领域将涵盖机器人技术、人机交互等。

> Event cameras capture changes in brightness with microsecond precision and remain reliable under motion blur and challenging illumination, offering clear advantages for modeling highly dynamic scenes. Yet, their integration with natural language understanding has received little attention, leaving a gap in multimodal perception. To address this, we introduce Talk2Event, the first large-scale benchmark for language-driven object grounding using event data. Built on real-world driving scenarios, Talk2Event comprises 5,567 scenes, 13,458 annotated objects, and more than 30,000 carefully validated referring expressions. Each expression is enriched with four structured attributes -- appearance, status, relation to the viewer, and relation to surrounding objects -- that explicitly capture spatial, temporal, and relational cues. This attribute-centric design supports interpretable and compositional grounding, enabling analysis that moves beyond simple object recognition to contextual reasoning in dynamic environments. We envision Talk2Event as a foundation for advancing multimodal and temporally-aware perception, with applications spanning robotics, human-AI interaction, and so on.

[Arxiv](https://arxiv.org/abs/2509.09584)