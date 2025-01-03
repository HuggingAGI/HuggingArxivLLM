# 扩散增强的测试时适应：结合文本与图像增强

发布时间：2024年12月12日

`LLM应用

理由：这篇论文主要讨论了一种新的测试时适应方法（IT3A），利用预训练的生成模型对来自未知新领域的每个测试样本进行多模态增强。该方法结合了预训练的视觉和语言模型，提升了模型适应未知新测试数据的能力。虽然论文中提到了生成模型和视觉模型，但其核心是利用预训练的语言模型（LLM）进行多模态增强，因此可以归类为LLM应用。` `计算机视觉`

> Diffusion-Enhanced Test-time Adaptation with Text and Image Augmentation

# 摘要

> 现有的测试时提示调优（TPT）方法主要针对单模态数据，通常通过增强图像并利用置信度评分过滤不准确的图像。然而，尽管图像生成模型能够生成多样化的图像，单模态数据增强技术仍难以捕捉不同模态提供的全面知识。此外，当增强图像数量有限时，基于TPT的方法性能显著下降，这在生成增强计算成本较高的情况下并不罕见。为解决这些问题，我们提出了IT3A，一种新颖的测试时适应方法，利用预训练的生成模型对来自未知新领域的每个测试样本进行多模态增强。通过结合预训练视觉和语言模型的增强数据，IT3A提升了模型适应未知新测试数据的能力。同时，为确保在生成各种视觉和文本增强时准确保留关键语义，我们在增强图像和文本的logits与原始测试数据之间采用余弦相似度过滤，以剔除虚假增强和不充分组合。为了充分利用生成模型在不同模态上的多样化增强，我们用适配器替代提示调优，从而更灵活地使用文本模板。在具有分布偏移和领域差距的测试数据集上的实验表明，在零-shot设置下，IT3A以5.50%的准确率提升超越了最先进的测试时提示调优方法。

> Existing test-time prompt tuning (TPT) methods focus on single-modality data, primarily enhancing images and using confidence ratings to filter out inaccurate images. However, while image generation models can produce visually diverse images, single-modality data enhancement techniques still fail to capture the comprehensive knowledge provided by different modalities. Additionally, we note that the performance of TPT-based methods drops significantly when the number of augmented images is limited, which is not unusual given the computational expense of generative augmentation. To address these issues, we introduce IT3A, a novel test-time adaptation method that utilizes a pre-trained generative model for multi-modal augmentation of each test sample from unknown new domains. By combining augmented data from pre-trained vision and language models, we enhance the ability of the model to adapt to unknown new test data. Additionally, to ensure that key semantics are accurately retained when generating various visual and text enhancements, we employ cosine similarity filtering between the logits of the enhanced images and text with the original test data. This process allows us to filter out some spurious augmentation and inadequate combinations. To leverage the diverse enhancements provided by the generation model across different modals, we have replaced prompt tuning with an adapter for greater flexibility in utilizing text templates. Our experiments on the test datasets with distribution shifts and domain gaps show that in a zero-shot setting, IT3A outperforms state-of-the-art test-time prompt tuning methods with a 5.50% increase in accuracy.

[Arxiv](https://arxiv.org/abs/2412.09706)