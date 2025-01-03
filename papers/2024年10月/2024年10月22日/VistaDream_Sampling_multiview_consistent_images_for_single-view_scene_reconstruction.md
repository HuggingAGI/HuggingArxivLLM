# VistaDream：单视图场景重建中的多视图一致图像采样

发布时间：2024年10月22日

`其他

理由：这篇论文主要讨论的是从单视角图像重建3D场景的技术，涉及扩散模型和多视角一致性采样等技术。虽然使用了扩散模型，但其核心内容与LLM（大型语言模型）无关，也不涉及Agent、RAG或LLM理论。因此，将其分类为“其他”更为合适。` `计算机视觉` `3D重建`

> VistaDream: Sampling multiview consistent images for single-view scene reconstruction

# 摘要

> # 摘要
本文提出VistaDream，一个从单视角图像重建3D场景的创新框架。现有扩散模型虽能从单视角图像生成高质量新视角图像，但大多仅关注输入与生成图像间的一致性，忽略了生成图像间的一致性。VistaDream通过两阶段流程解决这一问题：首先，通过轻微放大并修复边界与深度图，构建全局粗略3D支架；随后，基于该支架，利用迭代扩散的RGB-D修复生成新视角图像，填补支架孔洞。第二阶段，我们引入无训练的多视角一致性采样（MCS），在扩散模型的反向采样中引入多视角一致性约束，进一步提升生成图像间的一致性。实验表明，VistaDream无需训练或微调现有扩散模型，仅凭单视角图像即可实现一致且高质量的新视角合成，显著优于基线方法。代码、视频及交互演示详见：https URL。

> 
Abstract:In this paper, we propose VistaDream a novel framework to reconstruct a 3D scene from a single-view image. Recent diffusion models enable generating high-quality novel-view images from a single-view input image. Most existing methods only concentrate on building the consistency between the input image and the generated images while losing the consistency between the generated images. VistaDream addresses this problem by a two-stage pipeline. In the first stage, VistaDream begins with building a global coarse 3D scaffold by zooming out a little step with inpainted boundaries and an estimated depth map. Then, on this global scaffold, we use iterative diffusion-based RGB-D inpainting to generate novel-view images to inpaint the holes of the scaffold. In the second stage, we further enhance the consistency between the generated novel-view images by a novel training-free Multiview Consistency Sampling (MCS) that introduces multi-view consistency constraints in the reverse sampling process of diffusion models. Experimental results demonstrate that without training or fine-tuning existing diffusion models, VistaDream achieves consistent and high-quality novel view synthesis using just single-view images and outperforms baseline methods by a large margin. The code, videos, and interactive demos are available at this https URL.
    

[Arxiv](https://arxiv.org/pdf/2410.16892)