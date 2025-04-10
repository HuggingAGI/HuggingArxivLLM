# # VideoChat-R1：通过强化微调提升时空感知能力

发布时间：2025年04月09日

`LLM应用` `视频处理` `问答系统`

> VideoChat-R1: Enhancing Spatio-Temporal Perception via Reinforcement Fine-Tuning

# 摘要

> 强化学习的最新进展显著提升了多模态大型语言模型（MLLMs）的推理能力。尽管基于群体相对策略优化（GRPO）和基于规则的奖励机制等方法在文本和图像领域展现出潜力，但它们在视频理解方面的应用仍然有限。本文系统性地探索了基于GRPO的强化微调（RFT）在视频MLLMs中的应用，旨在提升空间-时间感知能力的同时保持模型的通用能力。我们的实验表明，RFT在特定任务上的改进具有高度数据效率。通过在空间-时间感知目标上进行多任务RFT且仅使用有限样本，我们开发了VideoChat-R1——一款强大的视频MLLM，它在空间-时间感知任务上达到了最先进水平，同时保持了聊天能力，并展现出新兴的空间-时间推理能力。与Qwen2.5-VL-7B相比，VideoChat-R1在时间定位（+31.8）和目标跟踪（+31.2）等任务上性能提升了数倍。此外，它在VideoMME、MVBench和Perception Test等通用问答基准测试上也取得了显著提升（分别提高+0.9、+1.0和+0.9）。我们的研究结果凸显了RFT在提升视频MLLMs专用任务性能方面的潜力。我们希望这项工作能为未来视频MLLMs的强化学习研究提供有价值的见解。

> Recent advancements in reinforcement learning have significantly advanced the reasoning capabilities of multimodal large language models (MLLMs). While approaches such as Group Relative Policy Optimization (GRPO) and rule-based reward mechanisms demonstrate promise in text and image domains, their application to video understanding remains limited. This paper presents a systematic exploration of Reinforcement Fine-Tuning (RFT) with GRPO for video MLLMs, aiming to enhance spatio-temporal perception while maintaining general capabilities. Our experiments reveal that RFT is highly data-efficient for task-specific improvements. Through multi-task RFT on spatio-temporal perception objectives with limited samples, we develop VideoChat-R1, a powerful video MLLM that achieves state-of-the-art performance on spatio-temporal perception tasks without sacrificing chat ability, while exhibiting emerging spatio-temporal reasoning abilities. Compared to Qwen2.5-VL-7B, VideoChat-R1 boosts performance several-fold in tasks like temporal grounding (+31.8) and object tracking (+31.2). Additionally, it significantly improves on general QA benchmarks such as VideoMME (+0.9), MVBench (+1.0), and Perception Test (+0.9). Our findings underscore the potential of RFT for specialized task enhancement of Video MLLMs. We hope our work offers valuable insights for future RL research in video MLLMs.

[Arxiv](https://arxiv.org/abs/2504.06958)