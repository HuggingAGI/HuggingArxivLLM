# 思而后画：情感语义分解与细粒度可控的表情说话头生成

发布时间：2025年07月16日

`LLM应用` `计算机视觉` `多模态人工智能`

> Think-Before-Draw: Decomposing Emotion Semantics & Fine-Grained Controllable Expressive Talking Head Generation

# 摘要

> 情感对话头生成作为计算机视觉与多模态人工智能交叉领域的重要研究方向，其核心价值在于通过沉浸式且富有同理心的交互来提升人机交互体验。随着多模态大语言模型的发展，情感对话头生成的驱动信号已从音频和视频转向更为灵活的文本。然而，当前基于文本的方法依赖于预定义的离散情绪标签文本，这过于简化了真实面部肌肉运动的动态复杂性，因而难以实现自然的情感表达。本研究提出了“先思后画”（Think-Before-Draw）框架，旨在解决以下两个关键挑战：（1）情绪的深度语义解析——通过创新性地引入思维链（Chain-of-Thought, CoT），将抽象的情绪标签转化为具有生理基础的面部肌肉运动描述，从而实现从高层次语义到可操作运动特征的映射；（2）表达精细度的优化——受艺术家肖像画创作过程启发，提出了一种渐进式引导去噪策略，采用“全局情绪定位——局部肌肉控制”机制，以优化生成视频中的微表情动态。实验结果表明，我们的方法在MEAD和HDTF等广泛使用的基准数据集上达到了当前最优性能。此外，我们还收集了一组肖像图像来评估模型的零样本生成能力。

> Emotional talking-head generation has emerged as a pivotal research area at the intersection of computer vision and multimodal artificial intelligence, with its core value lying in enhancing human-computer interaction through immersive and empathetic engagement.With the advancement of multimodal large language models, the driving signals for emotional talking-head generation has shifted from audio and video to more flexible text. However, current text-driven methods rely on predefined discrete emotion label texts, oversimplifying the dynamic complexity of real facial muscle movements and thus failing to achieve natural emotional expressiveness.This study proposes the Think-Before-Draw framework to address two key challenges: (1) In-depth semantic parsing of emotions--by innovatively introducing Chain-of-Thought (CoT), abstract emotion labels are transformed into physiologically grounded facial muscle movement descriptions, enabling the mapping from high-level semantics to actionable motion features; and (2) Fine-grained expressiveness optimization--inspired by artists' portrait painting process, a progressive guidance denoising strategy is proposed, employing a "global emotion localization--local muscle control" mechanism to refine micro-expression dynamics in generated videos.Our experiments demonstrate that our approach achieves state-of-the-art performance on widely-used benchmarks, including MEAD and HDTF. Additionally, we collected a set of portrait images to evaluate our model's zero-shot generation capability.

[Arxiv](https://arxiv.org/abs/2507.12761)