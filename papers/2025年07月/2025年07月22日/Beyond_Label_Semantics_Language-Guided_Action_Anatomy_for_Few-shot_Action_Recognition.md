# 超越标签语义：基于语言引导的动作解构助力少量样本动作识别

发布时间：2025年07月22日

`LLM应用` `计算机视觉` `多模态学习`

> Beyond Label Semantics: Language-Guided Action Anatomy for Few-shot Action Recognition

# 摘要

> 小样本动作识别（FSAR）的目标是仅使用少量标注样本对视频中的动作进行分类。由于训练数据稀缺，近期研究开始引入文本等额外模态。然而，动作分类中姿势、运动动态及物体交互等细微变化是关键先验知识，仅靠标签无法完全挖掘。本文提出语言引导动作解构（LGA），超越标签语义，利用大型语言模型（LLMs）解构隐藏在动作标签下的核心特性。通过LLM的先验知识，LGA在小样本场景下能有效捕获时空线索。具体而言，文本方面引导LLM将标签分解为原子动作描述序列，重点关注主体、动作、物体三个要素。视频方面通过视觉解构模块分割为原子阶段，捕获动作序列结构。细粒度融合策略整合文本和视觉特征生成更具泛化的原型。最后，多模态匹配机制（包含视频-视频和视频-文本匹配）确保分类稳健性。实验表明，LGA在多个FSAR基准上均达到前沿水准。

> Few-shot action recognition (FSAR) aims to classify human actions in videos with only a small number of labeled samples per category. The scarcity of training data has driven recent efforts to incorporate additional modalities, particularly text. However, the subtle variations in human posture, motion dynamics, and the object interactions that occur during different phases, are critical inherent knowledge of actions that cannot be fully exploited by action labels alone. In this work, we propose Language-Guided Action Anatomy (LGA), a novel framework that goes beyond label semantics by leveraging Large Language Models (LLMs) to dissect the essential representational characteristics hidden beneath action labels. Guided by the prior knowledge encoded in LLM, LGA effectively captures rich spatiotemporal cues in few-shot scenarios. Specifically, for text, we prompt an off-the-shelf LLM to anatomize labels into sequences of atomic action descriptions, focusing on the three core elements of action (subject, motion, object). For videos, a Visual Anatomy Module segments actions into atomic video phases to capture the sequential structure of actions. A fine-grained fusion strategy then integrates textual and visual features at the atomic level, resulting in more generalizable prototypes. Finally, we introduce a Multimodal Matching mechanism, comprising both video-video and video-text matching, to ensure robust few-shot classification. Experimental results demonstrate that LGA achieves state-of-the-art performance across multipe FSAR benchmarks.

[Arxiv](https://arxiv.org/abs/2507.16287)