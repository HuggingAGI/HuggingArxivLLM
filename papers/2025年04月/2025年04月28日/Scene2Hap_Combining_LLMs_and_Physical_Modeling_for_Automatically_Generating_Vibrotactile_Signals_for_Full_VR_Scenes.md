# Scene2Hap：融合大型语言模型与物理建模，实现完整 VR 场景的振动触觉信号自动生成

发布时间：2025年04月28日

`LLM应用` `虚拟现实` `多模态`

> Scene2Hap: Combining LLMs and Physical Modeling for Automatically Generating Vibrotactile Signals for Full VR Scenes

# 摘要

> 触觉反馈是沉浸式虚拟现实（VR）体验的关键。然而，为VR场景中的所有对象及其布局设计触觉反馈仍是一项耗时的工作。我们推出了一款以大型语言模型（LLM）为核心的创新系统——Scene2Hap，它能够根据对象的语义特性和物理环境，自动为整个VR场景设计对象级的振动触觉反馈。Scene2Hap借助多模态大型语言模型，从VR场景的多模态信息中提取每个对象的语义和物理环境，包括其材料特性和振动行为。基于这些信息，系统通过生成或检索音频信号并将其转换为振动触觉信号，创建出逼真的触觉反馈。为了实现更真实的触觉空间渲染，Scene2Hap模拟了振动信号从其来源在场景中传播和衰减的过程，考虑了材料特性和物理环境因素，如虚拟对象之间的距离和接触。通过两项用户研究验证，Scene2Hap不仅成功捕捉了VR场景的语义和物理环境，其振动传播的物理建模还显著提升了用户的可用性、材质感知和空间意识。

> Haptic feedback contributes to immersive virtual reality (VR) experiences. Designing such feedback at scale, for all objects within a VR scene and their respective arrangements, remains a time-consuming task. We present Scene2Hap, an LLM-centered system that automatically designs object-level vibrotactile feedback for entire VR scenes based on the objects' semantic attributes and physical context. Scene2Hap employs a multimodal large language model to estimate the semantics and physical context of each object, including its material properties and vibration behavior, from the multimodal information present in the VR scene. This semantic and physical context is then used to create plausible vibrotactile signals by generating or retrieving audio signals and converting them to vibrotactile signals. For the more realistic spatial rendering of haptics in VR, Scene2Hap estimates the propagation and attenuation of vibration signals from their source across objects in the scene, considering the estimated material properties and physical context, such as the distance and contact between virtual objects. Results from two user studies confirm that Scene2Hap successfully estimates the semantics and physical context of VR scenes, and the physical modeling of vibration propagation improves usability, perceived materiality, and spatial awareness.

[Arxiv](https://arxiv.org/abs/2504.19611)