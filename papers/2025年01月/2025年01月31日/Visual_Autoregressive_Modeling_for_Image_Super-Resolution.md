# 视觉自回归建模：图像超分辨率的新方法

发布时间：2025年01月31日

`其他

理由：这篇论文主要讨论的是图像超分辨率（ISR）技术，特别是提出了一种新的视觉自回归建模方法（VARSR）。虽然论文中提到了自回归模型在语言领域的成功，但主要内容集中在图像处理领域，与LLM（大型语言模型）、Agent（智能体）、RAG（检索增强生成）等主题无关。因此，将其分类为“其他”更为合适。` `图像处理` `计算机视觉`

> Visual Autoregressive Modeling for Image Super-Resolution

# 摘要

> # 图像超分辨率（ISR）在引入卓越的生成模型后取得了显著进展。然而，保真度与真实感之间的权衡问题以及计算复杂性等挑战也限制了其应用。基于自回归模型在语言领域的巨大成功，我们提出了 	extbf{VARSR}，一种新颖的视觉自回归建模方法，用于 ISR 框架，采用下一尺度预测的形式。为了有效整合和保留低分辨率图像中的语义信息，我们提出使用前缀标记来引入条件。引入了尺度对齐的旋转位置编码以捕捉空间结构，并利用扩散细化器来建模量化残差损失，以实现像素级保真度。提出了基于图像的无分类器引导，以指导生成更真实的图像。此外，我们收集了大规模数据并设计了训练过程，以获得鲁棒的生成先验。定量和定性结果表明，VARSR 能够生成高保真和高真实感的图像，并且比基于扩散的方法更高效。我们的代码将在 https://github.com/qyp2000/VARSR 发布。

> Image Super-Resolution (ISR) has seen significant progress with the introduction of remarkable generative models. However, challenges such as the trade-off issues between fidelity and realism, as well as computational complexity, have also posed limitations on their application. Building upon the tremendous success of autoregressive models in the language domain, we propose \textbf{VARSR}, a novel visual autoregressive modeling for ISR framework with the form of next-scale prediction. To effectively integrate and preserve semantic information in low-resolution images, we propose using prefix tokens to incorporate the condition. Scale-aligned Rotary Positional Encodings are introduced to capture spatial structures and the diffusion refiner is utilized for modeling quantization residual loss to achieve pixel-level fidelity. Image-based Classifier-free Guidance is proposed to guide the generation of more realistic images. Furthermore, we collect large-scale data and design a training process to obtain robust generative priors. Quantitative and qualitative results show that VARSR is capable of generating high-fidelity and high-realism images with more efficiency than diffusion-based methods. Our codes will be released at https://github.com/qyp2000/VARSR.

[Arxiv](https://arxiv.org/abs/2501.18993)