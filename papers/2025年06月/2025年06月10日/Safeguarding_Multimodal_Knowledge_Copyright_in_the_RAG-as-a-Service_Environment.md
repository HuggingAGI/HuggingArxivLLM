# # 标题
保护多模态知识版权在 RAG 即服务环境下的方案

发布时间：2025年06月10日

`RAG` `版权保护` `多模态处理`

> Safeguarding Multimodal Knowledge Copyright in the RAG-as-a-Service Environment

# 摘要

> 随着检索增强生成（RAG）发展为服务导向型平台（Rag-as-a-Service），保护共享知识库中数据版权的重要性日益凸显。现有方法仅关注文本知识的水印保护，而图像知识的版权问题却被忽视。为此，我们提出了AQUA——首个专为多模态RAG系统设计的图像知识水印框架。AQUA采用两种互补方法：基于首字母缩写的触发器和空间关系提示，将语义信号嵌入合成图像。这些创新技术确保水印信号在从图像检索器到文本生成器的传播过程中保持稳定，同时具备高效、可靠且难以察觉的特点。实验结果表明，AQUA在多模态RAG保护中实现了稳健、隐蔽且可靠的版权追踪，填补了这一领域的关键空白。

> As Retrieval-Augmented Generation (RAG) evolves into service-oriented platforms (Rag-as-a-Service) with shared knowledge bases, protecting the copyright of contributed data becomes essential. Existing watermarking methods in RAG focus solely on textual knowledge, leaving image knowledge unprotected. In this work, we propose AQUA, the first watermark framework for image knowledge protection in Multimodal RAG systems. AQUA embeds semantic signals into synthetic images using two complementary methods: acronym-based triggers and spatial relationship cues. These techniques ensure watermark signals survive indirect watermark propagation from image retriever to textual generator, being efficient, effective and imperceptible. Experiments across diverse models and datasets show that AQUA enables robust, stealthy, and reliable copyright tracing, filling a key gap in multimodal RAG protection.

[Arxiv](https://arxiv.org/abs/2506.10030)