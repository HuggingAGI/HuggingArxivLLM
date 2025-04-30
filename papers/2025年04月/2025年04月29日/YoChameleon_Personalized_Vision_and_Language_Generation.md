# YoChameleon：个性化的视觉与语言生成系统

发布时间：2025年04月29日

`LLM应用

理由：这篇论文探讨了如何将个性化方法应用于大型多模态模型，特别是图像生成方面。它提出了一种新的方法Yo'Chameleon，用于在少量样本的情况下提升图像质量，并实现了多模态性能的平衡。这属于大型语言模型的应用层面，因此归类为LLM应用。` `图像生成` `个性化`

> YoChameleon: Personalized Vision and Language Generation

# 摘要

> 大型多模态模型（如GPT-4、Gemini、Chameleon）已发展为拥有数百万用户的强大工具。然而，这些模型仍然是通用模型，缺乏对特定用户概念的个性化知识。此前的研究探索了文本生成中的个性化方法，但如何将这些方法扩展到新的模态（如图像生成）仍不清楚。本文中，我们介绍了Yo'Chameleon，这是首个研究大型多模态模型个性化的方法。给定3-5张特定概念的图像，Yo'Chameleon利用软提示调优技术将特定主题的信息嵌入模型，从而实现（i）回答关于该主题的问题，以及（ii）在新场景中重现像素级细节以生成该主题的图像。Yo'Chameleon的训练采用了（i）一种自我提示优化机制，以平衡多模态性能；以及（ii）一种“软正向”图像生成方法，以在少量样本的情况下提升图像质量。

> Large Multimodal Models (e.g., GPT-4, Gemini, Chameleon) have evolved into powerful tools with millions of users. However, they remain generic models and lack personalized knowledge of specific user concepts. Previous work has explored personalization for text generation, yet it remains unclear how these methods can be adapted to new modalities, such as image generation. In this paper, we introduce Yo'Chameleon, the first attempt to study personalization for large multimodal models. Given 3-5 images of a particular concept, Yo'Chameleon leverages soft-prompt tuning to embed subject-specific information to (i) answer questions about the subject and (ii) recreate pixel-level details to produce images of the subject in new contexts. Yo'Chameleon is trained with (i) a self-prompting optimization mechanism to balance performance across multiple modalities, and (ii) a ``soft-positive" image generation approach to enhance image quality in a few-shot setting.

[Arxiv](https://arxiv.org/abs/2504.20998)