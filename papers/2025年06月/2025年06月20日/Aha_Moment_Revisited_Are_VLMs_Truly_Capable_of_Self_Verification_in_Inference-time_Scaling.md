# # “啊哈”时刻再审视：视觉语言模型在推理时的扩展中是否真的具备自我验证能力？

发布时间：2025年06月20日

`LLM应用` `视觉语言模型` `计算机视觉`

> Aha Moment Revisited: Are VLMs Truly Capable of Self Verification in Inference-time Scaling?

# 摘要

> 近期研究表明，推理时的计算技术（如解码时的缩放和自我完善）可在不依赖外部知识的情况下显著提升大型语言模型（LLMs）的推理能力。这一突破的关键在于强化学习（RL）激发的自我修正和自我验证行为。本文探讨了这些推理时的技术是否能有效扩展至视觉语言模型（VLMs），尤其是那些经过RL训练的模型。研究发现，尽管多数投票和带自我验证的最佳N选择等解码策略均能提升VLM推理性能，但生成依赖的方法（如前者）较验证依赖的方法（如后者）表现出显著更高的提升。值得注意的是，通常与RL调优模型相关的自我修正行为（如顿悟时刻）并未带来显著收益。通过在推理时的缩放框架内进行广泛实验，我们揭示了这一现象的根本原因：RL训练的VLM在视觉和文本模态中仍缺乏强大的自我验证能力。

> Recent advances in large language models (LLMs) have demonstrated that inference-time computation techniques, such as decoding-time scaling and self-refinement, can significantly enhance reasoning capabilities without relying on external knowledge. A key driver of this success is the emergence of self-correction and self-verification behaviors, often elicited through reinforcement learning (RL). In this paper, we investigate whether these inference-time techniques extend effectively to vision-language models (VLMs), particularly those trained with RL. We find that while decoding strategies such as majority voting and best-of-N selection with self-verification all improve VLM reasoning performance, generation-reliant methods such as the former achieve significantly higher gains versus verification-reliant methods such as the latter. Additionally, the self-correction behavior often associated with RL-tuned models, such as aha moment, does not lead to measurable gains. We show via extensive experimentation within the inference-time scaling framework to identify a key root cause: RL-trained VLMs still lack robust self-verification capabilities across both visual and textual modalities.

[Arxiv](https://arxiv.org/abs/2506.17417)