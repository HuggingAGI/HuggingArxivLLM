# KOALA：通过知识冲突增强提升视觉语言模型的稳健性

发布时间：2025年02月18日

`其他` `视觉语言模型` `多模态学习`

> KOALA: Knowledge Conflict Augmentations for Robustness in Vision Language Models

# 摘要

> 在单模态问答系统中，大型语言模型（LLMs）对抗知识冲突的鲁棒性已得到充分研究。然而，在多模态环境下，信息来源冲突对视觉语言模型（VLMs）的影响尚未被探索。本研究提出了一种名为\segsub的框架，通过向图像来源施加定向扰动，来研究并提升VLMs在参数冲突、来源冲突以及反事实冲突这三种不同知识冲突类型下的鲁棒性。与之前的研究结果相反，我们发现VLMs对源于文本扰动的参数冲突并不敏感。然而，VLMs在处理反事实示例时表现不佳（准确率低于30%），并且无法有效推理来源冲突（准确率低于1%）。我们还发现幻觉现象与图像上下文之间存在关联，当面对高度上下文化反事实示例时，GPT-4o容易出现幻觉。尽管在处理来源冲突方面仍存在挑战，但微调模型显著提升了对反事实样本的推理能力。我们的研究结果强调了需要开发提升VLM推理能力的训练方法，特别是在解决多模态来源之间复杂知识冲突方面。

> The robustness of large language models (LLMs) against knowledge conflicts in unimodal question answering systems has been well studied. However, the effect of conflicts in information sources on vision language models (VLMs) in multimodal settings has not yet been explored. In this work, we propose \segsub, a framework that applies targeted perturbations to image sources to study and improve the robustness of VLMs against three different types of knowledge conflicts, namely parametric, source, and counterfactual conflicts. Contrary to prior findings that showed that LLMs are sensitive to parametric conflicts arising from textual perturbations, we find VLMs are largely robust to image perturbation. On the other hand, VLMs perform poorly on counterfactual examples (<30% accuracy) and fail to reason over source conflicts (<1% accuracy). We also find a link between hallucinations and image context, with GPT-4o prone to hallucination when presented with highly contextualized counterfactual examples. While challenges persist with source conflicts, finetuning models significantly improves reasoning over counterfactual samples. Our findings highlight the need for VLM training methodologies that enhance their reasoning capabilities, particularly in addressing complex knowledge conflicts between multimodal sources.

[Arxiv](https://arxiv.org/abs/2502.14908)