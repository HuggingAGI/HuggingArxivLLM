# POSTA：专为定制艺术海报打造的一站式生成框架

发布时间：2025年03月19日

`LLM应用`

> POSTA: A Go-to Framework for Customized Artistic Poster Generation

# 摘要

> # 海报设计：视觉传达的关键媒介

已有研究尝试利用深度学习技术实现自动化的海报设计，但这些方法在文字准确性、用户定制性和艺术吸引力方面存在不足，限制了其在电影、展览等艺术领域中的应用，这些领域需要在清晰传达内容的同时具备视觉冲击力。

为了解决这些问题，我们提出了POSTA：一个基于扩散模型和多模态大型语言模型（MLLMs）的模块化框架，用于定制化艺术海报生成。该框架包含三个模块：

1. 背景扩散模块根据用户输入生成主题背景。
2. 设计MLLM模块随后生成与背景风格一致且相辅相成的布局和字体元素。
3. 最后，为了提升海报的艺术吸引力，ArtText Diffusion模块对关键文字元素进行额外的风格化处理。

最终生成的海报视觉上高度统一且吸引人，整个模块化流程允许完全定制。

为了训练我们的模型，我们开发了PosterArt数据集，包含带有布局、字体和像素级风格化文本分割标注的高质量艺术海报。

我们的综合实验分析表明，POSTA在可控性和设计多样性方面表现卓越，在文字准确性和美学质量上均优于现有模型。


> Poster design is a critical medium for visual communication. Prior work has explored automatic poster design using deep learning techniques, but these approaches lack text accuracy, user customization, and aesthetic appeal, limiting their applicability in artistic domains such as movies and exhibitions, where both clear content delivery and visual impact are essential. To address these limitations, we present POSTA: a modular framework powered by diffusion models and multimodal large language models (MLLMs) for customized artistic poster generation. The framework consists of three modules. Background Diffusion creates a themed background based on user input. Design MLLM then generates layout and typography elements that align with and complement the background style. Finally, to enhance the poster's aesthetic appeal, ArtText Diffusion applies additional stylization to key text elements. The final result is a visually cohesive and appealing poster, with a fully modular process that allows for complete customization. To train our models, we develop the PosterArt dataset, comprising high-quality artistic posters annotated with layout, typography, and pixel-level stylized text segmentation. Our comprehensive experimental analysis demonstrates POSTA's exceptional controllability and design diversity, outperforming existing models in both text accuracy and aesthetic quality.

[Arxiv](https://arxiv.org/abs/2503.14908)