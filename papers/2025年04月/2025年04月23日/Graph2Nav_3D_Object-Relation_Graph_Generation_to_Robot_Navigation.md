# Graph2Nav：三维物体关系图生成技术应用于机器人导航

发布时间：2025年04月23日

`Agent

理由：这篇论文主要讨论了一个实时3D对象关系图生成框架Graph2Nav，用于自主导航。虽然提到了与大型语言模型SayNav的集成，但论文的核心在于3D场景图的生成和应用，属于智能体和自主导航的范畴。因此，归类为Agent。` `机器人` `计算机视觉`

> Graph2Nav: 3D Object-Relation Graph Generation to Robot Navigation

# 摘要

> 我们提出了一个实时3D对象关系图生成框架——Graph2Nav，用于实现现实世界的自主导航。该框架在3D分层场景图中完整生成并充分利用3D对象及其丰富的语义关系，支持室内外场景。通过结合并优化现有的2D全景场景图研究成果，并借助3D语义映射技术将其拓展至3D空间，Graph2Nav能够学习生成3D对象间的语义关系，从而突破传统方法直接从3D数据学习场景图的训练数据限制。实验验证了我们的3D场景图在对象定位和关系标注上的准确性。此外，我们将Graph2Nav与基于大型语言模型的先进规划器SayNav集成，应用于无人地面机器人在真实环境中的对象搜索任务。实验结果表明，Graph2Nav通过场景图建模对象关系的方法能够显著提升导航任务中的搜索效率。

> We propose Graph2Nav, a real-time 3D object-relation graph generation framework, for autonomous navigation in the real world. Our framework fully generates and exploits both 3D objects and a rich set of semantic relationships among objects in a 3D layered scene graph, which is applicable to both indoor and outdoor scenes. It learns to generate 3D semantic relations among objects, by leveraging and advancing state-of-the-art 2D panoptic scene graph works into the 3D world via 3D semantic mapping techniques. This approach avoids previous training data constraints in learning 3D scene graphs directly from 3D data. We conduct experiments to validate the accuracy in locating 3D objects and labeling object-relations in our 3D scene graphs. We also evaluate the impact of Graph2Nav via integration with SayNav, a state-of-the-art planner based on large language models, on an unmanned ground robot to object search tasks in real environments. Our results demonstrate that modeling object relations in our scene graphs improves search efficiency in these navigation tasks.

[Arxiv](https://arxiv.org/abs/2504.16782)