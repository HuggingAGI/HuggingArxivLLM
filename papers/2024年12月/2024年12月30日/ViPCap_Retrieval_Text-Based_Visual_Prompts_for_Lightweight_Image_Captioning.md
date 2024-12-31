# ViPCap：用于轻量图像字幕生成的基于检索文本的视觉提示

发布时间：2024年12月30日

`LLM应用` `图像描述` `计算机视觉`

> ViPCap: Retrieval Text-Based Visual Prompts for Lightweight Image Captioning

# 摘要

> 近期，采用检索数据的轻量级图像描述模型主要聚焦于文本提示。然而，以往的工作仅把检索到的文本当作文本提示，视觉信息也仅依赖于 CLIP 视觉嵌入。正因如此，存在一个局限性，即提示中固有的图像描述在视觉嵌入空间里未能充分体现。为应对此问题，我们提出了 ViPCap，这是一种用于轻量级图像描述的新型基于检索文本的视觉提示。ViPCap 借助带有图像信息的检索文本作为视觉提示，增强模型捕捉相关视觉信息的能力。通过将文本提示映射至 CLIP 空间并生成多个随机高斯分布，我们的方法利用采样来探索随机增强的分布，有效检索包含图像信息的语义特征。这些检索到的特征被融入图像并指定为视觉提示，使得在 COCO、Flickr30k 和 NoCaps 等数据集上的性能得以提升。实验结果表明，ViPCap 在效率和效果上显著优于先前的轻量级描述模型，展现出作为即插即用解决方案的潜力。

> Recent lightweight image captioning models using retrieved data mainly focus on text prompts. However, previous works only utilize the retrieved text as text prompts, and the visual information relies only on the CLIP visual embedding. Because of this issue, there is a limitation that the image descriptions inherent in the prompt are not sufficiently reflected in the visual embedding space. To tackle this issue, we propose ViPCap, a novel retrieval text-based visual prompt for lightweight image captioning. ViPCap leverages the retrieved text with image information as visual prompts to enhance the ability of the model to capture relevant visual information. By mapping text prompts into the CLIP space and generating multiple randomized Gaussian distributions, our method leverages sampling to explore randomly augmented distributions and effectively retrieves the semantic features that contain image information. These retrieved features are integrated into the image and designated as the visual prompt, leading to performance improvements on the datasets such as COCO, Flickr30k, and NoCaps. Experimental results demonstrate that ViPCap significantly outperforms prior lightweight captioning models in efficiency and effectiveness, demonstrating the potential for a plug-and-play solution.

[Arxiv](https://arxiv.org/abs/2412.19289)