# X2I：通过注意力蒸馏实现多模态理解与扩散式Transformer的无缝融合。

发布时间：2025年03月08日

`LLM应用

理由：这篇论文探讨了将多模态大语言模型的能力迁移到文本到图像生成模型中，提出了一个框架X2I，使其支持多模态输入。这属于LLM的应用层面，因为它展示了如何将LLM的能力扩展到图像生成任务中，涉及模型的应用和迁移。` `图像生成` `多模态`

> X2I: Seamless Integration of Multimodal Understanding into Diffusion Transformer via Attention Distillation

# 摘要

> 文本到图像（T2I）模型擅长生成逼真图像，而多模态大语言模型（MLLMs）则在多模态理解与整合方面表现出色。然而，目前尚无简单高效的框架能将MLLMs的多模态能力迁移至T2I模型，使其支持多模态输入。为此，我们提出了X2I框架，赋予了Diffusion Transformer（DiT）模型理解多种模态的能力，涵盖多语言文本、截图文档、图像、视频和音频。X2I仅需100K英语语料库和160 GPU小时即可完成训练。基于DiT教师模型，我们采用创新蒸馏方法提取其推理能力，并设计轻量级AlignNet作为中间桥梁。与教师模型相比，X2I的性能仅下降不到1%，却新增了多模态理解能力，包括多语言到图像、图像到图像、图像文本到图像、视频到图像、音频到图像，以及通过创意融合提升图像质量。此外，它还支持图像文本到图像生成的低秩适应（LoRA）训练，填补了行业空白。我们还设计了简单易用的LightControl来增强图像编辑的真实感。最后，大量实验验证了X2I在有效性、效率、多功能性和可迁移性方面的卓越表现。X2I的开源代码和检查点可在以下链接获取：https://github.com/OPPO-Mente-Lab/X2I。

> Text-to-image (T2I) models are well known for their ability to produce highly realistic images, while multimodal large language models (MLLMs) are renowned for their proficiency in understanding and integrating multiple modalities. However, currently there is no straightforward and efficient framework to transfer the multimodal comprehension abilities of MLLMs to T2I models to enable them to understand multimodal inputs. In this paper, we propose the X2I framework, which endows Diffusion Transformer (DiT) models with the capability to comprehend various modalities, including multilingual text, screenshot documents, images, videos, and audio. X2I is trained using merely 100K English corpus with 160 GPU hours. Building on the DiT teacher model, we adopt an innovative distillation method to extract the inference capabilities of the teacher model and design a lightweight AlignNet structure to serve as an intermediate bridge. Compared to the teacher model, X2I shows a decrease in performance degradation of less than 1\% while gaining various multimodal understanding abilities, including multilingual to image, image to image, image-text to image, video to image, audio to image, and utilizing creative fusion to enhance imagery. Furthermore, it is applicable for LoRA training in the context of image-text to image generation, filling a void in the industry in this area. We further design a simple LightControl to enhance the fidelity of instructional image editing. Finally, extensive experiments demonstrate the effectiveness, efficiency, multifunctionality, and transferability of our X2I. The open-source code and checkpoints for X2I can be found at the following link: https://github.com/OPPO-Mente-Lab/X2I.

[Arxiv](https://arxiv.org/abs/2503.06134)