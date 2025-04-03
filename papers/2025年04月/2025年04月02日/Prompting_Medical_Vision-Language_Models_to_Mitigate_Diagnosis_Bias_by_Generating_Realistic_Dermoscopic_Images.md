# # 引导医疗视觉-语言模型生成真实皮肤镜图像以缓解诊断偏见

发布时间：2025年04月02日

`LLM应用

理由：这篇论文提出了一种基于生成式AI的新框架，利用视觉语言模型生成文本提示和多模态学习来生成皮肤镜图像，以改善皮肤病诊断中的偏见问题。这属于将大型语言模型（LLM）应用于特定领域（皮肤病诊断）的实际应用，因此归类为LLM应用。` `皮肤病诊断`

> Prompting Medical Vision-Language Models to Mitigate Diagnosis Bias by Generating Realistic Dermoscopic Images

# 摘要

> 人工智能（AI）在皮肤病诊断领域取得了显著进展，但这些模型在不同子群体中，尤其是涉及肤色等敏感属性时，常常表现出偏颇性能。为解决这一问题，我们提出了一种基于生成式AI的新框架——皮肤病扩散变压器（DermDiT）。该框架通过视觉语言模型生成的文本提示以及多模态文本-图像学习，生成新的皮肤镜图像。我们利用大型视觉语言模型为每张皮肤镜图像生成准确且恰当的提示，从而生成合成图像，以改善临床诊断中高度不平衡数据集中未充分代表的群体（如患者、疾病等）的表现。通过广泛实验，我们发现大型视觉语言模型能够提供更具洞察力的表征，使DermDiT能够生成高质量的图像。我们的代码可在GitHub上获取：https://github.com/Munia03/DermDiT

> Artificial Intelligence (AI) in skin disease diagnosis has improved significantly, but a major concern is that these models frequently show biased performance across subgroups, especially regarding sensitive attributes such as skin color. To address these issues, we propose a novel generative AI-based framework, namely, Dermatology Diffusion Transformer (DermDiT), which leverages text prompts generated via Vision Language Models and multimodal text-image learning to generate new dermoscopic images. We utilize large vision language models to generate accurate and proper prompts for each dermoscopic image which helps to generate synthetic images to improve the representation of underrepresented groups (patient, disease, etc.) in highly imbalanced datasets for clinical diagnoses. Our extensive experimentation showcases the large vision language models providing much more insightful representations, that enable DermDiT to generate high-quality images. Our code is available at https://github.com/Munia03/DermDiT

[Arxiv](https://arxiv.org/abs/2504.01838)