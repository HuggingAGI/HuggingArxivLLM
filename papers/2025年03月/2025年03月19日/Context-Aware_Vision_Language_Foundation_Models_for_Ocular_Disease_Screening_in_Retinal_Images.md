# 上下文感知视觉语言基础模型用于眼底图像的眼科疾病筛查

发布时间：2025年03月19日

`Agent` `机器人流程自动化` `智能体流程自动化`

> Context-Aware Vision Language Foundation Models for Ocular Disease Screening in Retinal Images

# 摘要

> # 摘要  
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

> Foundation models are large-scale versatile systems trained on vast quantities of diverse data to learn generalizable representations. Their adaptability with minimal fine-tuning makes them particularly promising for medical imaging, where data variability and domain shifts are major challenges. Currently, two types of foundation models dominate the literature: self-supervised models and more recent vision-language models. In this study, we advance the application of vision-language foundation (VLF) models for ocular disease screening using the OPHDIAT dataset, which includes nearly 700,000 fundus photographs from a French diabetic retinopathy (DR) screening network. This dataset provides extensive clinical data (patient-specific information such as diabetic health conditions, and treatments), labeled diagnostics, ophthalmologists text-based findings, and multiple retinal images for each examination. Building on the FLAIR model $unicode{x2013}$ a VLF model for retinal pathology classification $unicode{x2013}$ we propose novel context-aware VLF models (e.g jointly analyzing multiple images from the same visit or taking advantage of past diagnoses and contextual data) to fully leverage the richness of the OPHDIAT dataset and enhance robustness to domain shifts. Our approaches were evaluated on both in-domain (a testing subset of OPHDIAT) and out-of-domain data (public datasets) to assess their generalization performance. Our model demonstrated improved in-domain performance for DR grading, achieving an area under the curve (AUC) ranging from 0.851 to 0.9999, and generalized well to ocular disease detection on out-of-domain data (AUC: 0.631-0.913).

[Arxiv](https://arxiv.org/abs/2503.15212)