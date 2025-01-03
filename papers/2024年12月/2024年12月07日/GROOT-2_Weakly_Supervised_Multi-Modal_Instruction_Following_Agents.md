# GROOT-2: 弱监督多模态指令跟随智能体

发布时间：2024年12月07日

`Agent

理由：这篇论文主要讨论的是开发能够遵循多模态指令的智能体（Agent），并提出了GROOT-2这一方法。论文的核心内容围绕如何通过半监督学习和潜在变量模型来训练多模态可指令智能体，使其能够准确执行指令。因此，这篇论文应归类为Agent。` `机器人` `人工智能`

> GROOT-2: Weakly Supervised Multi-Modal Instruction Following Agents

# 摘要

> # 摘要
开发能够遵循多模态指令的智能体仍是机器人和AI领域的一大挑战。尽管大规模无标签数据集的预训练让智能体学会了多种行为，但它们往往难以准确执行指令。虽然增加指令标签数据可以缓解这一问题，但大规模获取高质量标注并不现实。为此，我们将问题转化为半监督学习任务，并提出了GROOT-2——一种结合弱监督与潜在变量模型训练的多模态可指令智能体。其核心方法包括：利用大量未标注演示的“受限自我模仿”策略，以及通过少量标注数据确保潜在空间与人类意图一致的“人类意图对齐”。GROOT-2在从视频游戏到机器人操作的多种环境中展现了强大的多模态指令执行能力，验证了其有效性。

> Developing agents that can follow multimodal instructions remains a fundamental challenge in robotics and AI. Although large-scale pre-training on unlabeled datasets (no language instruction) has enabled agents to learn diverse behaviors, these agents often struggle with following instructions. While augmenting the dataset with instruction labels can mitigate this issue, acquiring such high-quality annotations at scale is impractical. To address this issue, we frame the problem as a semi-supervised learning task and introduce GROOT-2, a multimodal instructable agent trained using a novel approach that combines weak supervision with latent variable models. Our method consists of two key components: constrained self-imitating, which utilizes large amounts of unlabeled demonstrations to enable the policy to learn diverse behaviors, and human intention alignment, which uses a smaller set of labeled demonstrations to ensure the latent space reflects human intentions. GROOT-2's effectiveness is validated across four diverse environments, ranging from video games to robotic manipulation, demonstrating its robust multimodal instruction-following capabilities.

[Arxiv](https://arxiv.org/abs/2412.10410)