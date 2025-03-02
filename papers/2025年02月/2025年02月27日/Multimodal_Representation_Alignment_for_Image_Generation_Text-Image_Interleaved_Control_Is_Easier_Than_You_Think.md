# # 多模态表征对齐在图像生成中的应用：文本-图像交错控制比你想象的更简单
多模态表征对齐在图像生成中的应用：文本-图像交错控制比你想象的更简单

发布时间：2025年02月27日

`LLM应用` `人工智能` `多模态学习`

> Multimodal Representation Alignment for Image Generation: Text-Image Interleaved Control Is Easier Than You Think

# 摘要

> 高级文本到图像生成领域正见证着统一框架的出现，这些框架整合了强大的文本编码器（如CLIP和T5）与扩散模型主干。尽管已有尝试通过附加条件（如边缘检测图和深度图）来控制输出图像，但目前仍缺乏一个全面的框架，能够实现任意文本与图像的交错控制。这种差距在尝试将多个图像的概念或视觉元素融合到生成过程中时尤为明显。

为弥补这一差距，我们进行了初步实验，发现大型多模态模型（LMMs）提供了一个有效的共享表示空间，在此空间中，图像和文本能够良好对齐，从而作为外部扩散模型的条件。基于这一发现，我们提出了Dream Engine——一个高效且统一的框架，专为图像生成模型中任意文本与图像的交错控制而设计。

基于强大的文本到图像模型如SD3.5，我们替换了原有的纯文本编码器，引入了 versatile 多模态信息编码器，如QwenVL。我们的方法采用了一个两阶段训练范式，包括联合文本-图像对齐和多模态交错指令微调。

实验结果表明，我们的训练方法有效，在GenEval基准上取得了0.69的总体评分，并达到了与当前最先进的文本到图像模型（如SD3.5和FLUX）相当的性能水平。


> The field of advanced text-to-image generation is witnessing the emergence of unified frameworks that integrate powerful text encoders, such as CLIP and T5, with Diffusion Transformer backbones. Although there have been efforts to control output images with additional conditions, like canny and depth map, a comprehensive framework for arbitrary text-image interleaved control is still lacking. This gap is especially evident when attempting to merge concepts or visual elements from multiple images in the generation process. To mitigate the gap, we conducted preliminary experiments showing that large multimodal models (LMMs) offer an effective shared representation space, where image and text can be well-aligned to serve as a condition for external diffusion models. Based on this discovery, we propose Dream Engine, an efficient and unified framework designed for arbitrary text-image interleaved control in image generation models. Building on powerful text-to-image models like SD3.5, we replace the original text-only encoders by incorporating versatile multimodal information encoders such as QwenVL. Our approach utilizes a two-stage training paradigm, consisting of joint text-image alignment and multimodal interleaved instruction tuning. Our experiments demonstrate that this training method is effective, achieving a 0.69 overall score on the GenEval benchmark, and matching the performance of state-of-the-art text-to-image models like SD3.5 and FLUX.

[Arxiv](https://arxiv.org/abs/2502.20172)