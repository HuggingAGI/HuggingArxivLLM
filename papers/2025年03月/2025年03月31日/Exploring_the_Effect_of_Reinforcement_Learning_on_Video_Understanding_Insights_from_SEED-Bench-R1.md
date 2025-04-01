# 强化学习如何影响视频理解？SEED-Bench-R1 的研究发现为你解答。

发布时间：2025年03月31日

`LLM应用` `视频理解` `多模态`

> Exploring the Effect of Reinforcement Learning on Video Understanding: Insights from SEED-Bench-R1

# 摘要

> # 近期进展：Chain of Thought生成技术显著提升大型语言模型推理能力
Chain of Thought (COT) 生成技术的突破性进展显著提升了大型语言模型 (LLMs) 的推理能力，其中强化学习 (RL) 作为一项有效的后训练方法脱颖而出。然而，多模态大型语言模型 (MLLMs) 虽然继承了这种推理潜力，但在需要结合感知与逻辑推理的任务中仍存在较大的探索空间。

为解决这一问题，我们推出了SEED-Bench-R1，这是一个专注于系统评估MLLMs视频理解后训练方法的基准测试。该基准包含复杂的现实视频和日常规划任务，以多项选择题形式呈现，要求模型具备高级感知与推理能力。SEED-Bench-R1通过三级评估体系（同分布、跨环境、跨环境任务）全面检验模型的泛化能力，并配备大规模训练数据集和易于验证的真值答案。

基于Qwen2-VL-Instruct-7B模型，我们对比了强化学习 (RL) 与监督微调 (SFT) 方法，结果显示RL在数据效率和性能上均优于SFT，尤其在跨分布任务中表现突出，甚至超越SFT在LongVideoBench等通用视频理解基准测试中的表现。我们的深入分析表明，RL能够有效提升模型的视觉感知能力，但其推理链的逻辑连贯性仍有待提升。我们还指出当前模型在推理一致性及视觉线索捕捉方面的局限性，并为未来改进基础模型推理能力、奖励建模及RL对噪声信号的鲁棒性提出了具体建议。


> Recent advancements in Chain of Thought (COT) generation have significantly improved the reasoning capabilities of Large Language Models (LLMs), with reinforcement learning (RL) emerging as an effective post-training approach. Multimodal Large Language Models (MLLMs) inherit this reasoning potential but remain underexplored in tasks requiring both perception and logical reasoning. To address this, we introduce SEED-Bench-R1, a benchmark designed to systematically evaluate post-training methods for MLLMs in video understanding. It includes intricate real-world videos and complex everyday planning tasks in the format of multiple-choice questions, requiring sophisticated perception and reasoning. SEED-Bench-R1 assesses generalization through a three-level hierarchy: in-distribution, cross-environment, and cross-environment-task scenarios, equipped with a large-scale training dataset with easily verifiable ground-truth answers. Using Qwen2-VL-Instruct-7B as a base model, we compare RL with supervised fine-tuning (SFT), demonstrating RL's data efficiency and superior performance on both in-distribution and out-of-distribution tasks, even outperforming SFT on general video understanding benchmarks like LongVideoBench. Our detailed analysis reveals that RL enhances visual perception but often produces less logically coherent reasoning chains. We identify key limitations such as inconsistent reasoning and overlooked visual cues, and suggest future improvements in base model reasoning, reward modeling, and RL robustness against noisy signals.

[Arxiv](https://arxiv.org/abs/2503.24376)