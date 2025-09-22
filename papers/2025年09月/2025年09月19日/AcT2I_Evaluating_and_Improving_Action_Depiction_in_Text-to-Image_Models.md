# AcT2I：文本到图像模型中动作描绘的评估与提升

发布时间：2025年09月19日

`LLM应用` `媒体与娱乐`

> AcT2I: Evaluating and Improving Action Depiction in Text-to-Image Models

# 摘要

> 文本到图像（T2I）模型近年来在根据文本描述生成图像方面取得了惊人成就。但在准确绘制以动作和交互为核心语义的复杂场景时，仍面临挑战。我们在研究中发现，T2I模型常常难以捕捉动作描述中那些细微且多为隐含的固有属性，进而生成的图像往往缺失关键的上下文细节。为此，我们构建了AcT2I基准，专门用于评估T2I模型对动作导向提示词的图像生成表现。实验结果表明，主流T2I模型在AcT2I上的表现不尽如人意。我们进一步推测，这一短板源于现有T2I模型训练语料未能完整表示动作的固有属性及上下文依赖关系。基于这一假设，我们提出了一种无需额外训练的知识蒸馏技术，借助大型语言模型来弥补这一不足。具体来说，我们从三个维度为提示词补充密集信息，结果显示注入时间细节能大幅提升图像生成的准确性，最优模型的表现提升了72%。研究结果揭示了现有T2I方法在生成需复杂推理的图像时的局限，同时表明系统性整合语言知识能有效提升图像的细节丰富度与上下文准确性。

> Text-to-Image (T2I) models have recently achieved remarkable success in generating images from textual descriptions. However, challenges still persist in accurately rendering complex scenes where actions and interactions form the primary semantic focus. Our key observation in this work is that T2I models frequently struggle to capture nuanced and often implicit attributes inherent in action depiction, leading to generating images that lack key contextual details. To enable systematic evaluation, we introduce AcT2I, a benchmark designed to evaluate the performance of T2I models in generating images from action-centric prompts. We experimentally validate that leading T2I models do not fare well on AcT2I. We further hypothesize that this shortcoming arises from the incomplete representation of the inherent attributes and contextual dependencies in the training corpora of existing T2I models. We build upon this by developing a training-free, knowledge distillation technique utilizing Large Language Models to address this limitation. Specifically, we enhance prompts by incorporating dense information across three dimensions, observing that injecting prompts with temporal details significantly improves image generation accuracy, with our best model achieving an increase of 72%. Our findings highlight the limitations of current T2I methods in generating images that require complex reasoning and demonstrate that integrating linguistic knowledge in a systematic way can notably advance the generation of nuanced and contextually accurate images.

[Arxiv](https://arxiv.org/abs/2509.16141)