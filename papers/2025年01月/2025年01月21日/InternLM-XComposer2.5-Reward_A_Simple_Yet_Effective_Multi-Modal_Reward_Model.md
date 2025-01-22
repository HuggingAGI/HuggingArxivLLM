# InternLM-XComposer2.5-Reward: 简洁高效的多模态奖励模型

发布时间：2025年01月21日

`LLM应用

**理由**：该论文主要讨论了如何通过开发一个多模态奖励模型（IXC-2.5-Reward）来提升大型视觉语言模型（LVLMs）的生成质量，并将其与人类偏好对齐。论文还展示了该模型在多个应用场景中的使用，如强化学习训练、测试时缩放和过滤噪声样本等。这些内容主要涉及如何将大型语言模型应用于实际任务中，因此归类为LLM应用。` `多模态学习`

> InternLM-XComposer2.5-Reward: A Simple Yet Effective Multi-Modal Reward Model

# 摘要

> 尽管大型视觉语言模型（LVLMs）在视觉理解方面表现出色，但它们有时会生成错误输出。虽然强化学习或测试时缩放的奖励模型（RMs）有望提升生成质量，但公开可用的多模态RMs仍然稀缺，且专有模型的实现细节往往不透明。为此，我们推出了InternLM-XComposer2.5-Reward（IXC-2.5-Reward），这是一个简单但高效的多模态奖励模型，能够将LVLMs与人类偏好对齐。为确保其鲁棒性和多功能性，我们构建了一个高质量的多模态偏好语料库，涵盖文本、图像和视频输入，涉及指令遵循、通用理解、文本丰富的文档、数学推理和视频理解等多个领域。IXC-2.5-Reward在最新的多模态奖励模型基准测试中表现优异，并在仅文本奖励模型基准测试中展现出竞争力。我们进一步展示了IXC-2.5-Reward的三大应用：（1）为RL训练提供监督信号。通过将IXC-2.5-Reward与近端策略优化（PPO）结合，我们开发了IXC-2.5-Chat，在指令遵循和多模态开放式对话方面持续改进；（2）从候选响应中选择最佳响应进行测试时缩放；（3）从现有的图像和视频指令调优训练数据中过滤异常或噪声样本。为促进可重复性和进一步研究，我们已在https://github.com/InternLM/InternLM-XComposer开源了所有模型权重和训练配方。

> Despite the promising performance of Large Vision Language Models (LVLMs) in visual understanding, they occasionally generate incorrect outputs. While reward models (RMs) with reinforcement learning or test-time scaling offer the potential for improving generation quality, a critical gap remains: publicly available multi-modal RMs for LVLMs are scarce, and the implementation details of proprietary models are often unclear. We bridge this gap with InternLM-XComposer2.5-Reward (IXC-2.5-Reward), a simple yet effective multi-modal reward model that aligns LVLMs with human preferences. To ensure the robustness and versatility of IXC-2.5-Reward, we set up a high-quality multi-modal preference corpus spanning text, image, and video inputs across diverse domains, such as instruction following, general understanding, text-rich documents, mathematical reasoning, and video understanding. IXC-2.5-Reward achieves excellent results on the latest multi-modal reward model benchmark and shows competitive performance on text-only reward model benchmarks. We further demonstrate three key applications of IXC-2.5-Reward: (1) Providing a supervisory signal for RL training. We integrate IXC-2.5-Reward with Proximal Policy Optimization (PPO) yields IXC-2.5-Chat, which shows consistent improvements in instruction following and multi-modal open-ended dialogue; (2) Selecting the best response from candidate responses for test-time scaling; and (3) Filtering outlier or noisy samples from existing image and video instruction tuning training data. To ensure reproducibility and facilitate further research, we have open-sourced all model weights and training recipes at https://github.com/InternLM/InternLM-XComposer

[Arxiv](https://arxiv.org/abs/2501.12368)