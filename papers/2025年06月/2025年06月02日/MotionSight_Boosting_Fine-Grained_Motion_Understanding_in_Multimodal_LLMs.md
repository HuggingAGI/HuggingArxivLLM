# # MotionSight：助力多模态大语言模型实现细粒度运动理解

发布时间：2025年06月02日

`LLM应用

摘要中提到的研究集中在多模态大型语言模型（MLLMs）的应用上，特别是如何提升其在细粒度视频运动理解方面的能力。研究者提出了MotionSight方法和构建了MotionVid-QA数据集，这些都是将LLM应用于视频运动理解的具体实践，属于LLM应用的范畴。` `问答系统`

> MotionSight: Boosting Fine-Grained Motion Understanding in Multimodal LLMs

# 摘要

> 尽管多模态大型语言模型（MLLMs）取得了进展，但它们在细粒度视频运动理解方面的能力仍显不足。它们通常无法有效捕捉帧间差异，往往忽略或平均化关键视觉线索。此外，视觉提示虽在静态图像中展现出潜力，但将其应用于视频的时间复杂性，特别是细粒度运动理解，仍是未开发的领域。我们研究如何解锁MLLMs的潜在能力，提升其运动感知，并实现物体与相机运动线索的分离。为此，我们提出了MotionSight——一种开创性的零样本方法，通过以对象为中心的视觉焦点和运动模糊作为视觉提示，无需训练即可显著增强细粒度运动理解。为了将这一创新转化为实用数据资产，我们构建了MotionVid-QA——首个大规模细粒度视频运动理解数据集，包含层次化标注（包括SFT和偏好数据）、Θ(40K)视频片段和Θ(87K)问答对。实验结果表明，MotionSight不仅达到开源领域的最先进水平，更可与商业模型相媲美。特别地，我们不仅提出了一种创新的零样本技术，还构建了一个大规模、高质量的数据集。所有代码和标注将公开共享。

> Despite advancements in Multimodal Large Language Models (MLLMs), their proficiency in fine-grained video motion understanding remains critically limited. They often lack inter-frame differencing and tend to average or ignore subtle visual cues. Furthermore, while visual prompting has shown potential in static images, its application to video's temporal complexities, particularly for fine-grained motion understanding, remains largely unexplored. We investigate whether inherent capability can be unlocked and boost MLLMs' motion perception and enable distinct visual signatures tailored to decouple object and camera motion cues. In this study, we introduce MotionSight, a novel zero-shot method pioneering object-centric visual spotlight and motion blur as visual prompts to effectively improve fine-grained motion understanding without training. To convert this into valuable data assets, we curated MotionVid-QA, the first large-scale dataset for fine-grained video motion understanding, with hierarchical annotations including SFT and preference data, Θ(40K) video clips and Θ(87K) QAs. Experiments show MotionSight achieves state-of-the-art open-source performance and competitiveness with commercial models. In particular, for fine-grained motion understanding we present a novel zero-shot technique and a large-scale, high-quality dataset. All the code and annotations will be publicly available.

[Arxiv](https://arxiv.org/abs/2506.01674)