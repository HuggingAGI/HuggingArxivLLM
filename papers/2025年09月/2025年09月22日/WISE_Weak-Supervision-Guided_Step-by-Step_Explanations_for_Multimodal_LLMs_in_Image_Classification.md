# WISE：弱监督引导的图像分类中多模态大型语言模型的逐步解释

发布时间：2025年09月22日

`LLM应用` `基础理论`

> WISE: Weak-Supervision-Guided Step-by-Step Explanations for Multimodal LLMs in Image Classification

# 摘要

> 多模态大型语言模型（MLLMs）在视觉-文本推理领域展现出巨大潜力，而多模态思维链（MCoT）提示法则显著提升了其可解释性。然而，现有MCoT方法依赖推理依据丰富的数据集，且多聚焦于对象间推理，却忽略了对图像分类而言至关重要的对象内理解。为填补这一空白，我们提出WISE——一种弱监督引导的逐步解释方法。它在弱监督条件下，将概念瓶颈模型（CBMs）的基于概念表示重构为简洁易懂的推理链，从而为任意图像分类数据集补充MCoTs。在十个数据集上的实验显示，我们生成的MCoTs不仅使可解释性提升37%，在微调MLLMs时还能显著提高分类准确率。我们的研究架起了基于概念的可解释性与生成式MCoT推理之间的桥梁，为增强MLLMs的细粒度视觉理解能力提供了可推广的框架。

> Multimodal Large Language Models (MLLMs) have shown promise in visual-textual reasoning, with Multimodal Chain-of-Thought (MCoT) prompting significantly enhancing interpretability. However, existing MCoT methods rely on rationale-rich datasets and largely focus on inter-object reasoning, overlooking the intra-object understanding crucial for image classification. To address this gap, we propose WISE, a Weak-supervision-guided Step-by-step Explanation method that augments any image classification dataset with MCoTs by reformulating the concept-based representations from Concept Bottleneck Models (CBMs) into concise, interpretable reasoning chains under weak supervision. Experiments across ten datasets show that our generated MCoTs not only improve interpretability by 37% but also lead to gains in classification accuracy when used to fine-tune MLLMs. Our work bridges concept-based interpretability and generative MCoT reasoning, providing a generalizable framework for enhancing MLLMs in fine-grained visual understanding.

[Arxiv](https://arxiv.org/abs/2509.17740)