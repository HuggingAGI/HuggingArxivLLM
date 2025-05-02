# V3LMA：视觉3D增强语言模型，应用于自动驾驶

发布时间：2025年04月30日

`LLM应用` `自动驾驶` `计算机视觉`

> V3LMA: Visual 3D-enhanced Language Model for Autonomous Driving

# 摘要

> 大型视觉语言模型（LVLMs）在跨领域视觉理解和分析方面表现出色。然而，它们在自动驾驶中对三维环境的理解能力有限，影响了对动态环境的全面安全感知。为解决这一问题，我们提出了V3LMA——一种结合大型语言模型（LLMs）与LVLMs来增强三维场景理解的新方法。V3LMA通过利用基于目标检测和视频输入生成的文本描述，显著提升了性能，无需微调。通过专门的预处理管道提取三维物体数据，我们的方法在复杂交通场景中提升了环境感知和决策能力，在LingoQA基准测试中达到了0.56的分数。我们进一步探索了不同的融合策略和token组合，以推动交通场景解读，最终实现更安全的自动驾驶系统。

> Large Vision Language Models (LVLMs) have shown strong capabilities in understanding and analyzing visual scenes across various domains. However, in the context of autonomous driving, their limited comprehension of 3D environments restricts their effectiveness in achieving a complete and safe understanding of dynamic surroundings. To address this, we introduce V3LMA, a novel approach that enhances 3D scene understanding by integrating Large Language Models (LLMs) with LVLMs. V3LMA leverages textual descriptions generated from object detections and video inputs, significantly boosting performance without requiring fine-tuning. Through a dedicated preprocessing pipeline that extracts 3D object data, our method improves situational awareness and decision-making in complex traffic scenarios, achieving a score of 0.56 on the LingoQA benchmark. We further explore different fusion strategies and token combinations with the goal of advancing the interpretation of traffic scenes, ultimately enabling safer autonomous driving systems.

[Arxiv](https://arxiv.org/abs/2505.00156)