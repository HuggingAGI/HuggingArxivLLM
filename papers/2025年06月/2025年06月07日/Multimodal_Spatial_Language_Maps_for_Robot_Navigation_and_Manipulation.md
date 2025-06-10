# 多模态空间语言地图助力机器人导航与操作

发布时间：2025年06月07日

`Agent` `机器人导航` `多模态`

> Multimodal Spatial Language Maps for Robot Navigation and Manipulation

# 摘要

> 将语言与导航代理的观察结果相结合，可以利用预训练的多模态基础模型，将感知与物体或事件描述相匹配。然而，之前的方法在与环境地图的结合上仍显不足，缺乏几何地图的空间精度，或者忽视了视觉之外的其他模态信息。为了解决这些问题，我们提出了多模态空间语言地图作为一种空间地图表示，它融合了预训练的多模态特征与环境的三维重建。我们通过标准探索自主构建这些地图。我们展示了两种地图实例，即视觉-语言地图（VLMaps）及其扩展到音频-视觉-语言地图（AVLMaps），后者通过添加音频信息获得。当与大型语言模型（LLMs）结合时，VLMaps可以（i）将自然语言指令直接定位在地图上的开放词汇空间目标（例如，“在沙发和电视之间”），以及（ii）在不同机器人形态之间共享，按需生成定制的障碍物地图。在此基础上，AVLMaps通过融合预训练多模态基础模型的特征，引入了一种统一的三维空间表示，整合了音频、视觉和语言线索。这使机器人能够将多模态目标查询（例如文本、图像或音频片段）定位到导航空间位置。此外，结合多样化的感官输入在模糊环境中显著提高了目标消歧能力。在模拟和现实环境中的实验表明，我们的多模态空间语言地图实现了零样本空间和多模态目标导航，并在模糊场景中将召回率提高了50%。这些能力扩展到了移动机器人和桌面操作器，支持基于视觉、音频和空间线索的导航和交互。


> Grounding language to a navigating agent's observations can leverage pretrained multimodal foundation models to match perceptions to object or event descriptions. However, previous approaches remain disconnected from environment mapping, lack the spatial precision of geometric maps, or neglect additional modality information beyond vision. To address this, we propose multimodal spatial language maps as a spatial map representation that fuses pretrained multimodal features with a 3D reconstruction of the environment. We build these maps autonomously using standard exploration. We present two instances of our maps, which are visual-language maps (VLMaps) and their extension to audio-visual-language maps (AVLMaps) obtained by adding audio information. When combined with large language models (LLMs), VLMaps can (i) translate natural language commands into open-vocabulary spatial goals (e.g., "in between the sofa and TV") directly localized in the map, and (ii) be shared across different robot embodiments to generate tailored obstacle maps on demand. Building upon the capabilities above, AVLMaps extend VLMaps by introducing a unified 3D spatial representation integrating audio, visual, and language cues through the fusion of features from pretrained multimodal foundation models. This enables robots to ground multimodal goal queries (e.g., text, images, or audio snippets) to spatial locations for navigation. Additionally, the incorporation of diverse sensory inputs significantly enhances goal disambiguation in ambiguous environments. Experiments in simulation and real-world settings demonstrate that our multimodal spatial language maps enable zero-shot spatial and multimodal goal navigation and improve recall by 50% in ambiguous scenarios. These capabilities extend to mobile robots and tabletop manipulators, supporting navigation and interaction guided by visual, audio, and spatial cues.

[Arxiv](https://arxiv.org/abs/2506.06862)