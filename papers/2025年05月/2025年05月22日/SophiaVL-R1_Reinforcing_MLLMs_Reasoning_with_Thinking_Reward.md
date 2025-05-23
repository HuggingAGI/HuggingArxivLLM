# SophiaVL-R1：利用思考奖励机制强化多语言大模型的推理能力

发布时间：2025年05月22日

`LLM应用` `人工智能`

> SophiaVL-R1: Reinforcing MLLMs Reasoning with Thinking Reward

# 摘要

> 近期研究展示了通过基于规则的强化学习（RL）结合结果奖励，在多模态大型语言模型（MLLMs）中成功激发强大的推理能力。然而，这一范式通常缺乏对推理过程的有效监督，可能导致模型学习到次优策略，从而影响其泛化能力。为解决这一问题，我们提出了SophiaVL-R1，旨在为推理过程增加奖励信号。为此，我们首先训练了一个评估推理过程质量的思考奖励模型。考虑到奖励欺骗可能导致部分样本的思考奖励不可靠，我们提出了Trust-GRPO方法，在训练过程中为思考奖励分配可信度权重。该权重通过比较正确和错误答案的思考奖励计算得出，有助于缓解不可靠奖励的影响。此外，我们设计了退火训练策略，逐步降低思考奖励的权重，使模型在后期训练中更加依赖准确的规则结果奖励。实验结果显示，我们的SophiaVL-R1在MathVisita、MMMU等基准测试中超越了现有推理MLLMs，展现了强大的推理和泛化能力。值得注意的是，尽管LLaVA-OneVision-72B的参数量是我们的10倍，但SophiaVL-R1-7B在大多数基准测试中表现更优。所有代码、模型和数据集均可在https://github.com/kxfan2002/SophiaVL-R1公开获取。


> Recent advances have shown success in eliciting strong reasoning abilities in multimodal large language models (MLLMs) through rule-based reinforcement learning (RL) with outcome rewards. However, this paradigm typically lacks supervision over the thinking process leading to the final outcome.As a result, the model may learn sub-optimal reasoning strategies, which can hinder its generalization ability. In light of this, we propose SophiaVL-R1, as an attempt to add reward signals for the thinking process in this paradigm. To achieve this, we first train a thinking reward model that evaluates the quality of the entire thinking process. Given that the thinking reward may be unreliable for certain samples due to reward hacking, we propose the Trust-GRPO method, which assigns a trustworthiness weight to the thinking reward during training. This weight is computed based on the thinking reward comparison of responses leading to correct answers versus incorrect answers, helping to mitigate the impact of potentially unreliable thinking rewards. Moreover, we design an annealing training strategy that gradually reduces the thinking reward over time, allowing the model to rely more on the accurate rule-based outcome reward in later training stages. Experiments show that our SophiaVL-R1 surpasses a series of reasoning MLLMs on various benchmarks (e.g., MathVisita, MMMU), demonstrating strong reasoning and generalization capabilities. Notably, our SophiaVL-R1-7B even outperforms LLaVA-OneVision-72B on most benchmarks, despite the latter having 10 times more parameters. All code, models, and datasets are made publicly available at https://github.com/kxfan2002/SophiaVL-R1.

[Arxiv](https://arxiv.org/abs/2505.17018)