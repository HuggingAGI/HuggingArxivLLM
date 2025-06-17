# BOW: 瓶颈式单词探索

发布时间：2025年06月16日

`LLM理论

摘要内容讨论了大型语言模型（LLMs）的训练方法和架构改进，特别是提出了一种新的强化学习框架（BOW）。该框架重新定义了下一个单词预测（NWP）任务，并通过强化学习策略模型来提升模型的推理能力。这些内容属于对LLM本身的理论和训练方法的研究，因此归类为LLM理论。` `人工智能` `机器学习`

> BOW: Bottlenecked Next Word Exploration

# 摘要

> 大型语言模型（LLMs）通常通过下一个单词预测（NWP）进行训练，虽然这提供了强大的表面流畅性，但往往缺乏对稳健推理的支持。为此，我们提出了一种名为BOW（瓶颈化单词探索）的新型强化学习框架，重新定义了NWP：策略模型首先生成推理路径，而非直接预测下一个标记，随后一个冻结的判别模型仅依据该推理路径预测下一个标记的分布。我们采用GRPO训练策略模型，奖励机制量化了推理路径对下一个单词恢复的促进效果。与其它持续预训练基线相比，BOW显著提升了基础模型的通用推理和下一个单词推理能力，并在多种基准测试中得到验证。研究结果表明，BOW可作为传统NWP的有效且可扩展的替代方案。

> Large language models (LLMs) are typically trained via next-word prediction (NWP), which provides strong surface-level fluency but often lacks support for robust reasoning. We propose BOttlenecked next Word exploration (BOW), a novel RL framework that rethinks NWP by introducing a reasoning bottleneck where a policy model first generates a reasoning path rather than predicting the next token directly, after which a frozen judge model predicts the next token distribution based solely on this reasoning path. We train the policy model using GRPO with rewards that quantify how effectively the reasoning path facilitates next-word recovery. Compared with other continual pretraining baselines, we show that BOW improves both the general and next-word reasoning capabilities of the base model, evaluated on various benchmarks. Our findings show that BOW can serve as an effective and scalable alternative to vanilla NWP.

[Arxiv](https://arxiv.org/abs/2506.13502)