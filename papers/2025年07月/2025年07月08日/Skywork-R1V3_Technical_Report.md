# 技术报告：Skywork-R1V3

发布时间：2025年07月08日

`LLM应用

理由：这篇论文主要探讨了如何将大语言模型（LLMs）的推理能力迁移至视觉任务，并通过强化学习框架提升性能。这属于大语言模型在具体任务中的应用，因此归类为LLM应用。` `计算机视觉` `视觉推理`

> Skywork-R1V3 Technical Report

# 摘要

> 我们很高兴推出 Skywork-R1V3，一款开创性的开源视觉语言模型 (VLM)，它以一种全新方式实现了视觉推理。Skywork-R1V3 的核心创新在于，能够将仅基于文本的大语言模型 (LLMs) 的推理能力成功迁移至视觉任务。其卓越性能主要归功于我们的训练后强化学习 (RL) 框架，这一框架无需额外的持续预训练，即可有效激活并提升模型的推理能力。通过这一框架，我们深入揭示了连接模块在实现多模态推理模型鲁棒跨模态对齐中的关键作用。此外，我们引入了一个创新的推理能力指标——关键推理 token 的熵，这一指标在强化学习训练中的检查点选择中表现尤为出色。Skywork-R1V3 在 MMMU 数据集上取得了突破性成果，准确率从 64.3% 大幅提升至 76.0%，已达到入门级人类水平。令人振奋的是，我们的强化学习驱动的训练后方法，甚至使 380 亿参数规模的模型能够与顶级闭源 VLM 相媲美。该模型成功实现了数学推理能力向其他主题相关推理任务的迁移。我们还对课程学习和强化微调策略进行了深入分析，并就多模态推理展开了更广泛的讨论。Skywork-R1V3 的推出标志着多模态推理领域的重要进展，充分展现了强化学习作为推动开源 VLM 能力发展的强大引擎。

> We introduce Skywork-R1V3, an advanced, open-source vision-language model (VLM) that pioneers a new approach to visual reasoning. Its key innovation lies in effectively transferring reasoning skills from text-only Large Language Models (LLMs) to visual tasks. The strong performance of Skywork-R1V3 primarily stems from our elaborate post-training RL framework, which effectively activates and enhances the model's reasoning ability, without the need for additional continue pre-training. Through this framework, we further uncover the fundamental role of the connector module in achieving robust cross-modal alignment for multimodal reasoning models. In addition, we introduce a unique indicator of reasoning capability, the entropy of critical reasoning tokens, which has proven highly effective for checkpoint selection during RL training. Skywork-R1V3 achieves state-of-the-art results on MMMU, significantly improving from 64.3% to 76.0%. This performance matches entry-level human capabilities. Remarkably, our RL-powered post-training approach enables even the 38B parameter model to rival top closed-source VLMs. The implementation successfully transfers mathematical reasoning to other subject-related reasoning tasks. We also include an analysis of curriculum learning and reinforcement finetuning strategies, along with a broader discussion on multimodal reasoning. Skywork-R1V3 represents a significant leap in multimodal reasoning, showcasing RL as a powerful engine for advancing open-source VLM capabilities.

[Arxiv](https://arxiv.org/abs/2507.06167)