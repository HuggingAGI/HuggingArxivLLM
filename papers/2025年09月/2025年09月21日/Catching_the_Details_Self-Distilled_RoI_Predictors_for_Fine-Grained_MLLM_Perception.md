# 捕捉细节：自蒸馏RoI预测器助力细粒度MLLM感知

发布时间：2025年09月21日

`LLM应用` `基础理论`

> Catching the Details: Self-Distilled RoI Predictors for Fine-Grained MLLM Perception

# 摘要

> 多模态大型语言模型（MLLMs）要实现细粒度感知，离不开高分辨率视觉信息，但其处理完整高分辨率图像的计算成本却高得惊人。近期虽有方法借助感兴趣区域（RoI）机制聚焦显著区域，却陷入两难权衡：基于训练的方案依赖大规模标注数据，而利用模型内部注意力的无训练方法又计算低效、准确性欠佳——要么需多遍预填充，要么依赖缓慢的自回归解码。为此，本文提出高效无标注的自蒸馏区域提议网络（SD-RPN），破解这一困境。SD-RPN的核心是一条处理流水线：通过显式信号去噪与模糊性消解，将MLLM中间层输出的噪声注意力图转化为高质量伪RoI标签。我们用这些标签训练轻量级区域提议网络（RPN），使其习得更精准的定位能力。该RPN还具备极致效率：借助MLLM中间层特征，单次前向传播即可完成RoI预测，将RoI识别与自回归生成解耦，彻底告别高昂的多遍操作。为验证方法有效性，我们将该框架集成至LLaVA-1.5架构。结果显示，即便仅在少量（如10K）问答对上训练，我们的方法仍展现出优异的数据效率与泛化能力——在TextVQA、DocVQA、V-Star等未见过的基准测试中，绝对准确率提升超10%。本文为增强MLLMs的细粒度感知能力提供了实用且可扩展的方案，无需大量监督成本或全模型微调。代码链接：https://github.com/YuHengsss/SD-RPN。

> Multimodal Large Language Models (MLLMs) require high-resolution visual information to perform fine-grained perception, yet processing entire high-resolution images is computationally prohibitive. While recent methods leverage a Region-of-Interest (RoI) mechanism to focus on salient areas, they typically present a difficult trade-off: training-based approaches depend on large-scale annotated datasets, while training-free methods that utilize the model's internal attention are computationally inefficient and less accurate, requiring either multi-pass prefill stages or reliance on the slow auto-regressive decoding process. In this paper, we propose an efficient, annotation-free Self-Distilled Region Proposal Network (SD-RPN) that resolves this trade-off. The SD-RPN is built around a pipeline that transforms the noisy attention maps from the MLLM's middle layers into high-quality pseudo-RoI labels by explicitly denoising the signal and resolving ambiguity. We use these labels to train a lightweight Region Proposal Network (RPN) that learns a more precise localization. This RPN is also highly efficient, predicting the RoI in a single forward pass using features from the MLLM's middle layers, decoupling RoI identification from the auto-regressive generation and avoiding costly multi-pass operations.To validate our approach, we integrate the framework into the LLaVA-1.5 architecture. Despite being trained on only a few (e.g. 10K) question-answer pairs, our method demonstrates exceptional data efficiency and generalization, achieving over a 10% absolute accuracy improvement on unseen benchmarks, including TextVQA, DocVQA, and V-Star. Our work presents a practical and scalable solution for enhancing the fine-grained perception of MLLMs without requiring costly supervision or full model fine-tuning. Code is available at https://github.com/YuHengsss/SD-RPN.

[Arxiv](https://arxiv.org/abs/2509.16944)