# 一个基于人类反馈和产品一致性的产品图像背景修复评估框架

发布时间：2024年12月23日

`其他` `产品图像`

> An Evaluation Framework for Product Images Background Inpainting based on Human Feedback and Product Consistency

# 摘要

> 在产品广告应用里，借助 AI 技术对产品图像的背景进行自动修复，已成为一项关键任务。但这些技术仍存在生成的产品图像背景不当、产品不一致等问题，现有的生成产品图像质量评估方法大多与人类反馈不符，致使该任务的评估依赖人工标注。为化解上述难题，本文提出了人类反馈和产品一致性（HFPC），它能基于两个模块自动评估生成的产品图像。其一，为解决背景不合适的问题，收集了 44,000 个自动修复产品图像的人类反馈，基于从 BLIP 提取的多模态特征和对比学习训练奖励模型。其二，为筛选出包含不一致产品的生成产品图像，运用微调的分割模型对原始和生成的产品图像中的产品进行分割，再比较两者差异。大量实验表明，HFPC 能有效评估生成产品图像的质量，大幅降低人工标注的成本。此外，与其他开源视觉质量评估模型相比，HFPC 达到了先进水平（精度达 96.4%）。数据集和代码可在：https://github.com/created-Bi/background_inpainting_products_dataset 获取。

> In product advertising applications, the automated inpainting of backgrounds utilizing AI techniques in product images has emerged as a significant task. However, the techniques still suffer from issues such as inappropriate background and inconsistent product in generated product images, and existing approaches for evaluating the quality of generated product images are mostly inconsistent with human feedback causing the evaluation for this task to depend on manual annotation. To relieve the issues above, this paper proposes Human Feedback and Product Consistency (HFPC), which can automatically assess the generated product images based on two modules. Firstly, to solve inappropriate backgrounds, human feedback on 44,000 automated inpainting product images is collected to train a reward model based on multi-modal features extracted from BLIP and comparative learning. Secondly, to filter generated product images containing inconsistent products, a fine-tuned segmentation model is employed to segment the product of the original and generated product images and then compare the differences between the above two. Extensive experiments have demonstrated that HFPC can effectively evaluate the quality of generated product images and significantly reduce the expense of manual annotation. Moreover, HFPC achieves state-of-the-art(96.4% in precision) in comparison to other open-source visual-quality-assessment models. Dataset and code are available at: https://github.com/created-Bi/background_inpainting_products_dataset

[Arxiv](https://arxiv.org/abs/2412.17504)