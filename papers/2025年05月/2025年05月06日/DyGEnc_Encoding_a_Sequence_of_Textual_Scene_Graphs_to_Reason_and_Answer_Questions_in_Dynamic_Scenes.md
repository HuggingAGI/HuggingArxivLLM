# DyGEnc：通过编码一系列文本场景图，在动态场景中实现推理与问答。

发布时间：2025年05月06日

`Agent` `机器人` `智能体`

> DyGEnc: Encoding a Sequence of Textual Scene Graphs to Reason and Answer Questions in Dynamic Scenes

# 摘要

> 在动态环境中分析事件是开发能够与人类互动的智能体和机器人所面临的一项基本挑战。目前的方法主要依赖于视觉模型，但这些方法通常从图像中隐式获取信息，缺乏可解释的空间-时间对象表示。为了解决这个问题，我们引入了DyGEnc——一种新型的动态图编码方法。该方法将压缩的空间-时间结构化观察表示与大型语言模型的认知能力相结合，旨在支持基于文本场景图序列的高级问答。在STAR和AGQA数据集上的扩展评估表明，DyGEnc在处理有关人类与物体交互历史的查询方面，比现有视觉方法高出15-25%。此外，该方法可以无缝扩展，利用基础模型从原始输入图像中提取显式的文本场景图，这一点在使用轮式操作平台进行的机器人实验中得到了验证。我们希望这些发现将有助于实现基于健壮且压缩的图结构机器人记忆，以支持长期推理。代码可在github.com/linukc/DyGEnc上获取。

> The analysis of events in dynamic environments poses a fundamental challenge in the development of intelligent agents and robots capable of interacting with humans. Current approaches predominantly utilize visual models. However, these methods often capture information implicitly from images, lacking interpretable spatial-temporal object representations. To address this issue we introduce DyGEnc - a novel method for Encoding a Dynamic Graph. This method integrates compressed spatial-temporal structural observation representation with the cognitive capabilities of large language models. The purpose of this integration is to enable advanced question answering based on a sequence of textual scene graphs. Extended evaluations on the STAR and AGQA datasets indicate that DyGEnc outperforms existing visual methods by a large margin of 15-25% in addressing queries regarding the history of human-to-object interactions. Furthermore, the proposed method can be seamlessly extended to process raw input images utilizing foundational models for extracting explicit textual scene graphs, as substantiated by the results of a robotic experiment conducted with a wheeled manipulator platform. We hope that these findings will contribute to the implementation of robust and compressed graph-based robotic memory for long-horizon reasoning. Code is available at github.com/linukc/DyGEnc.

[Arxiv](https://arxiv.org/abs/2505.03581)