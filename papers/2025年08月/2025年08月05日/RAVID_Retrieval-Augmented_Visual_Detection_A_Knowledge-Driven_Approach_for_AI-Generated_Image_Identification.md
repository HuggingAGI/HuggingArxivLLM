# RAVID：检索增强视觉检测：一种用于识别AI生成图像的知识驱动方法

发布时间：2025年08月05日

`RAG` `图像生成检测` `计算机视觉`

> RAVID: Retrieval-Augmented Visual Detection: A Knowledge-Driven Approach for AI-Generated Image Identification

# 摘要

> 本文提出了RAVID——首个基于视觉检索增强生成（RAG）技术的AI生成图像检测框架。尽管RAG方法在降低基础模型的事实错误方面展现出潜力，但它们主要集中在文本领域，视觉知识的探索仍显不足。与此同时，现有的检测方法普遍依赖于低级图像特征和模型特定属性，导致泛化能力和鲁棒性不足。为了解决这些问题，RAVID通过动态检索相关图像来增强检测能力。

我们的方法采用了经过微调的CLIP图像编码器——RAVID CLIP，并通过加入类别相关的提示词，提升了表示学习的效果。此外，我们还引入了视觉-语言模型（VLM），将检索到的图像与查询图像相结合，形成更丰富的输入，从而提高检测精度。当输入一张待检测图像时，RAVID首先通过RAVID CLIP生成图像嵌入，然后从数据库中检索出最相关的图像，并将这些图像与待检测图像融合，形成增强后的输入供VLM（如Qwen-VL或Openflamingo）处理。

在涵盖19种生成模型的UniversalFakeDetect基准测试中，RAVID达到了93.85%的平均准确率，创下当前最优成绩。此外，RAVID在图像降质（如高斯模糊和JPEG压缩）条件下的鲁棒性表现同样出色，平均准确率达到80.27%，显著优于当前最优模型C2P-CLIP的63.44%。无论是高斯模糊还是JPEG压缩场景，RAVID都展现了稳定的性能提升。本研究的代码将在论文接收后公开发布。

> In this paper, we introduce RAVID, the first framework for AI-generated image detection that leverages visual retrieval-augmented generation (RAG). While RAG methods have shown promise in mitigating factual inaccuracies in foundation models, they have primarily focused on text, leaving visual knowledge underexplored. Meanwhile, existing detection methods, which struggle with generalization and robustness, often rely on low-level artifacts and model-specific features, limiting their adaptability. To address this, RAVID dynamically retrieves relevant images to enhance detection. Our approach utilizes a fine-tuned CLIP image encoder, RAVID CLIP, enhanced with category-related prompts to improve representation learning. We further integrate a vision-language model (VLM) to fuse retrieved images with the query, enriching the input and improving accuracy. Given a query image, RAVID generates an embedding using RAVID CLIP, retrieves the most relevant images from a database, and combines these with the query image to form an enriched input for a VLM (e.g., Qwen-VL or Openflamingo). Experiments on the UniversalFakeDetect benchmark, which covers 19 generative models, show that RAVID achieves state-of-the-art performance with an average accuracy of 93.85%. RAVID also outperforms traditional methods in terms of robustness, maintaining high accuracy even under image degradations such as Gaussian blur and JPEG compression. Specifically, RAVID achieves an average accuracy of 80.27% under degradation conditions, compared to 63.44% for the state-of-the-art model C2P-CLIP, demonstrating consistent improvements in both Gaussian blur and JPEG compression scenarios. The code will be publicly available upon acceptance.

[Arxiv](https://arxiv.org/abs/2508.03967)