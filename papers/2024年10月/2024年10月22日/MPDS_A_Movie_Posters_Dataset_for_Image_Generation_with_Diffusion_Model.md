# MPDS: 基于扩散模型的电影海报图像生成数据集

发布时间：2024年10月22日

`其他

理由：这篇论文主要讨论的是电影海报数据集的创建和基于该数据集的多条件扩散框架的开发，用于生成个性化电影海报。虽然涉及到了大规模视觉语言模型的使用，但核心内容并不直接涉及Agent、RAG、LLM应用或LLM理论。因此，将其分类为“其他”更为合适。` `图像生成`

> MPDS: A Movie Posters Dataset for Image Generation with Diffusion Model

# 摘要

> # 摘要
电影海报在吸引观众、传达主题和推动市场竞争中扮演着关键角色。传统设计耗时费力，而智能生成技术则带来了效率提升和设计优化。尽管图像生成领域进展显著，但现有模型在海报生成上仍不尽如人意，主要原因是缺乏专门的海报数据集。为此，我们推出了电影海报数据集（MPDS），专为文本到图像生成模型设计，旨在革新海报制作。MPDS是我们所知的首个图像-文本对数据集，包含超过37.3万对图像-文本和8000多张演员图像（涵盖4000多名演员）。海报描述如电影标题、类型、演员阵容和剧情简介，均基于公开的电影简介精心整理，称为电影简介提示。为了增强描述并减少与电影简介的差异，我们利用大规模视觉语言模型自动生成视觉感知提示，并进行人工校正与电影简介提示整合。此外，我们还引入了海报字幕提示，展示海报中的文本元素，如演员姓名和电影标题。我们开发的多条件扩散框架以海报提示、海报字幕和演员图像（用于个性化）为输入，通过扩散模型学习生成出色结果。实验表明，MPDS在推进个性化电影海报生成方面发挥了重要作用。MPDS可在https://anonymous.4open.science/r/MPDS-373k-BD3B获取。

> Movie posters are vital for captivating audiences, conveying themes, and driving market competition in the film industry. While traditional designs are laborious, intelligent generation technology offers efficiency gains and design enhancements. Despite exciting progress in image generation, current models often fall short in producing satisfactory poster results. The primary issue lies in the absence of specialized poster datasets for targeted model training. In this work, we propose a Movie Posters DataSet (MPDS), tailored for text-to-image generation models to revolutionize poster production. As dedicated to posters, MPDS stands out as the first image-text pair dataset to our knowledge, composing of 373k+ image-text pairs and 8k+ actor images (covering 4k+ actors). Detailed poster descriptions, such as movie titles, genres, casts, and synopses, are meticulously organized and standardized based on public movie synopsis, also named movie-synopsis prompt. To bolster poster descriptions as well as reduce differences from movie synopsis, further, we leverage a large-scale vision-language model to automatically produce vision-perceptive prompts for each poster, then perform manual rectification and integration with movie-synopsis prompt. In addition, we introduce a prompt of poster captions to exhibit text elements in posters like actor names and movie titles. For movie poster generation, we develop a multi-condition diffusion framework that takes poster prompt, poster caption, and actor image (for personalization) as inputs, yielding excellent results through the learning of a diffusion model. Experiments demonstrate the valuable role of our proposed MPDS dataset in advancing personalized movie poster generation. MPDS is available at https://anonymous.4open.science/r/MPDS-373k-BD3B.

[Arxiv](https://arxiv.org/abs/2410.16840)