# Qianfan-VL：领域增强型通用视觉-语言模型

发布时间：2025年09月19日

`LLM应用` `教育科技`

> Qianfan-VL: Domain-Enhanced Universal Vision-Language Models

# 摘要

> 我们推出了千帆-VL（Qianfan-VL）系列多模态大型语言模型，参数规模覆盖30亿至700亿，凭借创新的领域增强技术达到了最先进性能水平。我们的方法采用多阶段渐进式训练与高精度数据合成流水线，这两项技术被证实是在保持优异通用性能的同时提升特定领域能力的关键。千帆-VL在通用基准测试中表现与主流开源模型相当，而在CCBench、SEEDBench IMG、ScienceQA及MMStar等基准测试中则刷新了最先进性能。领域增强策略在OCR与文档理解领域展现出显著优势，这一优势在公共基准测试（OCRBench 873分、DocVQA 94.75%准确率）和内部评估中均得到验证。值得关注的是，千帆-VL-8B与70B变体还具备长思维链能力，在数学推理（MathVista 78.6%）和逻辑推理任务中展现出卓越性能。所有模型均基于百度昆仑P800芯片完成训练，这验证了大规模AI基础设施可高效训练SOTA级多模态模型——在5000芯片集群上单任务训练的扩展效率超90%。这项研究为开发适用于各类企业部署场景的领域增强型多模态模型提供了一套行之有效的方法论。

> We present Qianfan-VL, a series of multimodal large language models ranging from 3B to 70B parameters, achieving state-of-the-art performance through innovative domain enhancement techniques. Our approach employs multi-stage progressive training and high-precision data synthesis pipelines, which prove to be critical technologies for enhancing domain-specific capabilities while maintaining strong general performance. Qianfan-VL achieves comparable results to leading open-source models on general benchmarks, with state-of-the-art performance on benchmarks such as CCBench, SEEDBench IMG, ScienceQA, and MMStar. The domain enhancement strategy delivers significant advantages in OCR and document understanding, validated on both public benchmarks (OCRBench 873, DocVQA 94.75%) and in-house evaluations. Notably, Qianfan-VL-8B and 70B variants incorporate long chain-of-thought capabilities, demonstrating superior performance on mathematical reasoning (MathVista 78.6%) and logical inference tasks. All models are trained entirely on Baidu's Kunlun P800 chips, validating the capability of large-scale AI infrastructure to train SOTA-level multimodal models with over 90% scaling efficiency on 5000 chips for a single task. This work establishes an effective methodology for developing domain-enhanced multimodal models suitable for diverse enterprise deployment scenarios.

[Arxiv](https://arxiv.org/abs/2509.18189)