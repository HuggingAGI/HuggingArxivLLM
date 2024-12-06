# MEMO：用于生成富有表现力的说话视频的内存引导扩散

发布时间：2024年12月05日

`其他` `视频生成` `音频处理`

> MEMO: Memory-Guided Diffusion for Expressive Talking Video Generation

# 摘要

> 近期视频扩散模型的进步为逼真的音频驱动说话视频生成开辟了新的可能。然而，在生成的说话视频里，实现无缝的音频-嘴唇同步、保持长期的身份一致性以及展现自然且与音频匹配的表情，依旧是巨大的挑战。为应对这些难题，我们提出了记忆引导的情感感知扩散（MEMO），这是一种端到端的音频驱动肖像动画方法，用于生成身份一致且富有表现力的说话视频。我们的方法构建于两个关键模块之上：（1）记忆引导的时间模块，通过开发记忆状态来存储来自更久远过去上下文的信息，借助线性注意力引导时间建模，从而提升长期身份一致性和运动平滑度；（2）情感感知音频模块，用多模态注意力取代传统交叉注意力来增强音视频交互，同时从音频中检测情感，通过情感自适应层范数来优化面部表情。大量的定量和定性结果显示，MEMO 在各种图像和音频类型中生成的说话视频更逼真，在整体质量、音频-嘴唇同步、身份一致性以及表情-情感对齐方面，都超越了最先进的方法。

> Recent advances in video diffusion models have unlocked new potential for realistic audio-driven talking video generation. However, achieving seamless audio-lip synchronization, maintaining long-term identity consistency, and producing natural, audio-aligned expressions in generated talking videos remain significant challenges. To address these challenges, we propose Memory-guided EMOtion-aware diffusion (MEMO), an end-to-end audio-driven portrait animation approach to generate identity-consistent and expressive talking videos. Our approach is built around two key modules: (1) a memory-guided temporal module, which enhances long-term identity consistency and motion smoothness by developing memory states to store information from a longer past context to guide temporal modeling via linear attention; and (2) an emotion-aware audio module, which replaces traditional cross attention with multi-modal attention to enhance audio-video interaction, while detecting emotions from audio to refine facial expressions via emotion adaptive layer norm. Extensive quantitative and qualitative results demonstrate that MEMO generates more realistic talking videos across diverse image and audio types, outperforming state-of-the-art methods in overall quality, audio-lip synchronization, identity consistency, and expression-emotion alignment.

[Arxiv](https://arxiv.org/abs/2412.04448)