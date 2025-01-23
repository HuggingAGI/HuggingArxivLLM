# LLM4WM: 大型语言模型在无线多任务中的适应性应用

发布时间：2025年01月22日

`LLM应用

理由：该论文提出了一个名为LLM4WM的框架，专门用于无线信道相关任务的多任务微调。该框架利用大型语言模型（LLM）的通用知识，通过混合专家与低秩适应（MoE-LoRA）方法进行微调，以优化系统设计。这表明该研究主要关注如何将LLM应用于特定领域（无线信道相关任务）的多任务学习，因此属于LLM应用类别。` `无线网络`

> LLM4WM: Adapting LLM for Wireless Multi-Tasking

# 摘要

> 无线信道是通信的核心，涉及一系列信道相关任务。这些任务可通过基于信道特性的联合学习共享表示，优化系统设计。为此，我们提出了LLM4WM——一个专为信道相关任务设计的大型语言模型（LLM）多任务微调框架。该框架采用混合专家与低秩适应（MoE-LoRA）方法进行多任务微调，将预训练LLM的通用知识迁移至这些任务。针对无线信道数据的特性，我们设计了预处理模块、适配器模块和多任务输出层，确保信道数据与LLM的语义特征空间对齐。实验表明，LLM4WM在全样本和少样本评估中均优于现有方法，得益于其强大的多任务联合建模和迁移学习能力。

> The wireless channel is fundamental to communication, encompassing numerous tasks collectively referred to as channel-associated tasks. These tasks can leverage joint learning based on channel characteristics to share representations and enhance system design. To capitalize on this advantage, LLM4WM is proposed--a large language model (LLM) multi-task fine-tuning framework specifically tailored for channel-associated tasks. This framework utilizes a Mixture of Experts with Low-Rank Adaptation (MoE-LoRA) approach for multi-task fine-tuning, enabling the transfer of the pre-trained LLM's general knowledge to these tasks. Given the unique characteristics of wireless channel data, preprocessing modules, adapter modules, and multi-task output layers are designed to align the channel data with the LLM's semantic feature space. Experiments on a channel-associated multi-task dataset demonstrate that LLM4WM outperforms existing methodologies in both full-sample and few-shot evaluations, owing to its robust multi-task joint modeling and transfer learning capabilities.

[Arxiv](https://arxiv.org/abs/2501.12983)