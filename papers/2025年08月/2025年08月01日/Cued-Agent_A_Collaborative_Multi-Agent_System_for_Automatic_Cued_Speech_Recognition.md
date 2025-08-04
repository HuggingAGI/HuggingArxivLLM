# Cued-Agent：一个协作式的多智能体系统，专为自动唇语识别而设计

发布时间：2025年08月01日

`Agent` `残疾人辅助` `计算机视觉`

> Cued-Agent: A Collaborative Multi-Agent System for Automatic Cued Speech Recognition

# 摘要

> Cued Speech（CS）是一种结合唇读和手语的视觉沟通系统，专为听力障碍者设计，帮助他们更高效地交流。自动CS识别（ACSR）的目标是通过AI驱动的方法，将CS手部动作和唇部动作转化为文字。传统方法中，由于手部动作和唇部动作的时间不同步，通常需要设计复杂的模块来促进多模态融合。然而，受限于可用数据的有限性，现有方法在训练这些融合机制方面的能力不足，导致性能表现不佳。最近，多智能体系统在处理数据有限的复杂任务方面展现出巨大潜力。基于此，我们提出了首个用于ACSR的协作式多智能体系统，命名为Cued-Agent。该系统集成了四个专业子智能体：基于多模态大型语言模型的手势识别智能体（采用关键帧筛选和CS专家提示策略解码手部动作）、预训练Transformer模型的唇部识别智能体（从输入视频中提取唇部特征）、动态手部提示解码智能体（无需训练即可在推理过程中将手部提示与唇部特征动态融合）、以及自我修正音素到词语智能体（首次通过语义优化实现从音素序列到自然语言句子的后处理和端到端转换）。为了支持这项研究，我们扩展了现有的普通话CS数据集，新增了来自八位听力障碍者的数据，形成了包含14个主体的混合数据集。大量实验表明，与现有最优方法相比，我们的Cued-Agent在正常和听力障碍场景下均表现出色。代码实现已开源，访问链接为https://github.com/DennisHgj/Cued-Agent。

> Cued Speech (CS) is a visual communication system that combines lip-reading with hand coding to facilitate communication for individuals with hearing impairments. Automatic CS Recognition (ACSR) aims to convert CS hand gestures and lip movements into text via AI-driven methods. Traditionally, the temporal asynchrony between hand and lip movements requires the design of complex modules to facilitate effective multimodal fusion. However, constrained by limited data availability, current methods demonstrate insufficient capacity for adequately training these fusion mechanisms, resulting in suboptimal performance. Recently, multi-agent systems have shown promising capabilities in handling complex tasks with limited data availability. To this end, we propose the first collaborative multi-agent system for ACSR, named Cued-Agent. It integrates four specialized sub-agents: a Multimodal Large Language Model-based Hand Recognition agent that employs keyframe screening and CS expert prompt strategies to decode hand movements, a pretrained Transformer-based Lip Recognition agent that extracts lip features from the input video, a Hand Prompt Decoding agent that dynamically integrates hand prompts with lip features during inference in a training-free manner, and a Self-Correction Phoneme-to-Word agent that enables post-process and end-to-end conversion from phoneme sequences to natural language sentences for the first time through semantic refinement. To support this study, we expand the existing Mandarin CS dataset by collecting data from eight hearing-impaired cuers, establishing a mixed dataset of fourteen subjects. Extensive experiments demonstrate that our Cued-Agent performs superbly in both normal and hearing-impaired scenarios compared with state-of-the-art methods. The implementation is available at https://github.com/DennisHgj/Cued-Agent.

[Arxiv](https://arxiv.org/abs/2508.00391)