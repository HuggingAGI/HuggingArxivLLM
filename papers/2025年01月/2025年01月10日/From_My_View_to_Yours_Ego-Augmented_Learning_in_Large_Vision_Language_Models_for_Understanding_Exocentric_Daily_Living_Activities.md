# 从我的视角到你的视角：大型视觉语言模型中的自我增强学习助力外中心日常生活活动理解

发布时间：2025年01月10日

`LLM应用

理由：这篇论文主要讨论了如何利用大型视觉语言模型（LVLMs）来增强对日常生活活动（ADL）视频的理解，特别是在老年监护和认知评估等应用中。论文提出了一种新的方法（EgoMimic）来生成模拟的自我视角，以增强LVLM的表现。虽然涉及视觉语言模型，但其核心应用场景和解决的问题属于LLM在实际应用中的扩展和优化，因此归类为“LLM应用”。` `老年监护` `认知评估`

> From My View to Yours: Ego-Augmented Learning in Large Vision Language Models for Understanding Exocentric Daily Living Activities

# 摘要

> # 摘要
大型视觉语言模型（LVLMs）在视频理解方面表现出色，但在日常生活活动（ADL）中的应用仍受限于其无法捕捉细粒度交互和空间关系。这一局限在ADL任务中尤为突出，尤其是在老年监护和认知评估等应用中，理解人-物交互和以人为中心的运动至关重要。为此，我们提出利用自我中心视角的互补性来增强LVLM对外中心ADL视频的理解。我们开发了一种在线ego2exo蒸馏方法，用于在LVLMs中学习自我增强的外中心表示。尽管有效，但该方法需要配对的自我-外中心训练数据，这在现实ADL场景中难以获取。因此，我们提出了EgoMimic，一种骨架引导的方法，能够从外中心视频生成模拟的自我视角。通过六个ADL基准和我们专门设计的EgoPerceptionMCQ基准的全面评估，我们发现自我增强的LVLMs成功提取了自我视角的线索。代码、模型和数据将在https://github.com/dominickrei/EgoExo4ADL开源。

> Large Vision Language Models (LVLMs) have demonstrated impressive capabilities in video understanding, yet their adoption for Activities of Daily Living (ADL) remains limited by their inability to capture fine-grained interactions and spatial relationships. This limitation is particularly evident in ADL tasks, where understanding detailed human-object interaction and human-centric motion is crucial for applications such as elderly monitoring and cognitive assessment. To address this, we aim to leverage the complementary nature of egocentric views to enhance LVLM's understanding of exocentric ADL videos. Consequently, we propose an online ego2exo distillation approach to learn ego-augmented exo representations in LVLMs. While effective, this approach requires paired ego-exo training data, which is impractical to collect for real-world ADL scenarios. Consequently, we develop EgoMimic, a skeleton-guided method that can generate mimicked ego views from exocentric videos. We find that the exo representations of our ego-augmented LVLMs successfully learn to extract ego-perspective cues, demonstrated through comprehensive evaluation on six ADL benchmarks and our proposed EgoPerceptionMCQ benchmark designed specifically to assess egocentric understanding from exocentric videos. Code, models, and data will be open-sourced at https://github.com/dominickrei/EgoExo4ADL.

[Arxiv](https://arxiv.org/abs/2501.05711)