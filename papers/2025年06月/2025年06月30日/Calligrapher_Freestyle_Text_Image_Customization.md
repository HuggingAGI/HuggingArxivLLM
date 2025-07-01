# # 书法大师: 自由定制文本图像

发布时间：2025年06月30日

`LLM应用` `数字艺术`

> Calligrapher: Freestyle Text Image Customization

# 摘要

> 我们推出了一款创新的扩散模型框架Calligrapher，它巧妙地结合了先进的文本自动生成与艺术排版，专为数字书法与设计应用而生。针对排版定制中的精确风格控制和数据依赖性挑战，我们的框架集成了三项核心技术。首先，我们开发了一种自我蒸馏机制，它结合预训练的文本到图像生成模型和大型语言模型，自动构建以风格为中心的排版基准。其次，我们引入了通过可训练的风格编码器实现的局部风格注入框架，该编码器包含Qformer和线性层，能够从参考图像中提取鲁棒的风格特征。此外，我们还采用了上下文生成机制，直接将参考图像嵌入去噪过程中，进一步提升目标风格的精准对齐。在多样字体和设计场景下的广泛定量和定性评估证实，Calligrapher能够准确再现复杂的风格细节和精确的字符定位。通过实现高质量且视觉一致的自动化排版，Calligrapher超越了传统模型，为数字艺术、品牌设计和情境化排版设计的创意从业者提供了强大助力。


> We introduce Calligrapher, a novel diffusion-based framework that innovatively integrates advanced text customization with artistic typography for digital calligraphy and design applications. Addressing the challenges of precise style control and data dependency in typographic customization, our framework incorporates three key technical contributions. First, we develop a self-distillation mechanism that leverages the pre-trained text-to-image generative model itself alongside the large language model to automatically construct a style-centric typography benchmark. Second, we introduce a localized style injection framework via a trainable style encoder, which comprises both Qformer and linear layers, to extract robust style features from reference images. An in-context generation mechanism is also employed to directly embed reference images into the denoising process, further enhancing the refined alignment of target styles. Extensive quantitative and qualitative evaluations across diverse fonts and design contexts confirm Calligrapher's accurate reproduction of intricate stylistic details and precise glyph positioning. By automating high-quality, visually consistent typography, Calligrapher surpasses traditional models, empowering creative practitioners in digital art, branding, and contextual typographic design.

[Arxiv](https://arxiv.org/abs/2506.24123)