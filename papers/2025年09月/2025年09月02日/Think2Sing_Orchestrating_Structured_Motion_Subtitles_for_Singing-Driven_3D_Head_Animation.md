# Think2Sing：面向歌唱驱动3D头部动画的结构化运动字幕编排

发布时间：2025年09月02日

`LLM应用` `媒体与娱乐` `教育科技`

> Think2Sing: Orchestrating Structured Motion Subtitles for Singing-Driven 3D Head Animation

# 摘要

> 歌唱驱动的3D头部动画是一项极具挑战却前景广阔的任务，在虚拟化身、娱乐及教育领域有着广泛应用。与语音不同，歌唱蕴含更丰富的情感意蕴、动态韵律及歌词语义，因此需要合成细粒度、时间连贯的面部动作。现有的语音驱动方法往往生成过于简化、情感单调且语义脱节的结果，难以满足歌唱动画的需求。为此，我们提出Think2Sing——一个基于扩散的框架，它借助预训练大型语言模型，以歌词和声学为条件，生成语义连贯且时间一致的3D头部动画。核心创新点在于引入了“运动字幕”——一种通过全新的“歌唱思维链”推理过程结合声学引导检索得到的辅助语义表示。这些字幕包含精确时间戳和区域化动作描述，可作为可解释的动作先验。我们将任务转化为运动强度预测问题，不仅实现对面部区域的更精细控制，还能提升富有表现力动作的建模效果。为支持该框架，我们构建了一个多模态歌唱数据集，包含同步视频、声学描述符和运动字幕，助力多样化、富有表现力的动作学习。大量实验表明，Think2Sing在真实感、表现力和情感保真度上均超越现有最先进方法，同时还支持灵活的用户可控动画编辑。

> Singing-driven 3D head animation is a challenging yet promising task with applications in virtual avatars, entertainment, and education. Unlike speech, singing involves richer emotional nuance, dynamic prosody, and lyric-based semantics, requiring the synthesis of fine-grained, temporally coherent facial motion. Existing speech-driven approaches often produce oversimplified, emotionally flat, and semantically inconsistent results, which are insufficient for singing animation. To address this, we propose Think2Sing, a diffusion-based framework that leverages pretrained large language models to generate semantically coherent and temporally consistent 3D head animations, conditioned on both lyrics and acoustics. A key innovation is the introduction of motion subtitles, an auxiliary semantic representation derived through a novel Singing Chain-of-Thought reasoning process combined with acoustic-guided retrieval. These subtitles contain precise timestamps and region-specific motion descriptions, serving as interpretable motion priors. We frame the task as a motion intensity prediction problem, enabling finer control over facial regions and improving the modeling of expressive motion. To support this, we create a multimodal singing dataset with synchronized video, acoustic descriptors, and motion subtitles, enabling diverse and expressive motion learning. Extensive experiments show that Think2Sing outperforms state-of-the-art methods in realism, expressiveness, and emotional fidelity, while also offering flexible, user-controllable animation editing.

[Arxiv](https://arxiv.org/abs/2509.02278)