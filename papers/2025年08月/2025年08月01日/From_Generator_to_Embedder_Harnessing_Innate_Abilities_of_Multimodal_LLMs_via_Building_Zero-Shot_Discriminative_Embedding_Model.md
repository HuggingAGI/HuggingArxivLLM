# 从生成器到嵌入器：利用零样本判别式嵌入模型挖掘多模态LLMs的内在潜力

发布时间：2025年08月01日

`LLM应用` `多模态` `嵌入学习`

> From Generator to Embedder: Harnessing Innate Abilities of Multimodal LLMs via Building Zero-Shot Discriminative Embedding Model

# 摘要

> 多模态大型语言模型（MLLMs）在通用嵌入任务中展现出巨大潜力，但如何将它们的生成特性转化为判别式表示学习能力仍是一个重要挑战。当前主流的大规模对比预训练方法存在计算成本过高、未能充分利用MLLMs指令遵循能力等关键低效问题。为解决这些问题，我们提出了一种高效的通用多模态嵌入框架，通过两个协同组件实现了突破。首先，我们的分层嵌入提示模板采用两级指令架构，迫使模型生成更具判别力的表示。在此基础上，我们的第二个创新组件——自感知硬负采样，通过利用模型自身的理解能力重新定义了微调过程，高效挖掘具有挑战性的负样本，同时主动过滤潜在的伪负样本。实验结果表明，我们的分层提示在零样本性能上可与对比训练的基线相媲美，并通过提升简单的批内负基线4.8个百分点在MMEB基准上优化了微调过程。结合自感知硬负采样，我们进一步提升性能，无需对比预训练即可达到最先进水平。这项工作为将MLLMs适配到通用嵌入任务提供了一条高效且有效的路径，大幅减少了训练时间。

> Multimodal Large Language Models (MLLMs) have emerged as a promising solution for universal embedding tasks, yet adapting their generative nature for discriminative representation learning remains a significant challenge. The dominant paradigm of large-scale contrastive pre-training suffers from critical inefficiencies, including prohibitive computational costs and a failure to leverage the intrinsic, instruction-following capabilities of MLLMs. To overcome these limitations, we propose an efficient framework for universal multimodal embeddings, which bridges this gap by centering on two synergistic components. First, our hierarchical embedding prompt template employs a two-level instruction architecture that forces the model to produce discriminative representations. Building on this strong foundation, our second component, self-aware hard negative sampling, redefines the fine-tuning process by leveraging the model's own understanding to efficiently mine challenging negatives while actively filtering out potential false negatives. Our comprehensive experiments show that our hierarchical prompt achieves zero-shot performance competitive with contrastively trained baselines and enhances the fine-tuning process by lifting a simple in-batch negative baseline by 4.8 points on the MMEB benchmark. We further boost the performance via our self-aware hard negative sampling, achieving the state-of-the-art performance without the contrative pre-training. Our work presents an effective and efficient pathway to adapt MLLMs for universal embedding tasks, significantly reducing training time.

[Arxiv](https://arxiv.org/abs/2508.00955)