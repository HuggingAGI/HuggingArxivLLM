# 基于增强型大型语言模型的多模态融合跨域序列推荐

发布时间：2025年06月22日

`LLM应用

摘要讨论了跨领域序列推荐系统，其中使用了大语言模型来增强推荐效果。这属于将LLM技术应用于特定领域（推荐系统）的范畴，因此归类为LLM应用。` `电子商务`

> LLM-Enhanced Multimodal Fusion for Cross-Domain Sequential Recommendation

# 摘要

> 跨领域序列推荐（CDSR）通过分析多领域的历史交互数据来预测用户行为，重点在于建模跨领域偏好并捕捉项目间的复杂关系。我们提出了一种创新的高级方法——基于大语言模型的多模态融合增强跨领域序列推荐（LLM-EMF）。该方法利用大语言模型的知识增强文本信息，并通过视觉与文本数据的融合显著提升推荐效果。借助冻结的CLIP模型，我们生成图像和文本嵌入，从而通过多模态数据丰富项目表示。独特的多注意力机制同时捕捉单领域和跨领域的用户偏好，精准理解用户在不同领域中的复杂兴趣。在四个电子商务数据集上的实验表明，LLM-EMF在跨领域用户偏好建模方面表现卓越，充分证明了多模态数据整合的优势及其对增强序列推荐系统的价值。我们的源代码即将开源。

> Cross-Domain Sequential Recommendation (CDSR) predicts user behavior by leveraging historical interactions across multiple domains, focusing on modeling cross-domain preferences and capturing both intra- and inter-sequence item relationships. We propose LLM-Enhanced Multimodal Fusion for Cross-Domain Sequential Recommendation (LLM-EMF), a novel and advanced approach that enhances textual information with Large Language Models (LLM) knowledge and significantly improves recommendation performance through the fusion of visual and textual data. Using the frozen CLIP model, we generate image and text embeddings, thereby enriching item representations with multimodal data. A multiple attention mechanism jointly learns both single-domain and cross-domain preferences, effectively capturing and understanding complex user interests across diverse domains. Evaluations conducted on four e-commerce datasets demonstrate that LLM-EMF consistently outperforms existing methods in modeling cross-domain user preferences, thereby highlighting the effectiveness of multimodal data integration and its advantages in enhancing sequential recommendation systems. Our source code will be released.

[Arxiv](https://arxiv.org/abs/2506.17966)