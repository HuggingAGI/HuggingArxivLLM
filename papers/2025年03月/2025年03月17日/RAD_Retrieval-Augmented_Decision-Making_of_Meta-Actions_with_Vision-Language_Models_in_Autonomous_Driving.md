# RAD：视觉语言模型增强的元动作决策方法在自动驾驶中的应用研究

发布时间：2025年03月17日

`RAG` `自动驾驶` `人工智能`

> RAD: Retrieval-Augmented Decision-Making of Meta-Actions with Vision-Language Models in Autonomous Driving

# 摘要

> 准确理解并决定高层次的元动作决策对于确保可靠的自动驾驶系统至关重要。尽管视觉语言模型（VLMs）在自动驾驶任务中展现了巨大潜力，但其空间感知不足和幻觉等问题限制了其在复杂场景中的应用。为了解决这些挑战，我们提出了一种检索增强的决策框架（RAD），旨在提升 VLMs 在自动驾驶场景中生成元动作的能力。RAD 通过嵌入流、检索流和生成流三个阶段的动态过程，利用检索增强生成（RAG）管道来提高决策准确性。此外，我们基于 NuScenes 数据集整理了一个专门的数据集，并对 VLMs 进行微调，以增强其空间感知和鸟瞰图图像理解能力。在基于该数据集的广泛实验中，RAD 在匹配准确率、F1 分数和自定义总体得分等关键指标上均优于基线方法，充分证明了其在提升自动驾驶任务中元动作决策能力方面的有效性。

> Accurately understanding and deciding high-level meta-actions is essential for ensuring reliable and safe autonomous driving systems. While vision-language models (VLMs) have shown significant potential in various autonomous driving tasks, they often suffer from limitations such as inadequate spatial perception and hallucination, reducing their effectiveness in complex autonomous driving scenarios. To address these challenges, we propose a retrieval-augmented decision-making (RAD) framework, a novel architecture designed to enhance VLMs' capabilities to reliably generate meta-actions in autonomous driving scenes. RAD leverages a retrieval-augmented generation (RAG) pipeline to dynamically improve decision accuracy through a three-stage process consisting of the embedding flow, retrieving flow, and generating flow. Additionally, we fine-tune VLMs on a specifically curated dataset derived from the NuScenes dataset to enhance their spatial perception and bird's-eye view image comprehension capabilities. Extensive experimental evaluations on the curated NuScenes-based dataset demonstrate that RAD outperforms baseline methods across key evaluation metrics, including match accuracy, and F1 score, and self-defined overall score, highlighting its effectiveness in improving meta-action decision-making for autonomous driving tasks.

[Arxiv](https://arxiv.org/abs/2503.13861)