# # 揭示大型多模态模型中的时间之箭

发布时间：2025年06月03日

`LLM应用` `视频分析` `视频问答`

> Seeing the Arrow of Time in Large Multimodal Models

# 摘要

> 时间之箭——时间不可逆的流动塑造了物理事件——是视频理解的基础，但对于现代大型多模态模型（LMMs）来说，这仍然是一个重大挑战。当前的LMMs在面对语言查询时，难以感知和利用视频中的时间方向性，阻碍了对时间的更深层次理解。我们通过首先对现有基准和模型进行关键分析来解决这一缺陷。然后，我们引入ArrowRL，这是一种基于强化学习（RL）的训练策略，采用了创新的反向奖励机制，通过鼓励正向和反向视觉帧之间的不同视频解释来灌输时间之箭意识。为了进行严格的评估，我们还开发了AoTBench，这是一个新的多方面基准，用于探测具有时间挑战性的问题。实验表明，ArrowRL大大提升了时间感知能力：它不仅在我们的具有挑战性的AoTBench上取得了显著改进，还在标准的视频问答（VQA）基准测试中明显提高了性能（峰值准确率分别提高了20%和10%以上）。这验证了ArrowRL的有效性，并突显了在LMMs中专门理解时间之箭的重要性。

> The Arrow of Time (AoT)-time's irreversible flow shaping physical events-is fundamental to video comprehension, yet remains a significant challenge for modern large multimodal models (LMMs). Current LMMs struggle to perceive and utilize temporal directionality in video when responding to language queries, obstructing deeper temporal understanding. We tackle this deficiency by first providing a critical analysis of existing benchmarks and models. We then introduce ArrowRL, a reinforcement learning (RL)-based training strategy with an innovative reverse reward that instills AoT awareness by encouraging divergent video interpretations between forward and reversed visual frames. For rigorous evaluation, we additionally develop AoTBench, a new multi-faceted benchmark probing temporally challenging questions. Experiments show ArrowRL greatly advances temporal perception: it not only achieves substantial improvements on our challenging AoTBench but also demonstrably boosts performance on standard video question answering (VQA) benchmarks (with peak accuracy gains reaching over 20% and 10% respectively). This validates ArrowRL's effectiveness and highlights the critical need for dedicated AoT understanding in LMMs.

[Arxiv](https://arxiv.org/abs/2506.03340)