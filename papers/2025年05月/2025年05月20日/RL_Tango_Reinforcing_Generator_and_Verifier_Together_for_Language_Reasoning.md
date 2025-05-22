# # RL探戈：强化生成器与验证器协同提升语言推理能力

发布时间：2025年05月20日

`LLM理论` `语言模型`

> RL Tango: Reinforcing Generator and Verifier Together for Language Reasoning

# 摘要

> 强化学习（RL）作为一种提升大型语言模型（LLMs）推理能力的强有力方法，最近备受关注。在这一框架中，LLM生成器作为策略，由验证器（奖励模型）进行引导。然而，当前针对LLMs的RL后训练方法存在以下局限：它们通常使用固定的验证器（基于规则或冻结的预训练模型），或者通过监督微调（SFT）进行判别式训练。这些设计不仅容易受到奖励欺骗的影响，而且在训练分布之外的表现也较为有限。为了解决这些问题，我们提出了Tango——一个创新的框架，通过强化学习同时以交错方式训练LLM生成器和验证器。Tango的核心创新在于其独特的生成式、过程级别的LLM验证器。该验证器通过强化学习进行训练，并与生成器协同进化。值得注意的是，这一验证器仅基于结果级别的验证正确性奖励进行训练，无需显式的流程级别标注。与传统的确定性或SFT训练的验证器相比，这种通过生成式强化学习训练的验证器展现出更强的鲁棒性和更好的泛化能力，与生成器实现了有效的相互强化。通过大量实验，我们发现Tango的两个组件在70亿/80亿规模的模型中均达到了最先进水平。具体而言，生成器在五个竞赛级别的数学基准测试和四个具有挑战性的跨领域推理任务中取得了最佳性能，而验证器在ProcessBench数据集上处于领先地位。特别值得一提的是，两个组件在最困难的数学推理问题上都表现出特别显著的提升。代码位于：https://github.com/kaiwenzha/rl-tango。

> Reinforcement learning (RL) has recently emerged as a compelling approach for enhancing the reasoning capabilities of large language models (LLMs), where an LLM generator serves as a policy guided by a verifier (reward model). However, current RL post-training methods for LLMs typically use verifiers that are fixed (rule-based or frozen pretrained) or trained discriminatively via supervised fine-tuning (SFT). Such designs are susceptible to reward hacking and generalize poorly beyond their training distributions. To overcome these limitations, we propose Tango, a novel framework that uses RL to concurrently train both an LLM generator and a verifier in an interleaved manner. A central innovation of Tango is its generative, process-level LLM verifier, which is trained via RL and co-evolves with the generator. Importantly, the verifier is trained solely based on outcome-level verification correctness rewards without requiring explicit process-level annotations. This generative RL-trained verifier exhibits improved robustness and superior generalization compared to deterministic or SFT-trained verifiers, fostering effective mutual reinforcement with the generator. Extensive experiments demonstrate that both components of Tango achieve state-of-the-art results among 7B/8B-scale models: the generator attains best-in-class performance across five competition-level math benchmarks and four challenging out-of-domain reasoning tasks, while the verifier leads on the ProcessBench dataset. Remarkably, both components exhibit particularly substantial improvements on the most difficult mathematical reasoning problems. Code is at: https://github.com/kaiwenzha/rl-tango.

[Arxiv](https://arxiv.org/abs/2505.15034)