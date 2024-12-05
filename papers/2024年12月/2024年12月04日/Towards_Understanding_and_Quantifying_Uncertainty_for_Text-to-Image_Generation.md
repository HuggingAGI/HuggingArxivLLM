# 旨在理解和量化文本到图像生成中的不确定性

发布时间：2024年12月04日

`LLM应用` `图像生成` `不确定性量化`

> Towards Understanding and Quantifying Uncertainty for Text-to-Image Generation

# 摘要

> 在文本到图像（T2I）生成模型里，不确定性量化对于理解模型行为、提升输出可靠性极为关键。在本文中，我们率先针对提示来量化和评估 T2I 模型的不确定性。除了适配现有的旨在衡量图像空间不确定性的方法，我们还推出了针对 T2I 模型的基于提示的不确定性估计（PUNC）这一新方法，它借助大型视觉语言模型（LVLMs），能更好地处理由提示和生成图像的语义引发的不确定性。PUNC 利用 LVLM 为生成的图像添加标题，然后在更具语义内涵的文本空间中将标题与原始提示进行对比。PUNC 还能通过精度和召回率来分离偶然不确定性和认知不确定性，这是图像空间方法无法实现的。大量实验表明，PUNC 在各种设定下都超越了最先进的不确定性估计技术。文本到图像生成模型中的不确定性量化能够应用于多种场景，比如偏差检测、版权保护和 OOD 检测。我们还引入了一个涵盖全面的文本提示和生成对的数据集，以推动生成模型不确定性量化方面的进一步研究。我们的发现表明，PUNC 不但表现出有竞争力的性能，而且在评估和提高文本到图像模型的可信度方面开拓了新的应用。

> Uncertainty quantification in text-to-image (T2I) generative models is crucial for understanding model behavior and improving output reliability. In this paper, we are the first to quantify and evaluate the uncertainty of T2I models with respect to the prompt. Alongside adapting existing approaches designed to measure uncertainty in the image space, we also introduce Prompt-based UNCertainty Estimation for T2I models (PUNC), a novel method leveraging Large Vision-Language Models (LVLMs) to better address uncertainties arising from the semantics of the prompt and generated images. PUNC utilizes a LVLM to caption a generated image, and then compares the caption with the original prompt in the more semantically meaningful text space. PUNC also enables the disentanglement of both aleatoric and epistemic uncertainties via precision and recall, which image-space approaches are unable to do. Extensive experiments demonstrate that PUNC outperforms state-of-the-art uncertainty estimation techniques across various settings. Uncertainty quantification in text-to-image generation models can be used on various applications including bias detection, copyright protection, and OOD detection. We also introduce a comprehensive dataset of text prompts and generation pairs to foster further research in uncertainty quantification for generative models. Our findings illustrate that PUNC not only achieves competitive performance but also enables novel applications in evaluating and improving the trustworthiness of text-to-image models.

[Arxiv](https://arxiv.org/abs/2412.03178)