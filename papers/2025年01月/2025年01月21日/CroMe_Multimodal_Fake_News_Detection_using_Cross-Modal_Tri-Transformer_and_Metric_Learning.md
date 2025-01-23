# CroMe: 基于跨模态三重Transformer与度量学习的多模态假新闻检测

发布时间：2025年01月21日

`LLM应用

**理由**：该论文主要讨论了利用大型语言模型（BLIP2）进行多模态假新闻检测的方法。虽然涉及多模态数据处理，但其核心在于利用LLM（BLIP2）进行文本和图像的联合表示学习，并将其应用于假新闻检测任务。因此，该论文应归类为**LLM应用**。` `新闻媒体` `信息安全`

> CroMe: Multimodal Fake News Detection using Cross-Modal Tri-Transformer and Metric Learning

# 摘要

> # 多模态假新闻检测
多模态假新闻检测近来备受瞩目。现有方法多依赖独立编码的单模态数据，未能充分利用先进技术捕捉模态内关系和整合模态间相似性的优势。为此，我们提出了跨模态三重Transformer和度量学习（CroMe）方法。CroMe采用带有冻结图像编码器和大型语言模型（BLIP2）的自举语言-图像预训练作为编码器，精准捕捉文本、图像及组合的图像-文本表示。度量学习模块通过代理锚点方法捕捉模态内关系，特征融合模块则利用跨模态和三重Transformer实现高效整合。最终，假新闻检测器通过分类器处理融合特征，预测内容真实性。实验表明，CroMe在多模态假新闻检测中表现卓越。

> Multimodal Fake News Detection has received increasing attention recently. Existing methods rely on independently encoded unimodal data and overlook the advantages of capturing intra-modality relationships and integrating inter-modal similarities using advanced techniques. To address these issues, Cross-Modal Tri-Transformer and Metric Learning for Multimodal Fake News Detection (CroMe) is proposed. CroMe utilizes Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models (BLIP2) as encoders to capture detailed text, image and combined image-text representations. The metric learning module employs a proxy anchor method to capture intra-modality relationships while the feature fusion module uses a Cross-Modal and Tri-Transformer for effective integration. The final fake news detector processes the fused features through a classifier to predict the authenticity of the content. Experiments on datasets show that CroMe excels in multimodal fake news detection.

[Arxiv](https://arxiv.org/abs/2501.12422)