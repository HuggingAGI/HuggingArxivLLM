# FCKT: 基于细粒度跨任务知识迁移与语义对比学习的面向目标情感分析方法

发布时间：2025年05月27日

`其他` `情感分析` `评论分析`

> FCKT: Fine-Grained Cross-Task Knowledge Transfer with Semantic Contrastive Learning for Targeted Sentiment Analysis

# 摘要

> 在这篇论文中，我们探讨了目标情感分析（TSA）任务，该任务包含两个子任务：从评论中识别具体方面以及判断这些方面的对应情感。方面提取作为情感预测的基础，凸显了这两个任务之间在跨任务知识转移中的紧密联系。目前，大多数研究采用多任务学习方法，试图在潜在空间中对齐任务特异性特征，但这些方法主要依赖于粗粒度的知识转移。这种做法在控制方面与情感之间的关系上显得不够精细，通常假设相关方面的情感倾向一致。这种过于简化的假设忽略了能够区分不同情感的上下文线索，导致负面迁移现象。为了解决这些问题，我们提出了FCKT（细粒度跨任务知识转移框架），专为TSA设计。通过将方面级别的信息直接整合到情感预测过程中，FCKT实现了更精细的知识转移，有效减少了负面迁移，提升了整体任务效果。我们在三个数据集上的实验结果，包括与多种基线模型和大型语言模型（LLMs）的对比，均验证了FCKT的有效性。如需获取源代码，请访问https://github.com/cwei01/FCKT。

> In this paper, we address the task of targeted sentiment analysis (TSA), which involves two sub-tasks, i.e., identifying specific aspects from reviews and determining their corresponding sentiments. Aspect extraction forms the foundation for sentiment prediction, highlighting the critical dependency between these two tasks for effective cross-task knowledge transfer. While most existing studies adopt a multi-task learning paradigm to align task-specific features in the latent space, they predominantly rely on coarse-grained knowledge transfer. Such approaches lack fine-grained control over aspect-sentiment relationships, often assuming uniform sentiment polarity within related aspects. This oversimplification neglects contextual cues that differentiate sentiments, leading to negative transfer. To overcome these limitations, we propose FCKT, a fine-grained cross-task knowledge transfer framework tailored for TSA. By explicitly incorporating aspect-level information into sentiment prediction, FCKT achieves fine-grained knowledge transfer, effectively mitigating negative transfer and enhancing task performance. Experiments on three datasets, including comparisons with various baselines and large language models (LLMs), demonstrate the effectiveness of FCKT. The source code is available on https://github.com/cwei01/FCKT.

[Arxiv](https://arxiv.org/abs/2505.21040)