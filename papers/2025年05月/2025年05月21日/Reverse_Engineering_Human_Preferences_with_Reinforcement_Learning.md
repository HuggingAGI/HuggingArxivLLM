# 基于强化学习解析人类偏好

发布时间：2025年05月21日

`LLM理论` `评估框架`

> Reverse Engineering Human Preferences with Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）的能力通常由其他 LLMs 进行评估，这些 LLMs 被训练来预测人类偏好。这种被称为“LLM-as-a-judge”的框架具有高度可扩展性和低成本，但也存在被恶意利用的风险，因为模型可以被调整以适应裁判模型的偏好。先前研究表明，候选 LLM 生成的回答可以在事后被编辑，以最大化裁判 LLM 的评分。在本研究中，我们采用了一种不同的方法，将裁判 LLM 提供的信号作为奖励，通过强化学习来调整生成文本前言的模型，这些前言旨在提升下游性能。我们发现，将这些模型与冻结的 LLM 管道结合使用，可以获得比现有框架更高的评分。至关重要的是，与直接干预模型响应的其他框架不同，我们的方法几乎无法被检测到。此外，我们证明，经过调整的前言生成器在替换候选 LLM 和裁判 LLM 后仍然有效。这些发现引发了关于如何设计更可靠 LLM-as-a-judge 评估框架的重要问题，同时也展示了通过管道化 LLMs 并利用强化学习来优化上游前言，从而有效逆向工程人类偏好的潜力。这种方法未来可能在多种任务和领域中找到应用，而不仅仅是对抗性攻击。

> The capabilities of Large Language Models (LLMs) are routinely evaluated by other LLMs trained to predict human preferences. This framework--known as LLM-as-a-judge--is highly scalable and relatively low cost. However, it is also vulnerable to malicious exploitation, as LLM responses can be tuned to overfit the preferences of the judge. Previous work shows that the answers generated by a candidate-LLM can be edited post hoc to maximise the score assigned to them by a judge-LLM. In this study, we adopt a different approach and use the signal provided by judge-LLMs as a reward to adversarially tune models that generate text preambles designed to boost downstream performance. We find that frozen LLMs pipelined with these models attain higher LLM-evaluation scores than existing frameworks. Crucially, unlike other frameworks which intervene directly on the model's response, our method is virtually undetectable. We also demonstrate that the effectiveness of the tuned preamble generator transfers when the candidate-LLM and the judge-LLM are replaced with models that are not used during training. These findings raise important questions about the design of more reliable LLM-as-a-judge evaluation settings. They also demonstrate that human preferences can be reverse engineered effectively, by pipelining LLMs to optimise upstream preambles via reinforcement learning--an approach that could find future applications in diverse tasks and domains beyond adversarial attacks.

[Arxiv](https://arxiv.org/abs/2505.15795)