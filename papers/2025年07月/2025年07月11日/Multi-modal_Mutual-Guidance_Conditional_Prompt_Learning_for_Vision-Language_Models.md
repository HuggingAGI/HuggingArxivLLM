# 面向视觉语言模型的多模态相互引导条件提示学习

发布时间：2025年07月11日

`LLM应用` `计算机视觉`

> Multi-modal Mutual-Guidance Conditional Prompt Learning for Vision-Language Models

# 摘要

> 提示学习为视觉语言模型（VLMs）在多种下游任务中的高效适配提供了可能。然而，当前方法面临两大核心挑战：(1) 未见实例的类别嵌入分布建模不足，导致新型类别泛化效果欠佳；(2) 跨模态对齐局限于编码器最终输出层，限制了与预训练多模态嵌入空间的一致性。针对这些问题，我们提出了MuGCP（多模态相互引导条件提示学习），一种创新性框架，专为条件提示生成而设计。MuGCP利用多模态大规模语言模型（MLLMs）作为条件提示学习器，自适应生成包含丰富、细致高层次语义知识的语义条件提示（SCP），以增强图像实例的语义表达。为实现视觉语言模型（VLMs）多模态空间的有效对齐与交互，我们引入了注意力相互引导（AMG）模块，该模块促进了视觉信息与语义信息之间的交互。通过相互引导机制，AMG模块生成视觉条件提示（VCP），从而提升模型在多模态任务中的性能。此外，我们提出了一种多提示融合（MPF）机制，将SCP、VCP与上下文提示进行整合，确保不同提示间的无缝协作，从而增强类别嵌入建模和实例特定知识的学习。在14个不同数据集上，我们的MuGCP方法均超越了现有最优方法的性能。代码将在论文发表后开源。

> Prompt learning facilitates the efficient adaptation of Vision-Language Models (VLMs) to various downstream tasks. However, it faces two significant challenges: (1) inadequate modeling of class embedding distributions for unseen instances, leading to suboptimal generalization on novel classes; (2) prevailing methodologies predominantly confine cross-modal alignment to the final output layer of vision and text encoders, which fundamentally limits their capacity to preserve topological consistency with pre-trained multi-modal embedding spaces. To this end, we introduce MuGCP (Multi-modal Mutual-Guidance Conditional Prompt Learning), a novel paradigm designed for conditional prompt generation. MuGCP leverages Multi-modal Large Language Models (MLLMs) as conditional prompt learners to adaptively generate Semantic Conditional Prompts (SCP) that incorporate rich, fine-grained high-level semantic knowledge for image instances. To ensure effective alignment and interaction across the multi-modal space of Vision-Language Models (VLMs), we introduce the Attention Mutual-Guidance (AMG) module, which facilitates interactions between visual and semantic information. Through mutual guidance, the AMG module generates Visual Conditional Prompts (VCP), enhancing the model's performance in multi-modal tasks. Additionally, we present a Multi-Prompt Fusion (MPF) mechanism that integrates SCP and VCP with contextual prompts, ensuring seamless coordination among the different prompts and enhancing the modeling of class embeddings and instance-specific knowledge. Our MuGCP outperforms existing state-of-the-art methods on 14 different datasets. The code will be made available after publication.

[Arxiv](https://arxiv.org/abs/2507.08410)