# # 摘要  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年04月10日

`LLM理论` `计算机视觉` `问答系统`

> Mimic In-Context Learning for Multimodal Tasks

# 摘要

> 近期，上下文学习 (ICL) 在大型多模态模型 (LMMs) 中成为一种重要的推理范式，通过少量上下文示例 (ICDs) 即可引导模型完成新任务。然而，多模态数据的协同效应使得 ICL 的性能对 ICD 配置更加敏感，因此需要更稳定和通用的映射函数。数学上，在基于 Transformer 的模型中，ICDs 作为 ``shift vectors'' 被添加到查询令牌的隐藏状态中。受此启发，我们提出模仿式上下文学习 (MimIC)，用于从 ICDs 中学习稳定且可推广的 shift 效应。具体来说，与一些基于 shift 向量的先前方法相比，MimIC 通过将轻量级可学习模块集成到 LMMs 中，并结合四个关键改进，更严格地近似 shift 效应：1) 在注意力层后插入 shift 向量，2) 为每个注意力头分配一个 shift 向量，3) 使 shift 幅度与查询相关，4) 采用逐层对齐损失。在两个 LMMs (Idefics-9b 和 Idefics2-8b-base) 上进行的广泛实验，涵盖三个多模态任务 (VQAv2, OK-VQA, Captioning)，表明 MimIC 在现有基于 shift 向量的方法中表现最佳。代码可在 https://github.com/Kamichanw/MimIC 获取。

> Recently, In-context Learning (ICL) has become a significant inference paradigm in Large Multimodal Models (LMMs), utilizing a few in-context demonstrations (ICDs) to prompt LMMs for new tasks. However, the synergistic effects in multimodal data increase the sensitivity of ICL performance to the configurations of ICDs, stimulating the need for a more stable and general mapping function. Mathematically, in Transformer-based models, ICDs act as ``shift vectors'' added to the hidden states of query tokens. Inspired by this, we introduce Mimic In-Context Learning (MimIC) to learn stable and generalizable shift effects from ICDs. Specifically, compared with some previous shift vector-based methods, MimIC more strictly approximates the shift effects by integrating lightweight learnable modules into LMMs with four key enhancements: 1) inserting shift vectors after attention layers, 2) assigning a shift vector to each attention head, 3) making shift magnitude query-dependent, and 4) employing a layer-wise alignment loss. Extensive experiments on two LMMs (Idefics-9b and Idefics2-8b-base) across three multimodal tasks (VQAv2, OK-VQA, Captioning) demonstrate that MimIC outperforms existing shift vector-based methods. The code is available at https://github.com/Kamichanw/MimIC.

[Arxiv](https://arxiv.org/abs/2504.08851)