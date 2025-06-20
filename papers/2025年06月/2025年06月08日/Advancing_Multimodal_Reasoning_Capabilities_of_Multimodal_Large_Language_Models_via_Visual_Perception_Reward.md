# 通过视觉感知奖励提升多模态大语言模型的多模态推理能力

发布时间：2025年06月08日

`LLM应用` `人工智能` `机器学习`

> Advancing Multimodal Reasoning Capabilities of Multimodal Large Language Models via Visual Perception Reward

# 摘要

> 提升多模态大语言模型（MLLMs）的多模态推理能力是一项充满挑战且备受关注的任务。近期研究尝试通过强化学习（RLVR）提升MLLMs的推理能力，但忽视了对其多模态感知能力的提升——这是复杂推理的基础。通过McNemar检验，我们发现现有方法未能有效提升MLLMs的感知能力，限制了其推理性能的进一步提升。为此，我们提出了Perception-R1，引入新型视觉感知奖励，鼓励MLLMs准确感知视觉内容，从而同时提升其感知与推理能力。具体而言，我们从多模态问题的CoT轨迹中提取文本视觉注释作为参考，在RLVR训练中利用判别性LLM评估注释与模型响应的一致性，并据此分配奖励。实验表明，仅用1,442个训练数据，Perception-R1就在多个基准上取得了最先进的性能，证明了其有效性。

> Enhancing the multimodal reasoning capabilities of Multimodal Large Language Models (MLLMs) is a challenging task that has attracted increasing attention in the community. Recently, several studies have applied Reinforcement Learning with Verifiable Rewards (RLVR) to the multimodal domain in order to enhance the reasoning abilities of MLLMs. However, these works largely overlook the enhancement of multimodal perception capabilities in MLLMs, which serve as a core prerequisite and foundational component of complex multimodal reasoning. Through McNemar's test, we find that existing RLVR method fails to effectively enhance the multimodal perception capabilities of MLLMs, thereby limiting their further improvement in multimodal reasoning. To address this limitation, we propose Perception-R1, which introduces a novel visual perception reward that explicitly encourages MLLMs to perceive the visual content accurately, thereby can effectively incentivizing both their multimodal perception and reasoning capabilities. Specifically, we first collect textual visual annotations from the CoT trajectories of multimodal problems, which will serve as visual references for reward assignment. During RLVR training, we employ a judging LLM to assess the consistency between the visual annotations and the responses generated by MLLM, and assign the visual perception reward based on these consistency judgments. Extensive experiments on several multimodal reasoning benchmarks demonstrate the effectiveness of our Perception-R1, which achieves state-of-the-art performance on most benchmarks using only 1,442 training data.

[Arxiv](https://arxiv.org/abs/2506.07218)