# 大型语言模型能否以零训练方式对非文本模态进行推理？——基于上下文表征学习的案例研究

发布时间：2025年09月22日

`LLM应用` `医疗健康`

> Can LLMs Reason Over Non-Text Modalities in a Training-Free Manner? A Case Study with In-Context Representation Learning

# 摘要

> 大型语言模型（LLMs）的卓越性能可通过测试时计算进一步提升，这种计算借助外部工具乃至其他深度学习模型实现。然而，现有将非文本模态表示融入LLMs的方法往往需要额外高昂的监督训练，限制了对新领域和模态的即时适配。本研究探索以无训练方式将非文本基础模型（FMs）的表示集成到文本LLMs中的可行性，并提出上下文表示学习（ICRL）作为概念验证——让LLMs能通过少样本学习自适应利用非文本模态表示。与传统上下文学习（结合文本-标签对）不同，ICRL用FM表示替代文本输入，使LLM无需微调即可执行多模态推理。我们在分子领域的一系列任务上评估ICRL，同时探究三个核心研究问题：（i）如何以无训练方式将FM表示映射到LLMs中；（ii）哪些因素影响ICRL性能；（iii）ICRL有效性的底层机制是什么。据我们所知，ICRL是首个将非文本模态表示集成到文本LLMs中的无训练框架，为适应性多模态泛化开辟了有前景的方向。

> The remarkable performance of Large Language Models (LLMs) can be enhanced with test-time computation, which relies on external tools and even other deep learning models. However, existing approaches for integrating non-text modality representations into LLMs typically require additional costly supervised training, restricting on-the-fly adaptation to new domains and modalities. In this work, we explore the feasibility of integrating representations from non-text foundational models (FMs) into text-based LLMs in a training-free manner. We propose In-Context Representation Learning (ICRL) as a proof-of-concept to allow LLMs to adaptively utilize non-text modality representations with few-shot learning. Unlike traditional in-context learning, which incorporates text-label pairs, ICRL replaces text inputs with FM representations, enabling the LLM to perform multi-modal inference without fine-tuning. We evaluate ICRL on a suite of tasks in the molecular domain, investigating three core research questions: (i) how to map FM representations into LLMs in a training-free manner, (ii) what factors influence ICRL performance, and (iii) what mechanisms underlie the effectiveness of ICRL. To the best of our knowledge, ICRL is the first training-free framework for integrating non-text modality representations into text-based LLMs, presenting a promising direction for adaptable, multi-modal generalization.

[Arxiv](https://arxiv.org/abs/2509.17552)