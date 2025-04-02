# IDMR：实例驱动的精准视觉对应在多模态检索中的探索

发布时间：2025年04月01日

`LLM应用` `数字内容产业` `图像检索`

> IDMR: Towards Instance-Driven Precise Visual Correspondence in Multimodal Retrieval

# 摘要

> 多模态检索系统在前沿 AI 技术中扮演着越来越重要的角色，例如在具身智能和 AI 驱动的数字内容产业中。然而，现有的多模态检索任务在复杂性和实际应用价值方面仍有欠缺。这激发了我们设计 Instance-Driven Multimodal Image Retrieval (IDMR) —— 一种新型检索任务，要求模型在匹配文本描述场景的同时，检索出与查询图像包含相同实例的图像。与现有专注于全局图像相似性或类别级匹配的检索任务不同，IDMR 强调在不同上下文中实现细粒度的实例级一致性。为评估这一能力，我们基于现实世界的目标跟踪和第一人称视频数据开发了 IDMR-bench。针对训练数据稀缺的问题，我们提出了一种跨域合成方法，通过从标准检测数据集中裁剪目标生成了 55.7 万个训练样本。我们的基于多模态大型语言模型（MLLM）的检索模型，在 120 万个样本上训练，不仅在传统基准测试中表现出色，还在零样本 IDMR-bench 上超越了现有最优方法。实验结果凸显了前一代模型在实例感知检索方面的局限性，并突显了 MLLM 在高级检索应用中的潜力。完整的训练数据集、代码和模型（涵盖多种规模）可在 https://github.com/BwLiu01/IDMR 获取。


> Multimodal retrieval systems are becoming increasingly vital for cutting-edge AI technologies, such as embodied AI and AI-driven digital content industries. However, current multimodal retrieval tasks lack sufficient complexity and demonstrate limited practical application value. It spires us to design Instance-Driven Multimodal Image Retrieval (IDMR), a novel task that requires models to retrieve images containing the same instance as a query image while matching a text-described scenario. Unlike existing retrieval tasks focused on global image similarity or category-level matching, IDMR demands fine-grained instance-level consistency across diverse contexts. To benchmark this capability, we develop IDMR-bench using real-world object tracking and first-person video data. Addressing the scarcity of training data, we propose a cross-domain synthesis method that creates 557K training samples by cropping objects from standard detection datasets. Our Multimodal Large Language Model (MLLM) based retrieval model, trained on 1.2M samples, outperforms state-of-the-art approaches on both traditional benchmarks and our zero-shot IDMR-bench. Experimental results demonstrate previous models' limitations in instance-aware retrieval and highlight the potential of MLLM for advanced retrieval applications. The whole training dataset, codes and models, with wide ranges of sizes, are available at https://github.com/BwLiu01/IDMR.

[Arxiv](https://arxiv.org/abs/2504.00954)