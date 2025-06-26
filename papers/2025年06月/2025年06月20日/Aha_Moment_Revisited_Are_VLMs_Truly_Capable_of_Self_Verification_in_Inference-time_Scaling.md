# 再探顿悟时刻：VLMs在推理时的缩放能力是否真的具备自我验证的能力？

发布时间：2025年06月20日

`LLM理论` `计算机视觉`

> Aha Moment Revisited: Are VLMs Truly Capable of Self Verification in Inference-time Scaling?

# 摘要

> 近期研究表明，大型语言模型（LLMs）在推理时采用解码缩放和自我改进等技巧，能够显著提升推理能力，无需依赖外部知识。这一成功的关键在于强化学习（RL）激发的自我修正和自我验证行为。本研究旨在探讨这些推理技巧是否能有效应用于视觉语言模型（VLMs），尤其是RL训练的模型。实验发现，尽管多数投票和最佳选择等解码策略结合自我验证均能提升VLM性能，但生成依赖的方法（如多数投票）相较于验证依赖的方法（如最佳选择）表现更优。此外，RL调整模型的自我修正行为，如顿悟时刻，并未带来显著提升。通过广泛实验，我们发现强化学习训练的VLM在视觉和文本模态上仍缺乏稳健的自我验证能力。

> Recent advances in large language models (LLMs) have demonstrated that inference-time computation techniques, such as decoding-time scaling and self-refinement, can significantly enhance reasoning capabilities without relying on external knowledge. A key driver of this success is the emergence of self-correction and self-verification behaviors, often elicited through reinforcement learning (RL). In this paper, we investigate whether these inference-time techniques extend effectively to vision-language models (VLMs), particularly those trained with RL. We find that while decoding strategies such as majority voting and best-of-N selection with self-verification all improve VLM reasoning performance, generation-reliant methods such as the former achieve significantly higher gains versus verification-reliant methods such as the latter. Additionally, the self-correction behavior often associated with RL-tuned models, such as aha moment, does not lead to measurable gains. We show via extensive experimentation within the inference-time scaling framework to identify a key root cause: RL-trained VLMs still lack robust self-verification capabilities across both visual and textual modalities.

[Arxiv](https://arxiv.org/abs/2506.17417)