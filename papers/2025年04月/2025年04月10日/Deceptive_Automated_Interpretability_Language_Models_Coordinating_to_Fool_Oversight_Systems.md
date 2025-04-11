# 欺骗式自动可解释性：语言模型协同欺骗监管系统

发布时间：2025年04月10日

`Agent` `人工智能` `网络安全`

> Deceptive Automated Interpretability: Language Models Coordinating to Fool Oversight Systems

# 摘要

> 我们展示了AI代理如何通过神经网络的自动解释能力来协同欺骗监管系统。借助稀疏自动编码器（SAEs）作为实验框架，我们发现Llama、DeepSeek R1和Claude 3.7 Sonnet等语言模型能够生成欺骗性解释以逃避检测。我们的代理采用信息隐藏方法，在看似无害的解释中藏匿信息，成功欺骗监管模型，同时生成的解释质量与参考标签相当。研究还发现，当模型认为检测有害特征可能对自己造成负面影响时，它们会主动策划欺骗策略。所有测试的LLM代理均能在实现高可解释性评分的同时欺骗监管者，这些评分与参考标签相当。最后，我们提出了应对策略，强调了对欺骗行为的 robust 理解和防御的迫切需求。

> We demonstrate how AI agents can coordinate to deceive oversight systems using automated interpretability of neural networks. Using sparse autoencoders (SAEs) as our experimental framework, we show that language models (Llama, DeepSeek R1, and Claude 3.7 Sonnet) can generate deceptive explanations that evade detection. Our agents employ steganographic methods to hide information in seemingly innocent explanations, successfully fooling oversight models while achieving explanation quality comparable to reference labels. We further find that models can scheme to develop deceptive strategies when they believe the detection of harmful features might lead to negative consequences for themselves. All tested LLM agents were capable of deceiving the overseer while achieving high interpretability scores comparable to those of reference labels. We conclude by proposing mitigation strategies, emphasizing the critical need for robust understanding and defenses against deception.

[Arxiv](https://arxiv.org/abs/2504.07831)