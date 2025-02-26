# SYNTHEMPATHY：无需众包，基于LLMs生成的可扩展共情语料库。

发布时间：2025年02月25日

`LLM应用` `对话系统`

> SYNTHEMPATHY: A Scalable Empathy Corpus Generated Using LLMs Without Any Crowdsourcing

# 摘要

> 此前研究发现，人类更倾向于接受那些表现出同理心的语言模型。虽然同理心对于打造有帮助的对话系统至关重要，但目前可用于微调大型语言模型 (LLMs) 的大规模共情对话数据集却寥寥无几。现有的少数数据集主要依赖众包模拟共情对话，这种方式成本高昂、耗时且难以扩展。我们提出了一种数据生成框架，用于构建SYNTHEMPATHY——一个包含10.5万个针对真实场景的共情回应的大型语料库，这些回应由LLM生成。在SYNTHEMPATHY语料库上微调后的Mistral 7B模型，其平均共情评分显著提升。

> Previous research has shown that humans are more receptive towards language models that that exhibit empathetic behavior. While empathy is essential for developing helpful dialogue agents, very few large corpora containing empathetic dialogues are available for fine-tune LLMs. The few existing corpora have largely relied on crowdsourcing to simulate empathetic conversations, a process that is expensive, time-consuming, and not scalable to larger datasets. We propose a data generation framework for developing SYNTHEMPATHY, a large corpus containing 105k empathetic responses to real-life situations compiled through LLM generation. A base Mistral 7B model fine-tuned on our SYNTHEMPATHY corpus exhibits an increase in the average empathy score.

[Arxiv](https://arxiv.org/abs/2502.17857)