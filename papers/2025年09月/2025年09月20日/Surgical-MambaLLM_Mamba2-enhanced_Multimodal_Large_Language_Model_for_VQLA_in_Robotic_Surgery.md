# Surgical-MambaLLM：基于Mamba2增强的机器人手术VQLA多模态大语言模型

发布时间：2025年09月20日

`LLM应用` `医疗健康`

> Surgical-MambaLLM: Mamba2-enhanced Multimodal Large Language Model for VQLA in Robotic Surgery

# 摘要

> 近年来，机器人手术领域的视觉问题定位回答技术（Surgical-VQLA）因其能助力医学生和初级医生理解手术场景，备受关注。近来，大型语言模型（LLMs）的迅猛发展为此任务带来了更具潜力的解决方案。但现有方法在构建文本与视觉细节间的复杂关联、感知手术场景空间信息方面仍存在不足。为此，我们提出全新方法Surgical-MambaLLM，它开创性地在手术领域将Mamba2与LLM融合，借助Mamba2捕捉跨模态依赖、感知手术场景空间信息的优势，提升LLMs对手术图像的理解能力。具体来说，我们设计了跨模态双向Mamba2集成（CBMI）模块，借助Mamba2的跨模态整合能力，实现高效的多模态融合。同时，结合手术场景的几何特性，我们为Mamba2定制了手术器械感知（SIP）扫描模式，通过扫描手术图像提升模型对手术场景的空间认知。大量实验验证，我们的Surgical-MambaLLM模型在EndoVis17-VQLA和EndoVis18-VQLA数据集上性能超越现有最优方法，大幅提升了Surgical-VQLA任务的表现。

> In recent years, Visual Question Localized-Answering in robotic surgery (Surgical-VQLA) has gained significant attention for its potential to assist medical students and junior doctors in understanding surgical scenes. Recently, the rapid development of Large Language Models (LLMs) has provided more promising solutions for this task. However, current methods struggle to establish complex dependencies between text and visual details, and have difficulty perceiving the spatial information of surgical scenes. To address these challenges, we propose a novel method, Surgical-MambaLLM, which is the first to combine Mamba2 with LLM in the surgical domain, that leverages Mamba2's ability to effectively capture cross-modal dependencies and perceive spatial information in surgical scenes, thereby enhancing the LLMs' understanding of surgical images. Specifically, we propose the Cross-modal Bidirectional Mamba2 Integration (CBMI) module to leverage Mamba2 for effective multimodal fusion, with its cross-modal integration capabilities. Additionally, tailored to the geometric characteristics of surgical scenes, we design the Surgical Instrument Perception (SIP) scanning mode for Mamba2 to scan the surgical images, enhancing the model's spatial understanding of the surgical scene. Extensive experiments demonstrate that our Surgical-MambaLLM model outperforms the state-of-the-art methods on the EndoVis17-VQLA and EndoVis18-VQLA datasets, significantly improving the performance of the Surgical-VQLA task.

[Arxiv](https://arxiv.org/abs/2509.16618)