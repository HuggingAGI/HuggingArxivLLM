# Maya：一个经过指令微调的多语言多模态模型

发布时间：2024年12月09日

`LLM应用` `计算机视觉`

> Maya: An Instruction Finetuned Multilingual Multimodal Model

# 摘要

> 大型视觉语言模型（VLMs）发展迅猛，在学术基准测试中成果斐然，尤其是在常用语言方面。然而，当下的VLMs在应对低资源语言和多样文化背景时能力尚有明显不足，很大程度上是因为缺少高质量、多元化且经过安全审核的数据。正因如此，这些模型常常难以无毒无害地理解低资源语言和文化中的细微差异。为克服这些局限，我们推出了Maya，这是一个开源的多模态多语言模型。我们的贡献主要有三点：1）基于LLaVA预训练数据集，构建了包含八种语言的多语言图像-文本预训练数据集；2）对LLaVA数据集中的毒性进行了全面剖析，并创建了涵盖八种语言的全新无毒版本；3）打造了支持这些语言的多语言图像-文本模型，提升了视觉语言任务中的文化和语言理解能力。代码可在https://github.com/nahidalam/maya获取。

> The rapid development of large Vision-Language Models (VLMs) has led to impressive results on academic benchmarks, primarily in widely spoken languages. However, significant gaps remain in the ability of current VLMs to handle low-resource languages and varied cultural contexts, largely due to a lack of high-quality, diverse, and safety-vetted data. Consequently, these models often struggle to understand low-resource languages and cultural nuances in a manner free from toxicity. To address these limitations, we introduce Maya, an open-source Multimodal Multilingual model. Our contributions are threefold: 1) a multilingual image-text pretraining dataset in eight languages, based on the LLaVA pretraining dataset; 2) a thorough analysis of toxicity within the LLaVA dataset, followed by the creation of a novel toxicity-free version across eight languages; and 3) a multilingual image-text model supporting these languages, enhancing cultural and linguistic comprehension in vision-language tasks. Code available at https://github.com/nahidalam/maya.

[Arxiv](https://arxiv.org/abs/2412.07112)