# STEVE-Audio：拓展《我的世界》中具身智能体的目标调节方式

发布时间：2024年12月01日

`Agent` `多模态`

> STEVE-Audio: Expanding the Goal Conditioning Modalities of Embodied Agents in Minecraft

# 摘要

> 最近，STEVE-1 方法作为训练生成式代理遵循潜在 CLIP 嵌入形式指令的手段被引入。在本研究中，我们给出一种通过学习从新输入模态到代理潜在目标空间的映射来拓展控制模态的方法。我们把该方法应用于富有挑战性的 Minecraft 领域，并将目标条件拓展至涵盖音频模态。所生成的音频条件代理能够达到与原始文本条件和视觉条件代理相当的水平。具体而言，我们为 Minecraft 创建了一个音视频 CLIP 基础模型和一个音频先验网络，二者共同将音频样本映射到 STEVE-1 策略的潜在目标空间。此外，我们还强调了在不同模态条件下出现的权衡。我们的训练代码、评估代码以及 Minecraft 的音视频 CLIP 基础模型已开源，以助力推动对多模态全能型顺序决策代理的进一步研究。

> Recently, the STEVE-1 approach has been introduced as a method for training generative agents to follow instructions in the form of latent CLIP embeddings. In this work, we present a methodology to extend the control modalities by learning a mapping from new input modalities to the latent goal space of the agent. We apply our approach to the challenging Minecraft domain, and extend the goal conditioning to include the audio modality. The resulting audio-conditioned agent is able to perform on a comparable level to the original text-conditioned and visual-conditioned agents. Specifically, we create an Audio-Video CLIP foundation model for Minecraft and an audio prior network which together map audio samples to the latent goal space of the STEVE-1 policy. Additionally, we highlight the tradeoffs that occur when conditioning on different modalities. Our training code, evaluation code, and Audio-Video CLIP foundation model for Minecraft are made open-source to help foster further research into multi-modal generalist sequential decision-making agents.

[Arxiv](https://arxiv.org/abs/2412.00949)