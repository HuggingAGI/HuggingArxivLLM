# 现实世界中的边缘神经网络实现通过物理侧信道泄露了私人交互信息。

发布时间：2025年01月24日

`其他

理由：这篇论文主要讨论的是神经网络在物理设备上的实现和隐私保护问题，特别是通过物理侧信道攻击（ScaAR）来提取用户与神经网络的交互信息。虽然提到了边缘大型语言模型（LLM）的实现，但论文的核心内容并不直接涉及LLM的理论、应用、Agent或RAG（Retrieval-Augmented Generation）等主题。因此，将其分类为“其他”更为合适。` `硬件安全` `隐私保护`

> Real-world Edge Neural Network Implementations Leak Private Interactions Through Physical Side Channel

# 摘要

> 神经网络已成为众多实际应用的核心组件，其实现通常由硬件加速，并广泛应用于各种物理设备中。用户与硬件加速器上的神经网络交互通常涉及隐私敏感信息。尽管在机器学习算法层面已有大量研究致力于揭示漏洞并加强隐私保护，如成员推理攻击、差分隐私和联邦学习，但神经网络最终是在物理设备上实现和部署的，而当前研究对实现层面的隐私保护关注较少。本文提出了一种通用的物理侧信道攻击ScaAR，通过利用物理设备的电磁（EM）辐射来提取用户与神经网络的交互。ScaAR攻击是实现无关的，得益于基于深度学习的侧信道分析（DLSCA），攻击者无需了解硬件或软件的具体实现细节。实验表明，通过EM侧信道，ScaAR能够有效提取用户与神经网络分类器交互的类别标签，包括输入和输出，适用于AMD-Xilinx MPSoC ZCU104 FPGA和Raspberry Pi 3 B。此外，我们首次在Raspberry Pi 5上对边缘大型语言模型（LLM）实现进行了侧信道分析，发现EM侧信道泄露了交互数据，且不同的LLM令牌可以从EM痕迹中区分出来。

> Neural networks have become a fundamental component of numerous practical applications, and their implementations, which are often accelerated by hardware, are integrated into all types of real-world physical devices. User interactions with neural networks on hardware accelerators are commonly considered privacy-sensitive. Substantial efforts have been made to uncover vulnerabilities and enhance privacy protection at the level of machine learning algorithms, including membership inference attacks, differential privacy, and federated learning. However, neural networks are ultimately implemented and deployed on physical devices, and current research pays comparatively less attention to privacy protection at the implementation level. In this paper, we introduce a generic physical side-channel attack, ScaAR, that extracts user interactions with neural networks by leveraging electromagnetic (EM) emissions of physical devices. Our proposed attack is implementation-agnostic, meaning it does not require the adversary to possess detailed knowledge of the hardware or software implementations, thanks to the capabilities of deep learning-based side-channel analysis (DLSCA). Experimental results demonstrate that, through the EM side channel, ScaAR can effectively extract the class label of user interactions with neural classifiers, including inputs and outputs, on the AMD-Xilinx MPSoC ZCU104 FPGA and Raspberry Pi 3 B. In addition, for the first time, we provide side-channel analysis on edge Large Language Model (LLM) implementations on the Raspberry Pi 5, showing that EM side channel leaks interaction data, and different LLM tokens can be distinguishable from the EM traces.

[Arxiv](https://arxiv.org/abs/2501.14512)