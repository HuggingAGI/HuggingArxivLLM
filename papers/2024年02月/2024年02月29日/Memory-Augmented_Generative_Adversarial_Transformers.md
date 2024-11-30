# 记忆强化的生成对抗Transformer模型

发布时间：2024年02月29日

`Agent`

> Memory-Augmented Generative Adversarial Transformers

# 摘要

> 基于大型语言模型（如Transformer）的对话AI系统，在融合理论知识与生成语言时面临挑战，它们往往难以精准回答事实性问题。本研究提出了一种改进方案，即在标准Transformer结构基础上增加一个包含额外信息（如来自知识库的事实）的记忆库，以及一个用于检索该记忆的新注意力层，并将此扩展内存融入GAN启发的Transformer架构中。这一创新设计使我们可以灵活控制Transformer生成语言的得体性。实验首先展示了这套机制如何应用于解决目标导向对话中的事实查询难题，然后进一步验证了它在风格适应等场景中的有效性——可根据对话中人类参与者的社会属性等外部风格限制进行话语调整。

> Conversational AI systems that rely on Large Language Models, like Transformers, have difficulty interweaving external data (like facts) with the language they generate. Vanilla Transformer architectures are not designed for answering factual questions with high accuracy. This paper investigates a possible route for addressing this problem. We propose to extend the standard Transformer architecture with an additional memory bank holding extra information (such as facts drawn from a knowledge base), and an extra attention layer for addressing this memory. We add this augmented memory to a Generative Adversarial Network-inspired Transformer architecture. This setup allows for implementing arbitrary felicity conditions on the generated language of the Transformer. We first demonstrate how this machinery can be deployed for handling factual questions in goal-oriented dialogues. Secondly, we demonstrate that our approach can be useful for applications like {\it style adaptation} as well: the adaptation of utterances according to certain stylistic (external) constraints, like social properties of human interlocutors in dialogues.

[Arxiv](https://arxiv.org/abs/2402.19218)