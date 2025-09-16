# # 自己动手（DIY）：零样本场景下通过加权提示词操控为诗歌修改图像

发布时间：2025年09月15日

`LLM应用` `媒体与娱乐`

> Do It Yourself (DIY): Modifying Images for Poems in a Zero-Shot Setting Using Weighted Prompt Manipulation

# 摘要

> 诗歌作为富有表现力的艺术形式，本身就充满了多重解读的可能——读者总会带着自己的情感、经历与文化背景去理解诗句。正因如此，我们希望为诗歌生成图像，并在零样本场景下对图像进行优化，让观众能按需调整图像。为此，我们提出了全新的加权提示操纵（WPM）技术，它能系统性地调整扩散模型中的注意力权重与文本嵌入。WPM通过动态调整特定词语的权重，增强或削弱它们在最终生成图像中的影响力，进而得到语义更丰富、语境更精准的视觉效果。我们的方法将扩散模型、大型语言模型（如GPT）与现有诗歌数据集相结合，为文学领域的图像生成改进提供了全面且结构化的方案。据我们所知，这是首次通过整合加权提示操纵来增强诗歌语言的图像表现力。

> Poetry is an expressive form of art that invites multiple interpretations, as readers often bring their own emotions, experiences, and cultural backgrounds into their understanding of a poem. Recognizing this, we aim to generate images for poems and improve these images in a zero-shot setting, enabling audiences to modify images as per their requirements. To achieve this, we introduce a novel Weighted Prompt Manipulation (WPM) technique, which systematically modifies attention weights and text embeddings within diffusion models. By dynamically adjusting the importance of specific words, WPM enhances or suppresses their influence in the final generated image, leading to semantically richer and more contextually accurate visualizations. Our approach exploits diffusion models and large language models (LLMs) such as GPT in conjunction with existing poetry datasets, ensuring a comprehensive and structured methodology for improved image generation in the literary domain. To the best of our knowledge, this is the first attempt at integrating weighted prompt manipulation for enhancing imagery in poetic language.

[Arxiv](https://arxiv.org/abs/2509.11878)