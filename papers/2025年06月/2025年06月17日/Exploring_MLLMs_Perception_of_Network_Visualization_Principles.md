# MLLMs 对网络可视化原则的理解探索

发布时间：2025年06月17日

`LLM应用` `计算机网络` `系统设计`

> Exploring MLLMs Perception of Network Visualization Principles

# 摘要

> 本文探讨了多模态大型语言模型（MLLMs）能否在涉及网络布局属性感知的任务中达到与人类相当的水平。我们使用GPT-4o和Gemini-2.5复制了一个关于感知网络布局质量（压力）的人类实验。实验结果表明，当MLLMs获得与经过训练的人类参与者相同的研宄信息时，其表现可与人类专家媲美，甚至超越了未经训练的非专家。此外，我们发现，与人类实验不同的提示工程在某些情况下能够实现超越人类的表现。有趣的是，MLLMs似乎像人类受试者一样依赖于视觉代理，而非计算压力的实际值，这表明它们具有某种感知能力或感知的替代形式。模型的解释与人类参与者的描述相似，例如节点的均匀分布和边长的均匀性。

> In this paper, we test whether Multimodal Large Language Models (MLLMs) can match human-subject performance in tasks involving the perception of properties in network layouts. Specifically, we replicate a human-subject experiment about perceiving quality (namely stress) in network layouts using GPT-4o and Gemini-2.5. Our experiments show that giving MLLMs exactly the same study information as trained human participants results in a similar performance to human experts and exceeds the performance of untrained non-experts. Additionally, we show that prompt engineering that deviates from the human-subject experiment can lead to better-than-human performance in some settings. Interestingly, like human subjects, the MLLMs seem to rely on visual proxies rather than computing the actual value of stress, indicating some sense or facsimile of perception. Explanations from the models provide descriptions similar to those used by the human participants (e.g., even distribution of nodes and uniform edge lengths).

[Arxiv](https://arxiv.org/abs/2506.14611)