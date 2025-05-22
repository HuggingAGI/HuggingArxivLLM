# 学习排序思维链：一种基于能量的监督方法

发布时间：2025年05月20日

`LLM应用` `大型语言模型`

> Learning to Rank Chain-of-Thought: An Energy-Based Approach with Outcome Supervision

# 摘要

> 数学推理对大型语言模型（LLMs）来说是一个重大挑战，通常需要强大的多步逻辑一致性。虽然思维链（CoT）提示能够激发推理步骤，但它并不能保证正确性，而通过大量采样来提高可靠性则计算成本高昂。本文引入了能量结果奖励模型（EORM），一个有效且轻量级的事后验证器。EORM利用能量模型（EBMs）简化奖励模型的训练过程，仅通过结果标签学习为CoT解决方案分配标量能量分数，从而避免了繁琐的详细标注。它通过将判别器输出的logits解释为负能量，对候选方案进行排序，其中正确最终结果的解决方案会隐式获得较低的能量，从而更倾向于连贯的推理。在数学基准测试（GSM8k、MATH）中，EORM显著提高了最终答案的准确性（例如，使用Llama 3 8B模型，在GSM8k上达到90.7%的准确率，在MATH上达到63.7%）。EORM有效地利用给定的候选解决方案池，匹配或超越暴力采样的性能，从而通过其简化的事后验证流程提升了LLM推理结果的可靠性。

> Mathematical reasoning presents a significant challenge for Large Language Models (LLMs), often requiring robust multi step logical consistency. While Chain of Thought (CoT) prompting elicits reasoning steps, it doesn't guarantee correctness, and improving reliability via extensive sampling is computationally costly. This paper introduces the Energy Outcome Reward Model (EORM), an effective, lightweight, post hoc verifier. EORM leverages Energy Based Models (EBMs) to simplify the training of reward models by learning to assign a scalar energy score to CoT solutions using only outcome labels, thereby avoiding detailed annotations. It achieves this by interpreting discriminator output logits as negative energies, effectively ranking candidates where lower energy is assigned to solutions leading to correct final outcomes implicitly favoring coherent reasoning. On mathematical benchmarks (GSM8k, MATH), EORM significantly improves final answer accuracy (e.g., with Llama 3 8B, achieving 90.7% on GSM8k and 63.7% on MATH). EORM effectively leverages a given pool of candidate solutions to match or exceed the performance of brute force sampling, thereby enhancing LLM reasoning outcome reliability through its streamlined post hoc verification process.

[Arxiv](https://arxiv.org/abs/2505.14999)