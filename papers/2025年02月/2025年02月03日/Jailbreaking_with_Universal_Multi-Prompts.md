# 通用多提示越狱

发布时间：2025年02月03日

`LLM应用

理由：这篇论文主要讨论了一种基于提示的方法JUMP，用于实现大型语言模型（LLMs）的越狱，并将其调整为防御方法DUMP。这涉及到LLMs在实际应用中的安全性和防御机制，属于LLM应用的范畴。` `人工智能` `网络安全`

> Jailbreaking with Universal Multi-Prompts

# 摘要

> 近年来，大型语言模型（LLMs）发展迅猛，不仅革新了各类应用，还大幅提升了便利性和生产力。然而，伴随着其强大能力而来的，还有伦理问题和新型攻击（如越狱）。尽管大多数提示技术专注于优化单个案例的对抗性输入，但在处理大规模数据集时，计算成本较高。相比之下，关于训练一个能够迁移到未见任务的通用攻击者的研究较少。本文提出了一种基于提示的方法JUMP，旨在通过通用多提示实现LLMs的越狱。我们还将其调整为防御方法DUMP。实验表明，我们的通用多提示优化方法优于现有技术。

> Large language models (LLMs) have seen rapid development in recent years, revolutionizing various applications and significantly enhancing convenience and productivity. However, alongside their impressive capabilities, ethical concerns and new types of attacks, such as jailbreaking, have emerged. While most prompting techniques focus on optimizing adversarial inputs for individual cases, resulting in higher computational costs when dealing with large datasets. Less research has addressed the more general setting of training a universal attacker that can transfer to unseen tasks. In this paper, we introduce JUMP, a prompt-based method designed to jailbreak LLMs using universal multi-prompts. We also adapt our approach for defense, which we term DUMP. Experimental results demonstrate that our method for optimizing universal multi-prompts outperforms existing techniques.

[Arxiv](https://arxiv.org/abs/2502.01154)