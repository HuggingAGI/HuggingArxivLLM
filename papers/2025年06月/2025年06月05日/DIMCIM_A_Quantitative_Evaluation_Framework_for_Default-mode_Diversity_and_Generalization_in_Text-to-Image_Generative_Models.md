# DIMCIM：文本到图像生成模型中默认模式多样性和泛化的定量评估框架

发布时间：2025年06月05日

`LLM应用` `生成模型` `计算机视觉`

> DIMCIM: A Quantitative Evaluation Framework for Default-mode Diversity and Generalization in Text-to-Image Generative Models

# 摘要

> 近年来，文本到图像（T2I）模型在生成质量与一致性方面取得了显著突破。然而，这一进步却以牺牲表达多样性为代价。尽管现有自动评估方法可用于衡量模型多样性，但这些方法要么依赖参考图像数据集，要么未能明确说明所测多样性的具体类型，这大大限制了其适用性和可解释性。为弥补这一研究空白，我们提出了一种全新的评估框架——DIM-CIM（Does-it/Can-it框架），用于无参考地测量模型的默认模式多样性（“模型能否生成预期属性的图像？”）和泛化能力（“模型能否为特定概念生成多样化的属性？”）。我们基于COCO概念和 captions构建了COCO-DIMCIM基准测试，并通过大型语言模型进行增强。通过这一基准测试，我们发现，当模型参数从1.5B扩展到8.1B时，尽管模型的泛化能力有所提升，但其默认模式多样性却大幅下降。此外，DIMCIM还能识别出一些细粒度的失败案例，例如模型能够通过通用提示生成某些属性，但在显式请求时却很少生成。最后，我们利用DIMCIM对T2I模型的训练数据进行了评估，发现训练图像多样性与模型默认模式多样性之间存在高达0.85的相关性。我们的研究提供了一种灵活且可解释的框架，用于全面评估T2I模型的多样性和泛化能力，从而更深入地理解模型性能。

> Recent advances in text-to-image (T2I) models have achieved impressive quality and consistency. However, this has come at the cost of representation diversity. While automatic evaluation methods exist for benchmarking model diversity, they either require reference image datasets or lack specificity about the kind of diversity measured, limiting their adaptability and interpretability. To address this gap, we introduce the Does-it/Can-it framework, DIM-CIM, a reference-free measurement of default-mode diversity ("Does" the model generate images with expected attributes?) and generalization capacity ("Can" the model generate diverse attributes for a particular concept?). We construct the COCO-DIMCIM benchmark, which is seeded with COCO concepts and captions and augmented by a large language model. With COCO-DIMCIM, we find that widely-used models improve in generalization at the cost of default-mode diversity when scaling from 1.5B to 8.1B parameters. DIMCIM also identifies fine-grained failure cases, such as attributes that are generated with generic prompts but are rarely generated when explicitly requested. Finally, we use DIMCIM to evaluate the training data of a T2I model and observe a correlation of 0.85 between diversity in training images and default-mode diversity. Our work provides a flexible and interpretable framework for assessing T2I model diversity and generalization, enabling a more comprehensive understanding of model performance.

[Arxiv](https://arxiv.org/abs/2506.05108)