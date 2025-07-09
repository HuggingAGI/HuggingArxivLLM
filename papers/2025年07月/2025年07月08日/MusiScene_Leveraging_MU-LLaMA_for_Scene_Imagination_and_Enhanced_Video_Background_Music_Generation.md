# MusiScene：借助MU-LLaMA实现场景想象与视频背景音乐优化生成

发布时间：2025年07月08日

`LLM应用`

> MusiScene: Leveraging MU-LLaMA for Scene Imagination and Enhanced Video Background Music Generation

# 摘要

> 人类在聆听音乐时，脑海中常会浮现出与之相契合的场景，仿佛在观看一部电影。比如，慢节奏的忧郁旋律让人联想到心碎的画面，而轻快的曲调则让人感受到欢庆的氛围。本文探讨了音乐语言模型（如MU-LLaMA）能否完成类似的“音乐场景想象”（MSI）任务，这一任务需要结合视频和音乐的跨模态信息进行训练。为了超越现有仅关注音乐元素的描述模型，我们开发了MusiScene，一个能为音乐生成相辅相成场景描述的模型。在本文中，我们(1) 构建了一个包含3,371对数据的大规模视频-音频描述数据集，(2) 对音乐理解的LLaMA进行了微调，打造了专注于MSI任务的MusiScene模型，(3) 通过全面评估证明，MusiScene在生成上下文相关的描述方面优于MU-LLaMA。我们还利用这些MSI描述来提升从文本生成视频背景音乐（VBMG）的效果。

> Humans can imagine various atmospheres and settings when listening to music, envisioning movie scenes that complement each piece. For example, slow, melancholic music might evoke scenes of heartbreak, while upbeat melodies suggest celebration. This paper explores whether a Music Language Model, e.g. MU-LLaMA, can perform a similar task, called Music Scene Imagination (MSI), which requires cross-modal information from video and music to train. To improve upon existing music captioning models which focusing solely on musical elements, we introduce MusiScene, a music captioning model designed to imagine scenes that complement each music. In this paper, (1) we construct a large-scale video-audio caption dataset with 3,371 pairs, (2) we finetune Music Understanding LLaMA for the MSI task to create MusiScene, and (3) we conduct comprehensive evaluations and prove that our MusiScene is more capable of generating contextually relevant captions compared to MU-LLaMA. We leverage the generated MSI captions to enhance Video Background Music Generation (VBMG) from text.

[Arxiv](https://arxiv.org/abs/2507.05894)