# # 自适应超参数优化的序列策略梯度

发布时间：2025年06月17日

`LLM理论` `计算机视觉`

> Sequential Policy Gradient for Adaptive Hyperparameter Optimization

# 摘要

> 强化学习在神经架构搜索和超参数优化中至关重要，但传统方法由于耗时耗力，阻碍了其广泛应用。受DeepSeek-V3多标记预测架构启发，我们提出了一种轻量级在线超参数优化的新型轨迹生成范式，称为顺序策略梯度建模（SPG）。与传统策略梯度方法不同，SPG通过扩展基础模型的临时模块，使其能在单次前向传播中生成状态-动作（填充）轨迹。实验表明，使用SPG在原数据集上重新训练模型能提升性能，且优于标准迁移微调。我们在涵盖计算机视觉（ImageNet、COCO）、自然语言处理（GLUE、SQuAD）和音频（SUPERB）的五个数据集上进行评估，以验证SPG的工业适用性。该方法在广泛应用的模型上表现出一致的性能提升，增益达【数学公式】，且计算成本极低。完整可复现代码和预训练模型：https://huggingface.co/UniversalAlgorithmic/SPG。

> Reinforcement learning is essential for neural architecture search and hyperparameter optimization, but the conventional approaches impede widespread use due to prohibitive time and computational costs. Inspired by DeepSeek-V3 multi-token prediction architecture, we propose Sequential Policy Gradient modeling (SPG), a novel trajectory generation paradigm for lightweight online hyperparameter optimization. In contrast to conventional policy gradient methods, SPG extends the base model with temporary modules, enabling it to generate state-action (padded) trajectories in a single forward pass. Our experiments demonstrate that models gain performance when retrained with SPG on their original datasets and also outperform standard transfer fine-tuning. We evaluate on five datasets spanning computer vision (ImageNet, COCO), natural language processing (GLUE, SQuAD), and audio (SUPERB) to assess the industrial applicability of SPG. The proposed method demonstrates consistent improvements across widely adopted models, achieving performance gains of $+0.2\sim7\%$, with significantly low computational costs. Fully reproducible code and pre-trained models: https://huggingface.co/UniversalAlgorithmic/SPG.

[Arxiv](https://arxiv.org/abs/2506.15051)