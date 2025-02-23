# ChatVLA: 一体化多模态理解与基于视觉-语言-动作模型的机器人控制

发布时间：2025年02月20日

`Agent` `机器人控制` `人工智能`

> ChatVLA: Unified Multimodal Understanding and Robot Control with Vision-Language-Action Model

# 摘要

> 人类能够感知、理解并与物理世界互动，为何大型语言模型无法复制这种能力？通过对现有视觉-语言-动作模型（VLA）的训练范式进行系统性分析，我们发现两个关键挑战：虚假遗忘和任务干扰。前者指机器人训练过程中覆盖了关键的视觉-文本对齐，后者指控制与理解任务在联合训练时相互干扰，导致性能下降。为解决这些问题，我们提出了ChatVLA框架，该框架采用分阶段对齐训练，在掌握初始控制能力后逐步整合多模态数据，并通过专家混合架构降低任务干扰。实验结果显示，ChatVLA在视觉问答数据集上表现出色，且在多模态理解基准测试中显著超越现有VLA方法。具体而言，ChatVLA在MMMU上的性能是现有方法的六倍，在MMStar上以更高效的参数设计取得了47.2%的得分。此外，ChatVLA在25项真实世界机器人操作任务中的表现优于现有VLA方法，如OpenVLA。这些成果表明，我们的统一框架在实现稳健的多模态理解和有效的机器人控制方面具有巨大潜力。

> Humans possess a unified cognitive ability to perceive, comprehend, and interact with the physical world. Why can't large language models replicate this holistic understanding? Through a systematic analysis of existing training paradigms in vision-language-action models (VLA), we identify two key challenges: spurious forgetting, where robot training overwrites crucial visual-text alignments, and task interference, where competing control and understanding tasks degrade performance when trained jointly. To overcome these limitations, we propose ChatVLA, a novel framework featuring Phased Alignment Training, which incrementally integrates multimodal data after initial control mastery, and a Mixture-of-Experts architecture to minimize task interference. ChatVLA demonstrates competitive performance on visual question-answering datasets and significantly surpasses state-of-the-art vision-language-action (VLA) methods on multimodal understanding benchmarks. Notably, it achieves a six times higher performance on MMMU and scores 47.2% on MMStar with a more parameter-efficient design than ECoT. Furthermore, ChatVLA demonstrates superior performance on 25 real-world robot manipulation tasks compared to existing VLA methods like OpenVLA. Our findings highlight the potential of our unified framework for achieving both robust multimodal understanding and effective robot control.

[Arxiv](https://arxiv.org/abs/2502.14420)