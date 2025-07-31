# **MoCHA**：通过**专家连接器**与**分层组注意力机制**实现视觉语言推理能力的突破

发布时间：2025年07月30日

`LLM应用` `计算机视觉` `人工智能`

> MoCHA: Advanced Vision-Language Reasoning with MoE Connector and Hierarchical Group Attention

# 摘要

> 视觉大语言模型（VLLMs）通过集成先进视觉编码器并扩展视觉模型，专注于处理复杂且精细的视觉信息。然而，这些方法在训练和推理成本高昂的同时，还面临着提取视觉细节和跨模态有效关联的挑战。为解决这些问题，我们提出了一种全新的视觉框架——MoCHA。该框架整合了CLIP、SigLIP、DINOv2和ConvNeXt四个视觉主干，能够提取互补视觉特征，并配备了一个稀疏的专家混合连接模块（MoECs），可动态选择适合不同视觉维度的专家。为优化编码视觉信息的使用效率，我们设计了一种结合组内和组间操作的层级组注意力（HGA），并采用了自适应门控策略。我们在Phi2-2.7B和Vicuna-7B等主流大语言模型上训练了MoCHA，并在多个基准测试中评估其性能。结果显示，MoCHA在多种任务上超越了现有最优的开源模型。例如，与CuMo（Mistral-7B）相比，MoCHA（Phi2-2.7B）在缓解幻觉方面表现出色，POPE指标提升了3.25%，并在遵循视觉指令方面提高了153分。消融实验进一步证实了MoECs和HGA在提升MoCHA整体性能方面的有效性和鲁棒性。

> Vision large language models (VLLMs) are focusing primarily on handling complex and fine-grained visual information by incorporating advanced vision encoders and scaling up visual models. However, these approaches face high training and inference costs, as well as challenges in extracting visual details, effectively bridging across modalities. In this work, we propose a novel visual framework, MoCHA, to address these issues. Our framework integrates four vision backbones (i.e., CLIP, SigLIP, DINOv2 and ConvNeXt) to extract complementary visual features and is equipped with a sparse Mixture of Experts Connectors (MoECs) module to dynamically select experts tailored to different visual dimensions. To mitigate redundant or insufficient use of the visual information encoded by the MoECs module, we further design a Hierarchical Group Attention (HGA) with intra- and inter-group operations and an adaptive gating strategy for encoded visual features. We train MoCHA on two mainstream LLMs (e.g., Phi2-2.7B and Vicuna-7B) and evaluate their performance across various benchmarks. Notably, MoCHA outperforms state-of-the-art open-weight models on various tasks. For example, compared to CuMo (Mistral-7B), our MoCHA (Phi2-2.7B) presents outstanding abilities to mitigate hallucination by showing improvements of 3.25% in POPE and to follow visual instructions by raising 153 points on MME. Finally, ablation studies further confirm the effectiveness and robustness of the proposed MoECs and HGA in improving the overall performance of MoCHA.

[Arxiv](https://arxiv.org/abs/2507.22805)