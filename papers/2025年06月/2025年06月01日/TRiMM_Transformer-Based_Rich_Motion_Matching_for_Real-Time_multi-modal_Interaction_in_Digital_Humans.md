# TRiMM: 基于Transformer的丰富运动匹配，实现数字人类中实时多模态交互

发布时间：2025年06月01日

`LLM应用` `数字人` `手势生成`

> TRiMM: Transformer-Based Rich Motion Matching for Real-Time multi-modal Interaction in Digital Humans

# 摘要

> 基于大型语言模型（LLM）的数字人近期引发了协同手势生成系统的诸多研究。然而，现有方法在实时合成和长文本理解方面仍面临挑战。本文提出了一种基于Transformer的丰富动作匹配（TRiMM），这是一种用于实时3D手势生成的创新多模态框架。我们的方法整合了以下三个核心模块：1）跨模态注意力机制，实现语音与手势的精准时间对齐；2）长上下文自回归模型，配以滑动窗口机制，提升序列建模效果；3）大规模动作匹配系统，构建原子动作库并支持实时检索。此外，我们开发了一个在Unreal Engine中实现的轻量级实验管线。实验结果表明，我们的方法在消费级GPU（Geforce RTX3060）上实现了120 fps的实时推理，每句话延迟仅0.15秒。在ZEGGS和BEAT数据集上的广泛主观和客观评估均表明，我们的模型优于当前最先进的方法。TRiMM不仅提升了协同手势生成的速度，还保证了手势质量，使LLM驱动的数字人能够实时响应语音并生成相应的手势。我们的代码可在https://github.com/teroon/TRiMM-Transformer-Based-Rich-Motion-Matching获取。

> Large Language Model (LLM)-driven digital humans have sparked a series of recent studies on co-speech gesture generation systems. However, existing approaches struggle with real-time synthesis and long-text comprehension. This paper introduces Transformer-Based Rich Motion Matching (TRiMM), a novel multi-modal framework for real-time 3D gesture generation. Our method incorporates three modules: 1) a cross-modal attention mechanism to achieve precise temporal alignment between speech and gestures; 2) a long-context autoregressive model with a sliding window mechanism for effective sequence modeling; 3) a large-scale gesture matching system that constructs an atomic action library and enables real-time retrieval. Additionally, we develop a lightweight pipeline implemented in the Unreal Engine for experimentation. Our approach achieves real-time inference at 120 fps and maintains a per-sentence latency of 0.15 seconds on consumer-grade GPUs (Geforce RTX3060). Extensive subjective and objective evaluations on the ZEGGS, and BEAT datasets demonstrate that our model outperforms current state-of-the-art methods. TRiMM enhances the speed of co-speech gesture generation while ensuring gesture quality, enabling LLM-driven digital humans to respond to speech in real time and synthesize corresponding gestures. Our code is available at https://github.com/teroon/TRiMM-Transformer-Based-Rich-Motion-Matching

[Arxiv](https://arxiv.org/abs/2506.01077)