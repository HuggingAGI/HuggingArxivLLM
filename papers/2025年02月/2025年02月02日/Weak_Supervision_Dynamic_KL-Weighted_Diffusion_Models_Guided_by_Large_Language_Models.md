# 大型语言模型引导的弱监督动态KL加权扩散模型

发布时间：2025年02月02日

`LLM应用

**理由**：该论文主要探讨了如何将大型语言模型（LLMs）与扩散模型结合，以提升文本到图像生成的质量与效率。虽然涉及了扩散模型，但其核心是利用LLMs的语义理解能力来指导图像生成，属于LLM在多模态任务中的应用。因此，分类为“LLM应用”更为合适。` `计算机视觉` `图像生成`

> Weak Supervision Dynamic KL-Weighted Diffusion Models Guided by Large Language Models

# 摘要

> 本文提出了一种结合大型语言模型（LLMs）与扩散模型的新方法，旨在提升文本到图像生成的质量与效率。我们引入了动态KL加权策略优化扩散过程，并利用预训练LLMs的语义理解指导图像生成。该方法显著提升了生成图像的视觉质量与文本对齐度，有效解决了计算效率低、训练不稳定及文本变化鲁棒性等问题。在COCO数据集上的实验表明，该方法在定量与定性评估中均优于传统GAN模型。通过消融实验与人类评估，我们证实了该方法在图像真实性、文本相关性及美学质量上的优势。此外，该方法在多模态任务中展现出良好的可扩展性，为广泛的生成应用提供了多功能解决方案。

> In this paper, we presents a novel method for improving text-to-image generation by combining Large Language Models (LLMs) with diffusion models, a hybrid approach aimed at achieving both higher quality and efficiency in image synthesis from text descriptions. Our approach introduces a new dynamic KL-weighting strategy to optimize the diffusion process, along with incorporating semantic understanding from pre-trained LLMs to guide the generation process. The proposed method significantly improves both the visual quality and alignment of generated images with text descriptions, addressing challenges such as computational inefficiency, instability in training, and robustness to textual variability. We evaluate our method on the COCO dataset and demonstrate its superior performance over traditional GAN-based models, both quantitatively and qualitatively. Extensive experiments, including ablation studies and human evaluations, confirm that our method outperforms existing approaches in terms of image realism, relevance to the input text, and overall aesthetic quality. Our approach also shows promise in scalability to other multimodal tasks, making it a versatile solution for a wide range of generative applications.

[Arxiv](https://arxiv.org/abs/2502.00826)