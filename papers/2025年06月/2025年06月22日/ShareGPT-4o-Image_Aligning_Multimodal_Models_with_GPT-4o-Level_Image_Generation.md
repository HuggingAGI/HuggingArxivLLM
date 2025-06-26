# # ShareGPT-4o-Image：实现多模态模型与GPT-4o级图像生成的对齐

发布时间：2025年06月22日

`LLM应用` `视觉设计` `图像处理`

> ShareGPT-4o-Image: Aligning Multimodal Models with GPT-4o-Level Image Generation

# 摘要

> # 摘要
多模态生成模型的最新进展为生成照片级真实感且与指令对齐的图像开辟了新可能，但目前像GPT-4o-Image这样的顶尖系统仍处于封闭状态。为促进这一技术的普惠化，我们推出了ShareGPT-4o-Image，这是首个包含4.5万个文本到图像和4.6万个文本加图像到图像的数据集，所有样本均由GPT-4o的图像生成能力生成，旨在萃取其先进的图像生成技术。基于这一数据集，我们开发了Janus-4o，一款支持文本到图像和文本加图像到图像生成的多模态大型语言模型。Janus-4o不仅在文本到图像生成方面超越了前代Janus-Pro，还首次实现了文本加图像到图像生成功能。尤为值得关注的是，仅通过9.1万个合成样本和8张A800-GPU机器上6小时的训练，Janus-4o便在从零开始的文本加图像到图像生成任务中展现了卓越性能。我们期待ShareGPT-4o-Image数据集和Janus-4o模型的开源能够激发更多研究，推动照片级真实感且与指令对齐的图像生成技术的开放发展。

> Recent advances in multimodal generative models have unlocked photorealistic, instruction-aligned image generation, yet leading systems like GPT-4o-Image remain proprietary and inaccessible. To democratize these capabilities, we present ShareGPT-4o-Image, the first dataset comprising 45K text-to-image and 46K text-and-image-to-image data, all synthesized using GPT-4o's image generation capabilities for distilling its advanced image generation abilities. Leveraging this dataset, we develop Janus-4o, a multimodal large language model capable of both text-to-image and text-and-image-to-image generation. Janus-4o not only significantly improves text-to-image generation over its predecessor, Janus-Pro, but also newly supports text-and-image-to-image generation. Notably, it achieves impressive performance in text-and-image-to-image generation from scratch, using only 91K synthetic samples and 6 hours of training on an 8 A800-GPU machine. We hope the release of ShareGPT-4o-Image and Janus-4o will foster open research in photorealistic, instruction-aligned image generation.

[Arxiv](https://arxiv.org/abs/2506.18095)