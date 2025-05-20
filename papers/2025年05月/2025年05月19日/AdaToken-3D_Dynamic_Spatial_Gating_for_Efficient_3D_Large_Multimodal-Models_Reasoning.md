# AdaToken-3D：动态空间门控技术，实现高效三维大规模多模态模型推理

发布时间：2025年05月19日

`LLM应用` `计算机视觉` `模型优化`

> AdaToken-3D: Dynamic Spatial Gating for Efficient 3D Large Multimodal-Models Reasoning

# 摘要

> 大型多模态模型（LMMs）在深度学习领域备受关注，尤其在3D场景理解方面表现突出。然而，现有的3D LMMs在处理多模态推理时，因使用大量空间标记而导致效率低下，存在计算开销过大和信息流冗余的问题。与处理单一图像的2D视觉语言模型不同，3D LMMs由于空间标记与视觉标记之间的异构机制，存在固有的架构冗余。为了解决这一问题，我们提出了AdaToken-3D，一个通过空间贡献分析动态剪裁冗余标记的自适应空间标记优化框架。我们的方法通过挖掘注意力模式量化标记级信息流，为不同3D LMM架构自动定制剪裁策略。在70亿参数的3D-LMM模型LLaVA-3D上的实验表明，AdaToken-3D在保持原有任务精度的同时，实现了推理速度提升21%和计算量减少63%。除了效率提升，本研究通过定量的标记交互分析，系统性地探讨了多模态空间信息流中的冗余模式。我们的研究发现，超过60%的空间标记对最终预测的贡献微乎其微（<5%），为高效的3D多模态学习奠定了理论基础。

> Large Multimodal Models (LMMs) have become a pivotal research focus in deep learning, demonstrating remarkable capabilities in 3D scene understanding. However, current 3D LMMs employing thousands of spatial tokens for multimodal reasoning suffer from critical inefficiencies: excessive computational overhead and redundant information flows. Unlike 2D VLMs processing single images, 3D LMMs exhibit inherent architectural redundancy due to the heterogeneous mechanisms between spatial tokens and visual tokens. To address this challenge, we propose AdaToken-3D, an adaptive spatial token optimization framework that dynamically prunes redundant tokens through spatial contribution analysis. Our method automatically tailors pruning strategies to different 3D LMM architectures by quantifying token-level information flows via attention pattern mining. Extensive experiments on LLaVA-3D (a 7B parameter 3D-LMM) demonstrate that AdaToken-3D achieves 21\% faster inference speed and 63\% FLOPs reduction while maintaining original task accuracy. Beyond efficiency gains, this work systematically investigates redundancy patterns in multimodal spatial information flows through quantitative token interaction analysis. Our findings reveal that over 60\% of spatial tokens contribute minimally ($<$5\%) to the final predictions, establishing theoretical foundations for efficient 3D multimodal learning.

[Arxiv](https://arxiv.org/abs/2505.12782)