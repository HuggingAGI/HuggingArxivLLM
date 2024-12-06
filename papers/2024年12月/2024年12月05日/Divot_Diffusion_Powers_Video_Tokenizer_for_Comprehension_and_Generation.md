# Divot：用于理解与生成的扩散驱动式视频标记器

发布时间：2024年12月05日

`LLM应用` `人工智能`

> Divot: Diffusion Powers Video Tokenizer for Comprehension and Generation

# 摘要

> 近年来，在大型语言模型（LLMs）中统一图像理解与生成的兴趣大幅攀升。这一不断高涨的兴趣促使我们探索将这种统一拓展至视频领域。其核心难题在于研发一种通用的视频标记器，既能捕捉视频的空间特性又能把握时间动态，从而为LLMs获取表示，且这些表示还能进一步解码为逼真的视频片段，以实现视频生成。在本研究中，我们推出了Divot，一种由扩散驱动的视频标记器，它借助扩散过程开展自监督视频表示学习。我们认为，倘若视频扩散模型能以视频标记器的特征为条件，对视频片段有效去噪，那么该标记器就成功捕获了强大的空间和时间信息。此外，视频扩散模型本质上充当着去标记器，能从其表示中解码出视频。基于Divot标记器，我们通过视频到文本的自回归以及文本到视频的生成，采用高斯混合模型对连续值的Divot特征分布进行建模，提出了Divot-Vicuna。实验结果表明，我们基于扩散的视频标记器与预先训练的LLM集成后，在各类视频理解和生成基准测试中取得了颇具竞争力的性能。经过指令调整的Divot-Vicuna在视频叙事方面也表现卓越，能生成交错的叙述及相应的视频。

> In recent years, there has been a significant surge of interest in unifying image comprehension and generation within Large Language Models (LLMs). This growing interest has prompted us to explore extending this unification to videos. The core challenge lies in developing a versatile video tokenizer that captures both the spatial characteristics and temporal dynamics of videos to obtain representations for LLMs, and the representations can be further decoded into realistic video clips to enable video generation. In this work, we introduce Divot, a Diffusion-Powered Video Tokenizer, which leverages the diffusion process for self-supervised video representation learning. We posit that if a video diffusion model can effectively de-noise video clips by taking the features of a video tokenizer as the condition, then the tokenizer has successfully captured robust spatial and temporal information. Additionally, the video diffusion model inherently functions as a de-tokenizer, decoding videos from their representations. Building upon the Divot tokenizer, we present Divot-Vicuna through video-to-text autoregression and text-to-video generation by modeling the distributions of continuous-valued Divot features with a Gaussian Mixture Model. Experimental results demonstrate that our diffusion-based video tokenizer, when integrated with a pre-trained LLM, achieves competitive performance across various video comprehension and generation benchmarks. The instruction tuned Divot-Vicuna also excels in video storytelling, generating interleaved narratives and corresponding videos.

[Arxiv](https://arxiv.org/abs/2412.04432)