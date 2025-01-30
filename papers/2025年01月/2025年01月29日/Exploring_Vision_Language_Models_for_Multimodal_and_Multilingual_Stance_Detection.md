# 探索视觉语言模型在多模态和多语言立场检测中的应用

发布时间：2025年01月29日

`LLM应用

理由：这篇论文主要探讨了视觉-语言模型（VLMs）在多模态和多语言立场检测任务中的表现。虽然VLMs可以被视为一种特定类型的LLM（大型语言模型），但论文的重点在于这些模型在实际应用中的表现，特别是在多模态和多语言环境下的立场检测任务。因此，这篇论文更适合归类为“LLM应用”，而不是“LLM理论”或“Agent”。` `社交媒体`

> Exploring Vision Language Models for Multimodal and Multilingual Stance Detection

# 摘要

> # 摘要
社交媒体的全球影响力加速了信息传播，凸显了跨语言和多模态立场检测等自然语言处理任务的重要性。以往研究多集中于纯文本输入，而对图像和文本结合的多模态场景探索较少。近年来，多模态帖子日益流行。尽管先进的视觉-语言模型（VLMs）展现出潜力，但其在多模态和多语言立场检测任务中的表现仍鲜有研究。本文在一个涵盖七种语言和多模态输入的新扩展数据集上评估了最先进的VLMs，探讨了它们对视觉线索的利用、特定语言的性能以及跨模态交互。结果显示，VLMs在立场检测中更依赖文本而非图像，且这一趋势在不同语言中普遍存在。此外，VLMs更倾向于利用图像中的文本而非其他视觉内容。在多语言性方面，无论模型是否明确支持多语言，它们在不同语言中的预测结果通常一致，尽管存在与宏观F1、语言支持和模型大小不符的异常情况。

> Social media's global reach amplifies the spread of information, highlighting the need for robust Natural Language Processing tasks like stance detection across languages and modalities. Prior research predominantly focuses on text-only inputs, leaving multimodal scenarios, such as those involving both images and text, relatively underexplored. Meanwhile, the prevalence of multimodal posts has increased significantly in recent years. Although state-of-the-art Vision-Language Models (VLMs) show promise, their performance on multimodal and multilingual stance detection tasks remains largely unexamined. This paper evaluates state-of-the-art VLMs on a newly extended dataset covering seven languages and multimodal inputs, investigating their use of visual cues, language-specific performance, and cross-modality interactions. Our results show that VLMs generally rely more on text than images for stance detection and this trend persists across languages. Additionally, VLMs rely significantly more on text contained within the images than other visual content. Regarding multilinguality, the models studied tend to generate consistent predictions across languages whether they are explicitly multilingual or not, although there are outliers that are incongruous with macro F1, language support, and model size.

[Arxiv](https://arxiv.org/abs/2501.17654)