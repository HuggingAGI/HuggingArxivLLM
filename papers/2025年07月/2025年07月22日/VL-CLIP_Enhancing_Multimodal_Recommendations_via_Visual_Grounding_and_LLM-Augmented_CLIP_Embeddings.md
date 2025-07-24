# VL-CLIP: 结合视觉定位与 LLM 增强的 CLIP 嵌入提升多模态推荐效果

发布时间：2025年07月22日

`LLM应用` `多模态推荐`

> VL-CLIP: Enhancing Multimodal Recommendations via Visual Grounding and LLM-Augmented CLIP Embeddings

# 摘要

> 多模态学习在现代电商推荐平台中至关重要，它能够实现精准的商品推荐和深入的产品理解。然而，现有的视觉-语言模型（如CLIP）在电商推荐系统中面临三大核心挑战：1）对象级别对齐较弱，全局图像嵌入未能捕捉到细粒度的产品属性，导致检索效果不佳；2）文本表示模糊，商品描述常缺乏上下文清晰度，影响跨模态匹配；3）领域不匹配，通用视觉-语言模型可能无法很好地泛化到特定的电商数据。为了解决这些问题，我们提出了一种名为VL-CLIP的框架，通过整合视觉定位实现细粒度视觉理解，并结合基于LLM的代理生成增强文本嵌入，从而提升CLIP的嵌入效果。视觉定位通过定位关键产品来优化图像表示，而LLM代理则通过澄清商品描述来增强文本特征。我们的方法在美国最大的电子商务平台之一上显著提升了数千万商品的检索准确率、多模态检索效果和推荐质量，提升了18.6%的点击率（CTR）、15.5%的加入购物车率（ATC）以及4.0%的商品交易总额（GMV）。额外的实验结果表明，与包括CLIP、FashionCLIP和GCL在内的视觉-语言模型相比，我们的框架在精确度和语义对齐方面表现更优，证明了结合对象感知的视觉定位和LLM增强文本表示对于稳健的多模态推荐具有巨大潜力。

> Multimodal learning plays a critical role in e-commerce recommendation platforms today, enabling accurate recommendations and product understanding. However, existing vision-language models, such as CLIP, face key challenges in e-commerce recommendation systems: 1) Weak object-level alignment, where global image embeddings fail to capture fine-grained product attributes, leading to suboptimal retrieval performance; 2) Ambiguous textual representations, where product descriptions often lack contextual clarity, affecting cross-modal matching; and 3) Domain mismatch, as generic vision-language models may not generalize well to e-commerce-specific data. To address these limitations, we propose a framework, VL-CLIP, that enhances CLIP embeddings by integrating Visual Grounding for fine-grained visual understanding and an LLM-based agent for generating enriched text embeddings. Visual Grounding refines image representations by localizing key products, while the LLM agent enhances textual features by disambiguating product descriptions. Our approach significantly improves retrieval accuracy, multimodal retrieval effectiveness, and recommendation quality across tens of millions of items on one of the largest e-commerce platforms in the U.S., increasing CTR by 18.6%, ATC by 15.5%, and GMV by 4.0%. Additional experimental results show that our framework outperforms vision-language models, including CLIP, FashionCLIP, and GCL, in both precision and semantic alignment, demonstrating the potential of combining object-aware visual grounding and LLM-enhanced text representation for robust multimodal recommendations.

[Arxiv](https://arxiv.org/abs/2507.17080)