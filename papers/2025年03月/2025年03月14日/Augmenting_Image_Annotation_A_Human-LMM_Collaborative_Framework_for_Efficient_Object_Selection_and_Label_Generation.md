# # 增强图像标注：一种人机协作框架，实现高效目标选择与标签生成

发布时间：2025年03月14日

`LLM应用` `计算机视觉` `数据标注`

> Augmenting Image Annotation: A Human-LMM Collaborative Framework for Efficient Object Selection and Label Generation

# 摘要

> 传统的图像标注任务依赖人工操作，流程耗时且效率低，尤其在标注人员疲劳时。本文提出了一种全新框架，利用大型多模态模型（LMMs）的视觉理解能力，特别是GPT，来辅助标注工作。在我们的方法中，标注人员只需通过边界框选择目标，而LMM自动生成标签。这种人机协作框架通过减轻标注人员负担，显著提高了效率。通过分析系统在目标识别、场景描述和细粒度分类等任务中的表现，我们展示了其强大的泛化能力。我们的框架不仅为计算机视觉中的大规模数据标注提供了一种高效解决方案，还突显了重新定义标注工作流程的潜力。最后，我们探讨了将LMMs整合到标注管道中如何促进人机双向对齐，以及在信息过载的情况下，如何通过AI分担部分工作来缓解“无尽标注”负担的挑战。

> Traditional image annotation tasks rely heavily on human effort for object selection and label assignment, making the process time-consuming and prone to decreased efficiency as annotators experience fatigue after extensive work. This paper introduces a novel framework that leverages the visual understanding capabilities of large multimodal models (LMMs), particularly GPT, to assist annotation workflows. In our proposed approach, human annotators focus on selecting objects via bounding boxes, while the LMM autonomously generates relevant labels. This human-AI collaborative framework enhances annotation efficiency by reducing the cognitive and time burden on human annotators. By analyzing the system's performance across various types of annotation tasks, we demonstrate its ability to generalize to tasks such as object recognition, scene description, and fine-grained categorization. Our proposed framework highlights the potential of this approach to redefine annotation workflows, offering a scalable and efficient solution for large-scale data labeling in computer vision. Finally, we discuss how integrating LMMs into the annotation pipeline can advance bidirectional human-AI alignment, as well as the challenges of alleviating the "endless annotation" burden in the face of information overload by shifting some of the work to AI.

[Arxiv](https://arxiv.org/abs/2503.11096)