# DeltaVLM：交互式遥感图像变化分析——基于指令引导的差异感知

发布时间：2025年07月29日

`LLM应用` `计算机视觉`

> DeltaVLM: Interactive Remote Sensing Image Change Analysis via Instruction-guided Difference Perception

# 摘要

> 准确解析多时相卫星图像中的地表覆盖变化对实际应用至关重要。然而，现有方法通常只能提供单次变化掩膜或静态描述，这限制了它们在支持交互式、基于查询的分析方面的能力。在本研究中，我们提出了一种全新的方法——遥感图像变化分析（RSICA），该方法结合了变化检测与视觉问答的优势，支持对双时相遥感图像进行多轮、指令引导的变化探索。为了支持这一任务，我们构建了大规模指令遵循数据集ChangeChat-105k，该数据集通过混合规则和GPT辅助生成，涵盖了六种交互类型：变化描述、分类、量化、定位、开放性问答以及多轮对话。基于此数据集，我们提出了DeltaVLM，这是一种专为交互式RSICA设计的端到端架构。DeltaVLM拥有三大创新：（1）优化的双时相视觉编码器，用于捕捉时间差异；（2）配备跨语义关系测量（CSRM）机制的视觉差异感知模块，用于解析变化；（3）指令引导的Q-former，能有效从视觉变化中提取与查询相关差异信息，并与文本指令对齐。我们使用冻结的大型语言模型在ChangeChat-105k上训练DeltaVLM，仅对视觉和对齐模块进行适应，以优化效率。大量实验和消融研究表明，DeltaVLM在单轮描述和多轮交互式变化分析上均达到了最先进的性能，超越了现有的多模态大型语言模型和遥感视觉语言模型。代码、数据集和预训练权重可在https://github.com/hanlinwu/DeltaVLM获取。

> Accurate interpretation of land-cover changes in multi-temporal satellite imagery is critical for real-world scenarios. However, existing methods typically provide only one-shot change masks or static captions, limiting their ability to support interactive, query-driven analysis. In this work, we introduce remote sensing image change analysis (RSICA) as a new paradigm that combines the strengths of change detection and visual question answering to enable multi-turn, instruction-guided exploration of changes in bi-temporal remote sensing images. To support this task, we construct ChangeChat-105k, a large-scale instruction-following dataset, generated through a hybrid rule-based and GPT-assisted process, covering six interaction types: change captioning, classification, quantification, localization, open-ended question answering, and multi-turn dialogues. Building on this dataset, we propose DeltaVLM, an end-to-end architecture tailored for interactive RSICA. DeltaVLM features three innovations: (1) a fine-tuned bi-temporal vision encoder to capture temporal differences; (2) a visual difference perception module with a cross-semantic relation measuring (CSRM) mechanism to interpret changes; and (3) an instruction-guided Q-former to effectively extract query-relevant difference information from visual changes, aligning them with textual instructions. We train DeltaVLM on ChangeChat-105k using a frozen large language model, adapting only the vision and alignment modules to optimize efficiency. Extensive experiments and ablation studies demonstrate that DeltaVLM achieves state-of-the-art performance on both single-turn captioning and multi-turn interactive change analysis, outperforming existing multimodal large language models and remote sensing vision-language models. Code, dataset and pre-trained weights are available at https://github.com/hanlinwu/DeltaVLM.

[Arxiv](https://arxiv.org/abs/2507.22346)