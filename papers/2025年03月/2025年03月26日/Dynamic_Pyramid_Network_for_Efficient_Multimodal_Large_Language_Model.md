# 动态金字塔网络：高效多模态大型语言模型

发布时间：2025年03月26日

`LLM应用` `计算机视觉`

> Dynamic Pyramid Network for Efficient Multimodal Large Language Model

# 摘要

> 多模态大型语言模型（MLLMs）在视觉语言任务中表现卓越，但高昂的计算成本限制了其实际应用。为解决这一问题，我们提出了一种创新的动态金字塔网络（DPN），通过分层压缩视觉特征，显著降低了计算成本。即使在高压缩比下，浅层网络仍能捕捉到细粒度的视觉信息。为了进一步优化，我们引入了动态池化专家（DPE），可根据输入特征动态调整压缩率，确保在处理困难样本时保持模型性能。我们在两个主流MLLMs和十个基准测试中进行了全面实验，结果表明，DPN在LLaVA上节省了56%的计算量，同时性能提升了0.74%。此外，DPN在高分辨率的LLaVA-HR上也展现了良好的泛化能力。我们的代码已匿名开源，欢迎访问https://github.com/aihao2000/DPN-LLaVA查看。

> Multimodal large language models (MLLMs) have demonstrated impressive performance in various vision-language (VL) tasks, but their expensive computations still limit the real-world application. To address this issue, recent efforts aim to compress the visual features to save the computational costs of MLLMs. However, direct visual compression methods, e.g. efficient projectors, inevitably destroy the visual semantics in MLLM, especially in difficult samples. To overcome this shortcoming, we propose a novel dynamic pyramid network (DPN) for efficient MLLMs. Specifically, DPN formulates MLLM as a hierarchical structure where visual features are gradually compressed with increasing depth. In this case, even with a high compression ratio, fine-grained visual information can still be perceived in shallow layers. To maximize the benefit of DPN, we further propose an innovative Dynamic Pooling Experts (DPE) that can dynamically choose the optimal visual compression rate according to input features. With this design, harder samples will be assigned larger computations, thus preserving the model performance. To validate our approach, we conduct extensive experiments on two popular MLLMs and ten benchmarks. Experimental results show that DPN can save up to 56% average FLOPs on LLaVA while further achieving +0.74% performance gains. Besides, the generalization ability of DPN is also validated on the existing high-resolution MLLM called LLaVA-HR. Our source codes are anonymously released at https://github.com/aihao2000/DPN-LLaVA.

[Arxiv](https://arxiv.org/abs/2503.20322)