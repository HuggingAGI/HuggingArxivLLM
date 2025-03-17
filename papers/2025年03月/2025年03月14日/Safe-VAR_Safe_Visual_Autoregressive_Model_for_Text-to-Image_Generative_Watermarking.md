# Safe-VAR：安全的视觉自回归模型用于文本到图像的生成式水印

发布时间：2025年03月14日

`LLM应用` `计算机视觉`

> Safe-VAR: Safe Visual Autoregressive Model for Text-to-Image Generative Watermarking

# 摘要

> 自回归学习在大型语言模型中的成功使其成为文本到图像生成的主导方法，提供了高效和高质量的视觉效果。然而，尽管在防止滥用方面具有重要意义，但对于视觉自回归 (VAR) 模型的不可见水印技术仍鲜有探索。现有的水印方法，主要针对扩散模型设计，往往难以适应 VAR 模型的序列特性。为填补这一空白，我们提出了 Safe-VAR，首个专为自回归文本到图像生成设计的水印框架。研究发现，水印注入的时间对生成质量影响显著，且不同复杂度的水印具有不同的最佳注入时机。基于此观察，我们提出了一种自适应尺度交互模块，该模块可根据水印信息和生成图像的视觉特征，动态确定最优的水印嵌入策略。这不仅确保了水印的鲁棒性，还最大限度地减少了对图像质量的影响。此外，我们引入了一种跨尺度融合机制，通过结合多分辨率特征和处理图像内容与水印图案之间的复杂交互，有效融合了头部和专家的混合特征。实验结果表明，Safe-VAR 达到了最先进的性能，显著超越现有方法在图像质量、水印保真度和抗扰动鲁棒性方面。此外，我们的方法在应用于域外水印数据集 QR 码时也表现出良好的泛化能力。

> With the success of autoregressive learning in large language models, it has become a dominant approach for text-to-image generation, offering high efficiency and visual quality. However, invisible watermarking for visual autoregressive (VAR) models remains underexplored, despite its importance in misuse prevention. Existing watermarking methods, designed for diffusion models, often struggle to adapt to the sequential nature of VAR models. To bridge this gap, we propose Safe-VAR, the first watermarking framework specifically designed for autoregressive text-to-image generation. Our study reveals that the timing of watermark injection significantly impacts generation quality, and watermarks of different complexities exhibit varying optimal injection times. Motivated by this observation, we propose an Adaptive Scale Interaction Module, which dynamically determines the optimal watermark embedding strategy based on the watermark information and the visual characteristics of the generated image. This ensures watermark robustness while minimizing its impact on image quality. Furthermore, we introduce a Cross-Scale Fusion mechanism, which integrates mixture of both heads and experts to effectively fuse multi-resolution features and handle complex interactions between image content and watermark patterns. Experimental results demonstrate that Safe-VAR achieves state-of-the-art performance, significantly surpassing existing counterparts regarding image quality, watermarking fidelity, and robustness against perturbations. Moreover, our method exhibits strong generalization to an out-of-domain watermark dataset QR Codes.

[Arxiv](https://arxiv.org/abs/2503.11324)