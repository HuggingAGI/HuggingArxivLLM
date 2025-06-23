# RAST：通过小模型迁移实现LLMs中的推理激活

发布时间：2025年05月30日

`LLM应用` `人工智能` `机器学习`

> RAST: Reasoning Activation in LLMs via Small-model Transfer

# 摘要

> 强化学习（RL）在提升大型语言模型推理能力方面表现出了强大的能力，这一点从 OpenAI 的 o1 和 Deepseek-R1 等近期成功案例中可见一斑。然而，大规模应用 RL 仍面临资源消耗巨大的挑战，需要多份模型副本和大量 GPU 计算资源。另一方面，尽管 RL 强大，但近期研究表明，它并未从根本 上赋予模型新知识，而是主要通过重塑模型的输出分布，激活基础模型中潜藏的推理能力。基于这一洞察，我们假设 RL 引发的输出概率变化在很大程度上与模型规模无关，从而为更高效的方法打开了大门：使用 RL 训练小模型，并将其引发的概率变化迁移至更大的基础模型。为了验证我们的假设，我们对解码轨迹进行了 token 级别的分析，发现不同规模模型中 RL 引发的输出分布高度一致，这证实了我们的假设。由此，我们提出 RAST，这是一种简单而有效的方法，通过将小规模 RL 训练模型引发的概率调整注入到更大规模模型中，从而迁移推理行为。在多个数学推理基准测试中，实验表明 RAST 显著且持续地增强了基础模型的推理能力，同时所需的 GPU 内存远低于直接 RL 训练，有时甚至能超越 RL 训练模型的表现。我们的研究为 RL 驱动推理的本质提供了新的见解，并为在不完全承担其计算成本的情况下扩展其优势提供了实用策略。RAST 的项目页面可在 https://ozyyshr.github.io/RAST/ 查阅。

> Reinforcement learning (RL) has become a powerful approach for improving the reasoning capabilities of large language models (LLMs), as evidenced by recent successes such as OpenAI's o1 and Deepseek-R1. However, applying RL at scale remains intimidatingly resource-intensive, requiring multiple model copies and extensive GPU workloads. On the other hand, while being powerful, recent studies suggest that RL does not fundamentally endow models with new knowledge; rather, it primarily reshapes the model's output distribution to activate reasoning capabilities latent in the base model. Building on this insight, we hypothesize that the changes in output probabilities induced by RL are largely model-size invariant, opening the door to a more efficient paradigm: training a small model with RL and transferring its induced probability shifts to larger base models. To verify our hypothesis, we conduct a token-level analysis of decoding trajectories and find high alignment in RL-induced output distributions across model scales, validating our hypothesis. Motivated by this, we propose RAST, a simple yet effective method that transfers reasoning behaviors by injecting RL-induced probability adjustments from a small RL-trained model into larger models. Experiments across multiple mathematical reasoning benchmarks show that RAST substantially and consistently enhances the reasoning capabilities of base models while requiring significantly lower GPU memory than direct RL training, sometimes even yielding better performance than the RL-trained counterparts. Our findings offer new insights into the nature of RL-driven reasoning and practical strategies for scaling its benefits without incurring its full computational cost. The project page of RAST is available at https://ozyyshr.github.io/RAST/.

[Arxiv](https://arxiv.org/abs/2506.15710)