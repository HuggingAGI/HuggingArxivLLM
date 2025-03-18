# # 视觉与语言的融合：构建无文本多模态知识图谱，助力大语言模型推理能力提升

发布时间：2025年03月17日

`LLM应用` `多模态知识图谱` `大型语言模型`

> Aligning Vision to Language: Text-Free Multimodal Knowledge Graph Construction for Enhanced LLMs Reasoning

# 摘要

> 大型语言模型中的多模态推理面临知识不完整和幻觉 artifacts 的挑战，而文本知识图谱仅能部分缓解这些问题，因为它们存在模态隔离的局限性。尽管多模态知识图谱在跨模态理解方面展现出潜力，但其实际构建却因手动文本标注的语义狭窄性和视觉-语义实体链接中的固有噪声而受阻。在本文中，我们提出了 Vision-align-to-Language 集成知识图谱 (VaLiK)，这是一种构建 MMKGs 的新方法，通过跨模态信息补充来增强 LLMs 的推理能力。具体而言，我们级联预训练的视觉-语言模型 (VLMs) 以对齐图像特征与文本，将它们转换为包含图像特定信息的描述。此外，我们开发了一种跨模态相似性验证机制，用于量化语义一致性，有效过滤特征对齐过程中引入的噪声。即使没有人工标注的图像说明，经过优化的描述本身也足以构建 MMKG。与传统的 MMKGs 构建范式相比，我们的方法在保持直接的实体到图像链接能力的同时，实现了显著的存储效率提升。在多模态推理任务上的实验结果表明，增强 VaLiK 的 LLMs 在性能上超越了之前最先进的模型。我们的代码已发布在 https://github.com/Wings-Of-Disaster/VaLiK。


> Multimodal reasoning in Large Language Models (LLMs) struggles with incomplete knowledge and hallucination artifacts, challenges that textual Knowledge Graphs (KGs) only partially mitigate due to their modality isolation. While Multimodal Knowledge Graphs (MMKGs) promise enhanced cross-modal understanding, their practical construction is impeded by semantic narrowness of manual text annotations and inherent noise in visual-semantic entity linkages. In this paper, we propose Vision-align-to-Language integrated Knowledge Graph (VaLiK), a novel approach for constructing MMKGs that enhances LLMs reasoning through cross-modal information supplementation. Specifically, we cascade pre-trained Vision-Language Models (VLMs) to align image features with text, transforming them into descriptions that encapsulate image-specific information. Furthermore, we developed a cross-modal similarity verification mechanism to quantify semantic consistency, effectively filtering out noise introduced during feature alignment. Even without manually annotated image captions, the refined descriptions alone suffice to construct the MMKG. Compared to conventional MMKGs construction paradigms, our approach achieves substantial storage efficiency gains while maintaining direct entity-to-image linkage capability. Experimental results on multimodal reasoning tasks demonstrate that LLMs augmented with VaLiK outperform previous state-of-the-art models. Our code is published at https://github.com/Wings-Of-Disaster/VaLiK.

[Arxiv](https://arxiv.org/abs/2503.12972)