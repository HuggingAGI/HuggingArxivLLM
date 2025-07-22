# 稳定知识，推动推理：RLVR的双标记约束机制

发布时间：2025年07月21日

`LLM应用`

> Stabilizing Knowledge, Promoting Reasoning: Dual-Token Constraints for RLVR

# 摘要

> 可验证奖励的强化学习（RLVR）作为一种提升大型语言模型（LLMs）推理能力的后训练方法，通过塑造反思和规划等高阶行为展现出显著效果。然而，传统RLVR算法往往对所有令牌施加统一的训练信号，忽视了低熵知识相关令牌与高熵推理相关令牌之间的差异。尽管一些 recent 方法尝试通过梯度屏蔽或异步更新来区分这两种令牌，但这些手段可能破坏模型输出中的语义依赖，影响学习效果。为此，我们提出了一种基于熵感知的RLVR方法——Archer，采用双令牌约束和同步更新机制。具体而言，我们的方法对推理令牌施加较弱的KL正则化和较高的剪裁阈值，以促进探索；同时对知识令牌设置更强的约束，确保事实知识的准确性。实验结果表明，Archer在多个数学推理和代码生成基准测试中显著超越传统RLVR方法，性能达到或超越同类规模模型的最先进水平。代码已开源，地址为https://github.com/wizard-III/ArcherCodeR。

> Reinforcement Learning with Verifiable Rewards (RLVR) has become an effective post-training method for improving the reasoning abilities of Large Language Models (LLMs), mainly by shaping higher-order behaviors such as reflection and planning. However, previous RLVR algorithms often apply uniform training signals to all tokens, without considering the different roles of low-entropy knowledge-related tokens and high-entropy reasoning-related tokens. Some recent methods try to separate these token types by gradient masking or asynchronous updates, but these approaches may break semantic dependencies in the model output and hinder effective learning. In this work, we propose Archer, an entropy-aware RLVR approach with dual-token constraints and synchronous updates. Specifically, our method applies weaker KL regularization and higher clipping thresholds to reasoning tokens to encourage exploration, while using stronger constraints on knowledge tokens to maintain factual knowledge. Experimental results on several mathematical reasoning and code generation benchmarks show that our approach significantly outperforms previous RLVR methods, reaching or exceeding state-of-the-art performance among models of comparable size. The code is available at https://github.com/wizard-III/ArcherCodeR.

[Arxiv](https://arxiv.org/abs/2507.15778)