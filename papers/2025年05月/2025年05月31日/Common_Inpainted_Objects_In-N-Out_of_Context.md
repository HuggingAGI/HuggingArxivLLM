# # 上下文内外的常见图像修复对象

发布时间：2025年05月31日

`其他` `计算机视觉` `图像处理`

> Common Inpainted Objects In-N-Out of Context

# 摘要

> 我们提出了“上下文内外通用修复物体数据集”（COinCO），一个解决现有视觉数据集缺乏出上下文示例问题的创新数据集。通过系统性地利用扩散式图像修复技术替换COCO图像中的物体，我们生成了97,722张独特图像，涵盖上下文一致与不一致的场景，从而实现有效的上下文学习。每个修复的物体都经过多模态大语言模型的细致评估，被分类为“在上下文内”或“出上下文”。我们的分析揭示了影响不同物体类别修复成功的语义先验模式。COinCO支持三个关键任务：（1）训练上下文分类器，有效判断现有物体是否属于其所在上下文；（2）一种新型的“基于上下文的物体预测”任务，确定哪些新物体自然属于给定场景，涵盖实例和群体两个层面；（3）在无需微调的情况下，增强上下文的假图像检测能力。COinCO提供了一个带有上下文变化的受控测试环境，为推动计算机视觉和图像取证领域的上下文感知视觉理解奠定了基础。我们的代码和数据已开源：https://github.com/YangTianze009/COinCO。

> We present Common Inpainted Objects In-N-Out of Context (COinCO), a novel dataset addressing the scarcity of out-of-context examples in existing vision datasets. By systematically replacing objects in COCO images through diffusion-based inpainting, we create 97,722 unique images featuring both contextually coherent and inconsistent scenes, enabling effective context learning. Each inpainted object is meticulously verified and categorized as in- or out-of-context through a multimodal large language model assessment. Our analysis reveals significant patterns in semantic priors that influence inpainting success across object categories. We demonstrate three key tasks enabled by COinCO: (1) training context classifiers that effectively determine whether existing objects belong in their context; (2) a novel Objects-from-Context prediction task that determines which new objects naturally belong in given scenes at both instance and clique levels, and (3) context-enhanced fake detection on state-of-the-art methods without fine-tuning. COinCO provides a controlled testbed with contextual variations, establishing a foundation for advancing context-aware visual understanding in computer vision and image forensics. Our code and data are at: https://github.com/YangTianze009/COinCO.

[Arxiv](https://arxiv.org/abs/2506.00721)