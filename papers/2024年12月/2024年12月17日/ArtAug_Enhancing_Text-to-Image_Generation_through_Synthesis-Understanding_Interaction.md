# ArtAug：借助合成 - 理解交互提升文本到图像的生成效果

发布时间：2024年12月17日

`LLM应用` `图像合成` `人工智能`

> ArtAug: Enhancing Text-to-Image Generation through Synthesis-Understanding Interaction

# 摘要

> 扩散模型的出现显著推进了图像合成技术的发展。大型语言模型中有关模型交互和自我纠正推理方法的最新研究，为增强文本到图像模型带来了新的思路。受此启发，我们在本文中提出了一种名为 ArtAug 的新方法用于增强文本到图像模型。据我们了解，ArtAug 是首个通过与理解模型进行交互来改进图像合成模型的方法。在交互过程中，我们借助图像理解模型隐式习得的人类偏好，为图像合成模型提供精细的建议。这些交互能够对图像内容进行修改，使其更具美感，比如调整曝光、改变拍摄角度以及添加大气效果等。通过一个额外的增强模块，交互所带来的增强效果会迭代地融入到合成模型自身当中。这使得合成模型能够直接生成美观的图像，且无需额外的计算成本。在实验里，我们在现有的文本到图像模型上训练 ArtAug 增强模块。各种评估指标均一致显示，ArtAug 在不增加额外计算成本的情况下，提升了文本到图像模型的生成能力。源代码和模型将会公开。

> The emergence of diffusion models has significantly advanced image synthesis. The recent studies of model interaction and self-corrective reasoning approach in large language models offer new insights for enhancing text-to-image models. Inspired by these studies, we propose a novel method called ArtAug for enhancing text-to-image models in this paper. To the best of our knowledge, ArtAug is the first one that improves image synthesis models via model interactions with understanding models. In the interactions, we leverage human preferences implicitly learned by image understanding models to provide fine-grained suggestions for image synthesis models. The interactions can modify the image content to make it aesthetically pleasing, such as adjusting exposure, changing shooting angles, and adding atmospheric effects. The enhancements brought by the interaction are iteratively fused into the synthesis model itself through an additional enhancement module. This enables the synthesis model to directly produce aesthetically pleasing images without any extra computational cost. In the experiments, we train the ArtAug enhancement module on existing text-to-image models. Various evaluation metrics consistently demonstrate that ArtAug enhances the generative capabilities of text-to-image models without incurring additional computational costs. The source code and models will be released publicly.

[Arxiv](https://arxiv.org/abs/2412.12888)