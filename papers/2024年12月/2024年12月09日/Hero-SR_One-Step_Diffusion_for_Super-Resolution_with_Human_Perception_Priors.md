# Hero-SR：基于人类感知先验的超分辨率一步扩散法

发布时间：2024年12月09日

`其他` `图像超分辨率` `计算机视觉`

> Hero-SR: One-Step Diffusion for Super-Resolution with Human Perception Priors

# 摘要

> 由于扩散模型具有强大的先验优势，近来的一些方法在解决现实世界超分辨率（Real-SR）问题上展现出良好前景。然而，要达到语义一致和感知自然，从而满足人类的感知需求，依旧困难重重，尤其是在严重退化以及输入复杂多变的情况下。为此，我们提出了 Hero-SR，这是一个基于人类感知先验专门设计的一步扩散式超分辨率框架。Hero-SR 包含两个新颖的模块：动态时间步长模块（DTSM），它能自适应地选取最优扩散步长，灵活满足人类的感知标准；开放世界多模态监督（OWMS），它通过 CLIP 整合来自图像和文本领域的引导，提升语义一致性和感知自然性。借助这些模块，Hero-SR 生成的高分辨率图像不仅能保留精细细节，还能反映人类的感知偏好。大量实验证实 Hero-SR 在 Real-SR 中达到了领先水平。论文被接收后，代码将公开。

> Owing to the robust priors of diffusion models, recent approaches have shown promise in addressing real-world super-resolution (Real-SR). However, achieving semantic consistency and perceptual naturalness to meet human perception demands remains difficult, especially under conditions of heavy degradation and varied input complexities. To tackle this, we propose Hero-SR, a one-step diffusion-based SR framework explicitly designed with human perception priors. Hero-SR consists of two novel modules: the Dynamic Time-Step Module (DTSM), which adaptively selects optimal diffusion steps for flexibly meeting human perceptual standards, and the Open-World Multi-modality Supervision (OWMS), which integrates guidance from both image and text domains through CLIP to improve semantic consistency and perceptual naturalness. Through these modules, Hero-SR generates high-resolution images that not only preserve intricate details but also reflect human perceptual preferences. Extensive experiments validate that Hero-SR achieves state-of-the-art performance in Real-SR. The code will be publicly available upon paper acceptance.

[Arxiv](https://arxiv.org/abs/2412.07152)