# 基于多模态大型语言模型模拟临床AI辅助：糖尿病视网膜病变案例研究

发布时间：2025年09月16日

`LLM应用` `医疗健康`

> Simulating Clinical AI Assistance using Multimodal LLMs: A Case Study in Diabetic Retinopathy

# 摘要

> 糖尿病视网膜病变（DR）是全球失明的首要诱因，AI系统有助于普及眼底摄影筛查。当前FDA认证的系统主要提供二元转诊结果，这种简单输出可能降低临床信任度与实用性。然而，确定最有效的输出格式以提升临床医生与AI的协作表现，仍是一个难以大规模评估的实证难题。本研究评估了多模态大型语言模型（MLLMs）在DR检测中的表现，以及它们模拟不同输出类型临床AI辅助功能的能力。在IDRiD和Messidor-2两个数据集上对两款模型进行了测试：通用型MLLM GPT-4o和开源医疗模型MedGemma。实验涵盖：（1）基线评估，（2）基于合成预测的模拟AI辅助，（3）GPT-4o整合MedGemma输出的AI协同场景。基线评估显示，MedGemma性能优于GPT-4o，敏感性和AUROC均更高；而GPT-4o特异性接近完美但敏感性偏低。两款模型均会根据模拟的AI输入调整预测结果，但GPT-4o在输入错误时性能骤降，MedGemma则表现更稳定。实际协作中，即便无法直接访问图像，GPT-4o在MedGemma的描述性输出指导下仍表现优异（AUROC高达0.96）。这些发现表明，MLLMs有望优化DR筛查流程，还可作为可扩展的模拟器，用于研究不同输出配置下的临床AI辅助效果。MedGemma等开源轻量级模型在资源有限的环境中可能更具实用价值，而描述性输出则有助于提升AI的可解释性及临床医生在诊疗流程中对AI的信任度。

> Diabetic retinopathy (DR) is a leading cause of blindness worldwide, and AI systems can expand access to fundus photography screening. Current FDA-cleared systems primarily provide binary referral outputs, where this minimal output may limit clinical trust and utility. Yet, determining the most effective output format to enhance clinician-AI performance is an empirical challenge that is difficult to assess at scale. We evaluated multimodal large language models (MLLMs) for DR detection and their ability to simulate clinical AI assistance across different output types. Two models were tested on IDRiD and Messidor-2: GPT-4o, a general-purpose MLLM, and MedGemma, an open-source medical model. Experiments included: (1) baseline evaluation, (2) simulated AI assistance with synthetic predictions, and (3) actual AI-to-AI collaboration where GPT-4o incorporated MedGemma outputs. MedGemma outperformed GPT-4o at baseline, achieving higher sensitivity and AUROC, while GPT-4o showed near-perfect specificity but low sensitivity. Both models adjusted predictions based on simulated AI inputs, but GPT-4o's performance collapsed with incorrect ones, whereas MedGemma remained more stable. In actual collaboration, GPT-4o achieved strong results when guided by MedGemma's descriptive outputs, even without direct image access (AUROC up to 0.96). These findings suggest MLLMs may improve DR screening pipelines and serve as scalable simulators for studying clinical AI assistance across varying output configurations. Open, lightweight models such as MedGemma may be especially valuable in low-resource settings, while descriptive outputs could enhance explainability and clinician trust in clinical workflows.

[Arxiv](https://arxiv.org/abs/2509.13234)