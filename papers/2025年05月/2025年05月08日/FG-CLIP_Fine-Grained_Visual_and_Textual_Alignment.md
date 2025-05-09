# FG-CLIP：精细视觉文本对齐

发布时间：2025年05月08日

`LLM应用` `计算机视觉` `多模态学习`

> FG-CLIP: Fine-Grained Visual and Textual Alignment

# 摘要

> 对比语言-图像预训练（CLIP）在图像-文本检索和零样本分类等多模态任务中表现出色，但在细粒度理解方面存在局限性，主要因其依赖于粗粒度的简短描述。为解决这一问题，我们提出了细粒度CLIP（FG-CLIP），通过三项创新提升细粒度理解能力。首先，利用大型多模态模型生成16亿个长描述-图像对，捕捉全局语义细节。其次，构建包含1200万张图像和4000万个区域特定边界框的高质量数据集，确保精准且内容丰富的表示。第三，引入1000万个困难细粒度负样本，增强模型区分细微语义差异的能力。针对这些数据，我们精心设计了训练方法。实验结果表明，FG-CLIP在细粒度理解、开放词汇目标检测、图像-文本检索及通用多模态基准测试中均优于原始CLIP和其他先进方法。这些结果凸显了FG-CLIP在捕捉细粒度图像细节和提升整体模型性能方面的有效性。相关数据、代码和模型可在https://github.com/360CVGroup/FG-CLIP获取。

> Contrastive Language-Image Pre-training (CLIP) excels in multimodal tasks such as image-text retrieval and zero-shot classification but struggles with fine-grained understanding due to its focus on coarse-grained short captions. To address this, we propose Fine-Grained CLIP (FG-CLIP), which enhances fine-grained understanding through three key innovations. First, we leverage large multimodal models to generate 1.6 billion long caption-image pairs for capturing global-level semantic details. Second, a high-quality dataset is constructed with 12 million images and 40 million region-specific bounding boxes aligned with detailed captions to ensure precise, context-rich representations. Third, 10 million hard fine-grained negative samples are incorporated to improve the model's ability to distinguish subtle semantic differences. Corresponding training methods are meticulously designed for these data. Extensive experiments demonstrate that FG-CLIP outperforms the original CLIP and other state-of-the-art methods across various downstream tasks, including fine-grained understanding, open-vocabulary object detection, image-text retrieval, and general multimodal benchmarks. These results highlight FG-CLIP's effectiveness in capturing fine-grained image details and improving overall model performance. The related data, code, and models are available at https://github.com/360CVGroup/FG-CLIP.

[Arxiv](https://arxiv.org/abs/2505.05071)