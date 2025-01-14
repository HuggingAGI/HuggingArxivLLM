# GestLLM：基于大型语言模型的高级手势解析，助力人机交互

发布时间：2025年01月13日

`LLM应用

理由：这篇论文介绍了 GestLLM，一个结合大型语言模型（LLM）和手势识别技术的人机交互系统。该系统利用 LLM 的能力来解析多样化的手势，从而提升机器人控制的自然性和包容性。虽然涉及手势识别和机器人控制，但其核心创新在于利用 LLM 的能力来增强系统的灵活性和性能，因此属于 LLM 在具体应用场景中的应用。` `机器人` `人机交互`

> GestLLM: Advanced Hand Gesture Interpretation via Large Language Models for Human-Robot Interaction

# 摘要

> 本文介绍了 GestLLM，一种通过手势实现直观机器人控制的先进人机交互系统。与传统系统依赖有限预定义手势不同，GestLLM 结合大型语言模型和 MediaPipe 特征提取技术，能够解析多样化的手势，解决了现有系统在手势灵活性和复杂手势识别上的不足。
    通过融合前沿的特征提取与语言模型能力，GestLLM 不仅达到了与顶尖视觉语言模型相当的性能，还支持传统数据集中罕见的手势，如《星际迷航》中的“瓦肯举手礼”，且无需额外预训练或提示工程。这种灵活性显著提升了机器人控制的自然性和包容性，使交互更加直观和友好。
    GestLLM 在手势交互领域迈出了重要一步，使机器人能够高效理解并响应多种手势。本文详细阐述了其设计、实现与评估，展示了其在高级人机协作、辅助机器人及互动娱乐中的广阔应用前景。

> This paper introduces GestLLM, an advanced system for human-robot interaction that enables intuitive robot control through hand gestures. Unlike conventional systems, which rely on a limited set of predefined gestures, GestLLM leverages large language models and feature extraction via MediaPipe to interpret a diverse range of gestures. This integration addresses key limitations in existing systems, such as restricted gesture flexibility and the inability to recognize complex or unconventional gestures commonly used in human communication.
  By combining state-of-the-art feature extraction and language model capabilities, GestLLM achieves performance comparable to leading vision-language models while supporting gestures underrepresented in traditional datasets. For example, this includes gestures from popular culture, such as the ``Vulcan salute" from Star Trek, without any additional pretraining, prompt engineering, etc. This flexibility enhances the naturalness and inclusivity of robot control, making interactions more intuitive and user-friendly.
  GestLLM provides a significant step forward in gesture-based interaction, enabling robots to understand and respond to a wide variety of hand gestures effectively. This paper outlines its design, implementation, and evaluation, demonstrating its potential applications in advanced human-robot collaboration, assistive robotics, and interactive entertainment.

[Arxiv](https://arxiv.org/abs/2501.07295)