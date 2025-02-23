# FetalCLIP：用于胎儿超声图像分析的视觉-语言基础模型

发布时间：2025年02月20日

`LLM应用` `医学成像`

> FetalCLIP: A Visual-Language Foundation Model for Fetal Ultrasound Image Analysis

# 摘要

> 基础模型正在医学领域展现出强大潜力，通过预训练大型数据集，能够快速适配各种下游任务。然而，胎儿超声图像因其复杂性，依然是基础模型的难点领域，通常需要大量额外训练，且受限于配对多模态数据的稀缺性。为突破这一困境，我们推出了FetalCLIP——一款视觉-语言基础模型，专为生成胎儿超声图像的通用表示而设计。FetalCLIP基于210,035张配对文本的胎儿超声图像数据集，采用多模态学习方法进行了预训练，这是同类数据集中规模最大的。这一创新训练方式使FetalCLIP能够精准捕捉胎儿超声图像中的复杂解剖特征，生成的稳健表示可应用于多种场景。在涵盖胎儿超声分类、孕龄估算、先天性心脏病检测及胎儿结构分割等关键任务的全面评估中，FetalCLIP不仅超越所有现有基线模型，更展现了出色的泛化能力，即使在标注数据有限的情况下，依然表现优异。我们计划公开发布FetalCLIP模型，助力全球科研工作者。


> Foundation models are becoming increasingly effective in the medical domain, offering pre-trained models on large datasets that can be readily adapted for downstream tasks. Despite progress, fetal ultrasound images remain a challenging domain for foundation models due to their inherent complexity, often requiring substantial additional training and facing limitations due to the scarcity of paired multimodal data. To overcome these challenges, here we introduce FetalCLIP, a vision-language foundation model capable of generating universal representation of fetal ultrasound images. FetalCLIP was pre-trained using a multimodal learning approach on a diverse dataset of 210,035 fetal ultrasound images paired with text. This represents the largest paired dataset of its kind used for foundation model development to date. This unique training approach allows FetalCLIP to effectively learn the intricate anatomical features present in fetal ultrasound images, resulting in robust representations that can be used for a variety of downstream applications. In extensive benchmarking across a range of key fetal ultrasound applications, including classification, gestational age estimation, congenital heart defect (CHD) detection, and fetal structure segmentation, FetalCLIP outperformed all baselines while demonstrating remarkable generalizability and strong performance even with limited labeled data. We plan to release the FetalCLIP model publicly for the benefit of the broader scientific community.

[Arxiv](https://arxiv.org/abs/2502.14807)