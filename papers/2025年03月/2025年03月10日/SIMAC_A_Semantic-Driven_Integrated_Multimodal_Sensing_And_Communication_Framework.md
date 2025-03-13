# SIMAC：一个以语义驱动的多模态感知与通信集成框架

发布时间：2025年03月10日

`其他` `多模态`

> SIMAC: A Semantic-Driven Integrated Multimodal Sensing And Communication Framework

# 摘要

> 传统的单模态感知在准确性和能力上存在局限性，且与通信系统的解耦实现增加了带宽受限环境中的延迟。此外，面向单一任务的感知系统难以满足用户的多样化需求。为克服这些挑战，我们提出了一种语义驱动的集成多模态感知与通信框架（SIMAC）。该框架采用联合源信道编码架构，实现感知解码与感知结果传输的同步。具体来说，SIMAC首先引入了一种多模态语义融合（MSF）网络，分别通过两个提取器从雷达信号和图像中提取语义信息。随后，MSF采用交叉注意力机制融合单模态特征，生成多模态语义表示。其次，我们提出了一种基于大语言模型（LLM）的语义编码器（LSE），其中相关通信参数和多模态语义被映射到统一的潜在空间，并输入LLM，从而实现信道自适应的语义编码。第三，我们设计了一种面向任务的感知语义解码器（SSD），根据不同任务的具体需求设计了不同的解码头。同时，引入多任务学习策略训练SIMAC框架，实现多样化的感知服务。最后，实验仿真结果表明，所提出的框架能够实现多样化的感知服务并具有更高的准确性。

> Traditional single-modality sensing faces limitations in accuracy and capability, and its decoupled implementation with communication systems increases latency in bandwidth-constrained environments. Additionally, single-task-oriented sensing systems fail to address users' diverse demands. To overcome these challenges, we propose a semantic-driven integrated multimodal sensing and communication (SIMAC) framework. This framework leverages a joint source-channel coding architecture to achieve simultaneous sensing decoding and transmission of sensing results. Specifically, SIMAC first introduces a multimodal semantic fusion (MSF) network, which employs two extractors to extract semantic information from radar signals and images, respectively. MSF then applies cross-attention mechanisms to fuse these unimodal features and generate multimodal semantic representations. Secondly, we present a large language model (LLM)-based semantic encoder (LSE), where relevant communication parameters and multimodal semantics are mapped into a unified latent space and input to the LLM, enabling channel-adaptive semantic encoding. Thirdly, a task-oriented sensing semantic decoder (SSD) is proposed, in which different decoded heads are designed according to the specific needs of tasks. Simultaneously, a multi-task learning strategy is introduced to train the SIMAC framework, achieving diverse sensing services. Finally, experimental simulations demonstrate that the proposed framework achieves diverse sensing services and higher accuracy.

[Arxiv](https://arxiv.org/abs/2503.08726)