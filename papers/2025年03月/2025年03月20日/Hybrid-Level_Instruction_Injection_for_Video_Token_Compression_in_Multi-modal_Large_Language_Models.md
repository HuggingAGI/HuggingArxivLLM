# <翻译失败>

发布时间：2025年03月20日

`LLM应用` `视频处理` `多模态模型`

> Hybrid-Level Instruction Injection for Video Token Compression in Multi-modal Large Language Models

# 摘要

> 近期研究发现，多模态大语言模型（MLLMs）在处理视频数据时面临计算开销过大的问题，通常通过压缩策略来缓解。然而，现有压缩方法（如平均池化）会导致重要信息丢失。为解决这一难题，我们提出了混合级指令注入策略（HICom），通过将用户指令作为条件，从局部和全局两个层面优化压缩过程。这种策略既保留了用户关注的核心信息，又大幅降低了计算负担。具体来说，我们在局部层面将指令条件注入到视觉令牌组中，在全局层面注入可学习令牌，并通过注意力机制完成条件压缩。通过这种方式，与用户指令相关的视觉内容得以突出，同时保留了时空结构，便于模型理解。为了进一步提升HICom的效果，我们引入了一个新的条件预训练阶段，并构建了数据集HICom-248K。实验结果显示，相比现有最优方法，HICom在使用更少令牌的情况下，视频理解能力提升了2.43%（基于三个多项选择题基准测试），并且节省了78.8%的令牌。代码已开源，可在https://github.com/lntzm/HICom获取。

> Recent Multi-modal Large Language Models (MLLMs) have been challenged by the computational overhead resulting from massive video frames, often alleviated through compression strategies. However, the visual content is not equally contributed to user instructions, existing strategies (\eg, average pool) inevitably lead to the loss of potentially useful information. To tackle this, we propose the Hybrid-level Instruction Injection Strategy for Conditional Token Compression in MLLMs (HICom), utilizing the instruction as a condition to guide the compression from both local and global levels. This encourages the compression to retain the maximum amount of user-focused information while reducing visual tokens to minimize computational burden. Specifically, the instruction condition is injected into the grouped visual tokens at the local level and the learnable tokens at the global level, and we conduct the attention mechanism to complete the conditional compression. From the hybrid-level compression, the instruction-relevant visual parts are highlighted while the temporal-spatial structure is also preserved for easier understanding of LLMs. To further unleash the potential of HICom, we introduce a new conditional pre-training stage with our proposed dataset HICom-248K. Experiments show that our HICom can obtain distinguished video understanding ability with fewer tokens, increasing the performance by 2.43\% average on three multiple-choice QA benchmarks and saving 78.8\% tokens compared with the SOTA method. The code is available at https://github.com/lntzm/HICom.

[Arxiv](https://arxiv.org/abs/2503.16036)