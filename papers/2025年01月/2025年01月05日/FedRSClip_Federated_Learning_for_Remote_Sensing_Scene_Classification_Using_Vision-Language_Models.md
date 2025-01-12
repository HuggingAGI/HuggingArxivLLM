# FedRSClip: 基于视觉-语言模型的遥感场景分类联邦学习

发布时间：2025年01月05日

`LLM应用

理由：这篇论文主要讨论了如何利用联邦学习框架（FedRSCLIP）来解决遥感图像分类中的问题，特别是通过引入提示学习（Prompt Learning）来优化大规模视觉-语言模型（VLM）的通信成本和数据异构性问题。虽然论文中提到了视觉-语言模型（如CLIP），但其核心应用场景是遥感图像分类，属于LLM在实际应用中的扩展和优化，因此归类为“LLM应用”。` `联邦学习`

> FedRSClip: Federated Learning for Remote Sensing Scene Classification Using Vision-Language Models

# 摘要

> # 摘要
遥感数据通常分散在多个机构中，由于隐私和数据共享限制，集中式训练框架难以利用大规模数据集。联邦学习通过在不集中数据的情况下实现跨分布式数据源的协作模型训练，提供了一种可行的解决方案。然而，当前的视觉-语言模型（VLMs）通常包含数十亿参数，对传统基于模型参数更新的联邦学习方法提出了显著的通信挑战，导致高昂的通信成本。本文提出了FedRSCLIP，这是首个基于VLM（特别是CLIP）的遥感图像分类联邦学习框架。FedRSCLIP通过引入提示学习（Prompt Learning）来解决数据异构性和大规模模型传输的挑战，提示学习仅优化少量可调参数。该框架采用双提示机制，包括用于全局知识共享的共享提示和用于客户端特定适应的私有提示。为了保持共享提示和私有提示的语义一致性，我们提出了双提示对齐约束，以平衡不同客户端分布下的全局一致性和局部适应性。此外，为了增强跨模态表示学习，我们引入了跨模态特征对齐约束，以对齐文本和图像提示的多模态特征。为了验证模型的有效性，我们基于三个现有遥感图像分类数据集构建了Fed-RSIC数据集，专门用于模拟各种联邦学习配置。实验结果表明，FedRSCLIP在遥感图像分类中表现出色且具有显著优势。

> Remote sensing data is often distributed across multiple institutions, and due to privacy concerns and data-sharing restrictions, leveraging large-scale datasets in a centralized training framework is challenging. Federated learning offers a promising solution by enabling collaborative model training across distributed data sources without requiring data centralization. However, current Vision-Language Models (VLMs), which typically contain billions of parameters, pose significant communication challenges for traditional federated learning approaches based on model parameter updates, as they would incur substantial communication costs. In this paper, we propose FedRSCLIP, the first federated learning framework designed for remote sensing image classification based on a VLM, specifically CLIP. FedRSCLIP addresses the challenges of data heterogeneity and large-scale model transmission in federated environments by introducing Prompt Learning, which optimizes only a small set of tunable parameters. The framework introduces a dual-prompt mechanism, comprising Shared Prompts for global knowledge sharing and Private Prompts for client-specific adaptation. To maintain semantic coherence between shared and private prompts, we propose the Dual Prompt Alignment Constraint to balance global consistency and local adaptability across diverse client distributions. Additionally, to enhance cross-modal representation learning, we introduce the Cross-Modal Feature Alignment Constraint to align multimodal features between text and image prompts. To validate the effectiveness of our proposed model, we construct a Fed-RSIC dataset based on three existing remote sensing image classification datasets, specifically designed to simulate various federated learning configurations. Experimental results demonstrate the effectiveness and superiority of FedRSCLIP in remote sensing image classification.

[Arxiv](https://arxiv.org/abs/2501.02461)