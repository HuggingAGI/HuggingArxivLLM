# MOSS-ChatV：基于过程推理奖励的强化学习助力视频时序推理

发布时间：2025年09月25日

`强化学习` `媒体与娱乐`

> MOSS-ChatV: Reinforcement Learning with Process Reasoning Reward for Video Temporal Reasoning

# 摘要

> 视频推理已成为多模态大型语言模型（MLLMs）的核心能力，这要求模型不仅要具备静态感知能力，更要能连贯理解复杂场景中的时间动态。然而，现有MLLMs常存在推理过程不一致的问题：即使最终答案正确，中间推理过程也可能与视频动态脱节，这影响了模型的可解释性和鲁棒性。为解决这一问题，我们提出了MOSS-ChatV——一个基于动态时间规整（DTW）过程奖励的强化学习框架。这种基于规则的奖励机制能使推理轨迹与时间锚定参考对齐，无需辅助奖励模型即可实现高效的过程监督。我们进一步将动态状态预测确定为衡量视频推理能力的关键指标，并构建了包含带注释推理轨迹的MOSS-Video基准，其训练集用于微调MOSS-ChatV，预留的测试集则用于评估。MOSS-ChatV在MOSS-Video测试集上准确率达87.2%，在MVBench、MMVU等通用视频基准测试中也表现更优。该框架在Qwen2.5-VL和Phi-2等不同架构上均能持续提升性能，证明了其广泛适用性。通过GPT-4o作为评判的评估进一步显示，MOSS-ChatV生成的推理轨迹更一致、更稳定。

> Video reasoning has emerged as a critical capability for multimodal large language models (MLLMs), requiring models to move beyond static perception toward coherent understanding of temporal dynamics in complex scenes. Yet existing MLLMs often exhibit process inconsistency, where intermediate reasoning drifts from video dynamics even when the final answer is correct, undermining interpretability and robustness. To address this issue, we introduce MOSS-ChatV, a reinforcement learning framework with a Dynamic Time Warping (DTW)-based process reward. This rule-based reward aligns reasoning traces with temporally grounded references, enabling efficient process supervision without auxiliary reward models. We further identify dynamic state prediction as a key measure of video reasoning and construct MOSS-Video, a benchmark with annotated reasoning traces, where the training split is used to fine-tune MOSS-ChatV and the held-out split is reserved for evaluation. MOSS-ChatV achieves 87.2\% on MOSS-Video (test) and improves performance on general video benchmarks such as MVBench and MMVU. The framework consistently yields gains across different architectures, including Qwen2.5-VL and Phi-2, confirming its broad applicability. Evaluations with GPT-4o-as-judge further show that MOSS-ChatV produces more consistent and stable reasoning traces.

[Arxiv](https://arxiv.org/abs/2509.21113)