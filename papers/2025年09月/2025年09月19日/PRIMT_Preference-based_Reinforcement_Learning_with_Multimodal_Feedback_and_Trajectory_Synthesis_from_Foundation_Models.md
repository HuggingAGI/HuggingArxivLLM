# PRIMT：基于偏好的强化学习——结合基础模型的多模态反馈与轨迹合成

发布时间：2025年09月19日

`强化学习` `工业与制造`

> PRIMT: Preference-based Reinforcement Learning with Multimodal Feedback and Trajectory Synthesis from Foundation Models

# 摘要

> 基于偏好的强化学习（PbRL）无需奖励工程即可教授机器人复杂行为，已成为极具潜力的范式。然而，其效果常受两大核心挑战制约：一是过度依赖人工输入，二是在奖励学习中解决查询模糊性与信用分配时存在固有难题。本文提出PRIMT框架，通过借助基础模型（FMs）实现多模态合成反馈与轨迹合成，旨在攻克这些挑战。与依赖单模态FM评估的传统方法不同，PRIMT采用层次化神经符号融合策略，整合大型语言模型与视觉-语言模型在机器人行为评估中的互补优势，从而提供更可靠、全面的反馈。此外，PRIMT还融入远见轨迹生成（通过引导样本预热轨迹缓冲区以减少早期查询模糊性）和后见轨迹增强（利用因果辅助损失实现反事实推理以优化信用分配）。我们在多个基准测试的2项运动任务与6项操作任务上对PRIMT进行评估，结果显示其性能显著优于基于FM的基线和脚本化基线。

> Preference-based reinforcement learning (PbRL) has emerged as a promising paradigm for teaching robots complex behaviors without reward engineering. However, its effectiveness is often limited by two critical challenges: the reliance on extensive human input and the inherent difficulties in resolving query ambiguity and credit assignment during reward learning. In this paper, we introduce PRIMT, a PbRL framework designed to overcome these challenges by leveraging foundation models (FMs) for multimodal synthetic feedback and trajectory synthesis. Unlike prior approaches that rely on single-modality FM evaluations, PRIMT employs a hierarchical neuro-symbolic fusion strategy, integrating the complementary strengths of large language models and vision-language models in evaluating robot behaviors for more reliable and comprehensive feedback. PRIMT also incorporates foresight trajectory generation, which reduces early-stage query ambiguity by warm-starting the trajectory buffer with bootstrapped samples, and hindsight trajectory augmentation, which enables counterfactual reasoning with a causal auxiliary loss to improve credit assignment. We evaluate PRIMT on 2 locomotion and 6 manipulation tasks on various benchmarks, demonstrating superior performance over FM-based and scripted baselines.

[Arxiv](https://arxiv.org/abs/2509.15607)