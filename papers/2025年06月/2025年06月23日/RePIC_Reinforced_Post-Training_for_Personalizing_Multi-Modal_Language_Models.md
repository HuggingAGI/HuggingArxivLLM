# # RePIC：强化训练助力多模态语言模型个性化

发布时间：2025年06月23日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型（MLLMs）在生成个性化图片描述中的应用，特别是提出了基于强化学习（RL）的后训练框架来提升模型性能。这属于LLM的应用层面，因为研究集中在如何改进模型在特定任务中的表现，而不是探讨LLM的理论基础或机制。` `计算机视觉` `多模态模型`

> RePIC: Reinforced Post-Training for Personalizing Multi-Modal Language Models

# 摘要

> 近期的多模态大型语言模型（MLLMs）在生成个性化图片描述时常常遇到困难，即便是在高质量描述的基础上进行训练。在这项研究中，我们发现现有的基于后训练的MLLM个性化方法也存在同样的局限性。具体来说，尽管通过监督微调（SFT）使用大规模描述数据进行了后训练，但这些模型在现实场景中，如多概念图片描述，仍然难以生成忠实的描述。然而，在这种复杂场景下获取大规模、高质量的描述既昂贵又困难。为了解决SFT的数据中心性质，我们提出了一种基于强化学习（RL）的后训练框架。据我们所知，这是首个基于RL的用于个性化图片描述的MLLM后训练方法。我们的方法显著提升了MLLM的视觉识别和个性化生成能力，并在具有挑战性的多概念图片描述任务中，始终超越现有的基于SFT的基线方法。

> Recent multi-modal large language models (MLLMs) often struggle to generate personalized image captions, even when trained on high-quality captions. In this work, we observe that such limitations persist in existing post-training-based MLLM personalization methods. Specifically, despite being post-tuned with large-scale caption data through supervised fine-tuning (SFT), these models frequently fail to produce faithful descriptions in real-world scenarios, such as multi-concept image captioning. However, acquiring large-scale, high-quality captions for such complex settings is both costly and difficult. To address the data-centric nature of SFT, we propose a reinforcement learning (RL)-based post-training framework. To the best of our knowledge, this is the first RL-based approach to post-train MLLMs for personalized image captioning. Our method significantly enhances both visual recognition and personalized generation capabilities of MLLMs, and consistently outperforms existing SFT-based baselines, especially in the challenging multi-concept image captioning task.

[Arxiv](https://arxiv.org/abs/2506.18369)