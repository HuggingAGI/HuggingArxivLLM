# 基于可验证奖励的少量样本视觉语言推理方法用于卫星图像分析

发布时间：2025年07月29日

`LLM应用` `视觉语言模型`

> Few-Shot Vision-Language Reasoning for Satellite Imagery via Verifiable Rewards

# 摘要

> 大型语言模型和视觉语言模型的进步带来了强大的推理能力，但在遥感等数据稀缺领域仍面临挑战。我们提出了首个针对卫星图像的少样本可验证奖励强化学习（RLVR）框架，无需图像描述监督，仅需轻量级规则或IoU奖励即可运行。我们将语言模型中的“1样本RLVR”范式迁移至视觉语言模型，通过策略梯度优化，仅需少量精选样例即可使模型输出与卫星推理任务需求对齐。在分类、视觉问答和定位等多遥感基准测试中，实验表明即使仅使用一个样例，模型性能也能显著超越基础模型。扩展至128个样例时，性能可媲美基于数千标注样本训练的模型。尽管在极端1样本设置下可能出现轻微任务特定过拟合，但我们的方法在各类任务中始终展现出强大的泛化能力和高效性。此外，提示设计和损失函数权重对训练稳定性和准确性具有显著影响。本方法为开发领域专用视觉语言推理模型提供了一种经济高效、数据友好的解决方案，为数据匮乏领域提供了一套切实可行的实践指南：从精简的视觉语言模型出发，精选少量可验证奖励的案例，通过RLVR进行训练。

> Recent advances in large language and vision-language models have enabled strong reasoning capabilities, yet they remain impractical for specialized domains like remote sensing, where annotated data is scarce and expensive. We present the first few-shot reinforcement learning with verifiable reward (RLVR) framework for satellite imagery that eliminates the need for caption supervision--relying solely on lightweight, rule-based binary or IoU-based rewards. Adapting the "1-shot RLVR" paradigm from language models to vision-language models, we employ policy-gradient optimization with as few as one curated example to align model outputs for satellite reasoning tasks. Comprehensive experiments across multiple remote sensing benchmarks--including classification, visual question answering, and grounding--show that even a single example yields substantial improvements over the base model. Scaling to 128 examples matches or exceeds models trained on thousands of annotated samples. While the extreme one-shot setting can induce mild, task-specific overfitting, our approach consistently demonstrates robust generalization and efficiency across diverse tasks. Further, we find that prompt design and loss weighting significantly influence training stability and final accuracy. Our method enables cost-effective and data-efficient development of domain-specialist vision-language reasoning models, offering a pragmatic recipe for data-scarce fields: start from a compact VLM, curate a handful of reward-checkable cases, and train via RLVR.

[Arxiv](https://arxiv.org/abs/2507.21745)