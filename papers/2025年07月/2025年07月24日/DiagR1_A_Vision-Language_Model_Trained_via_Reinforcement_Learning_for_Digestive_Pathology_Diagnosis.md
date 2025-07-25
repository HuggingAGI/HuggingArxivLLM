# DiagR1：基于强化学习的视觉-语言模型在消化病理诊断中的应用

发布时间：2025年07月24日

`LLM应用` `病理图像分析`

> DiagR1: A Vision-Language Model Trained via Reinforcement Learning for Digestive Pathology Diagnosis

# 摘要

> 多模态大模型在病理图像分析的自动化领域展现出巨大潜力。然而，现有胃肠道病理相关的多模态模型面临数据质量和推理透明度的双重挑战：公共数据集中的噪声和标注缺失导致视觉语言模型在生成诊断文本时易出现事实性错误，而缺乏明确的推理链路则使输出难以审核，影响临床应用的可靠性。为解决这些问题，我们构建了一个包含微观描述和诊断结论的大型胃肠道病理数据集，并提出了一种结合病变分类和解剖部位信息的提示论证策略。这一设计不仅帮助模型更好地捕捉图像特异性特征，还确保了生成内容的语义一致性。此外，我们采用结合监督微调与组相对策略优化（GRPO）的后训练流水线，进一步提升推理质量和输出结构。在真实世界病理报告生成任务中，我们的方法在生成质量、结构完整性和临床相关性方面显著超越现有开源和专有基线模型。具体而言，我们的解决方案在临床相关性上比现有最优模型高出18.7%，结构完整性提升了32.4%，诊断错误减少了41.2%，充分展现了其在准确性和临床实用性上的显著优势。


> Multimodal large models have shown great potential in automating pathology image analysis. However, current multimodal models for gastrointestinal pathology are constrained by both data quality and reasoning transparency: pervasive noise and incomplete annotations in public datasets predispose vision language models to factual hallucinations when generating diagnostic text, while the absence of explicit intermediate reasoning chains renders the outputs difficult to audit and thus less trustworthy in clinical practice. To address these issues, we construct a large scale gastrointestinal pathology dataset containing both microscopic descriptions and diagnostic conclusions, and propose a prompt argumentation strategy that incorporates lesion classification and anatomical site information. This design guides the model to better capture image specific features and maintain semantic consistency in generation. Furthermore, we employ a post training pipeline that combines supervised fine tuning with Group Relative Policy Optimization (GRPO) to improve reasoning quality and output structure. Experimental results on real world pathology report generation tasks demonstrate that our approach significantly outperforms state of the art open source and proprietary baselines in terms of generation quality, structural completeness, and clinical relevance. Our solution outperforms state of the art models with 18.7% higher clinical relevance, 32.4% improved structural completeness, and 41.2% fewer diagnostic errors, demonstrating superior accuracy and clinical utility compared to existing solutions.

[Arxiv](https://arxiv.org/abs/2507.18433)