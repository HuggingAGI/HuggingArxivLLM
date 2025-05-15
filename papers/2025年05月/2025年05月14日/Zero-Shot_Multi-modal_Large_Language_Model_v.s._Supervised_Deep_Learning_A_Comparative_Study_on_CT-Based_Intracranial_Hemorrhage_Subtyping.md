# 零样本多模态大语言模型与监督式深度学习的对比研究：基于CT的颅内出血分型

发布时间：2025年05月14日

`LLM应用` `医学影像`

> Zero-Shot Multi-modal Large Language Model v.s. Supervised Deep Learning: A Comparative Study on CT-Based Intracranial Hemorrhage Subtyping

# 摘要

> 引言：颅内出血（ICH）亚型的及时识别在非对比增强CT上对于预后预测和治疗决策至关重要，但因对比度低和边界模糊而具有挑战性。本研究旨在评估零样本多模态大型语言模型（MLLMs）在ICH二分类和分型任务中相对于传统深度学习方法的性能。方法：我们采用了由RSNA提供的包含192个非对比增强CT体积的数据集。本研究比较了包括GPT-4o、Gemini 2.0 Flash和Claude 3.5 Sonnet V2在内的多种MLLMs，与ResNet50和Vision Transformer等传统深度学习模型进行了对比。通过精心设计的提示语，我们引导MLLMs完成ICH存在检测、亚型分类、定位以及体积估计等任务。结果：研究结果表明，在ICH二分类任务中，传统深度学习模型全面优于MLLMs。在亚型分类任务中，MLLMs的表现也逊色于传统深度学习模型，其中Gemini 2.0 Flash的平均精度为0.41，平均F1得分为0.31。结论：尽管MLLMs在交互能力方面表现出色，但在ICH亚型分类的整体准确性上仍逊于深度网络。然而，MLLMs通过语言交互提升了分析的可解释性，显示出在医学影像分析中的潜力。未来研究将聚焦于模型优化，开发更精确的MLLMs，以提升三维医学图像处理性能。

> Introduction: Timely identification of intracranial hemorrhage (ICH) subtypes on non-contrast computed tomography is critical for prognosis prediction and therapeutic decision-making, yet remains challenging due to low contrast and blurring boundaries. This study evaluates the performance of zero-shot multi-modal large language models (MLLMs) compared to traditional deep learning methods in ICH binary classification and subtyping. Methods: We utilized a dataset provided by RSNA, comprising 192 NCCT volumes. The study compares various MLLMs, including GPT-4o, Gemini 2.0 Flash, and Claude 3.5 Sonnet V2, with conventional deep learning models, including ResNet50 and Vision Transformer. Carefully crafted prompts were used to guide MLLMs in tasks such as ICH presence, subtype classification, localization, and volume estimation. Results: The results indicate that in the ICH binary classification task, traditional deep learning models outperform MLLMs comprehensively. For subtype classification, MLLMs also exhibit inferior performance compared to traditional deep learning models, with Gemini 2.0 Flash achieving an macro-averaged precision of 0.41 and a macro-averaged F1 score of 0.31. Conclusion: While MLLMs excel in interactive capabilities, their overall accuracy in ICH subtyping is inferior to deep networks. However, MLLMs enhance interpretability through language interactions, indicating potential in medical imaging analysis. Future efforts will focus on model refinement and developing more precise MLLMs to improve performance in three-dimensional medical image processing.

[Arxiv](https://arxiv.org/abs/2505.09252)