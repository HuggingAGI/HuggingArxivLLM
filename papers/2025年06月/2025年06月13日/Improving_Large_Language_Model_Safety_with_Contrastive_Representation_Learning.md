# 利用对比学习提升大型语言模型的安全性

发布时间：2025年06月13日

`LLM理论` `人工智能`

> Improving Large Language Model Safety with Contrastive Representation Learning

# 摘要

> 大型语言模型（LLMs）作为具有深远社会影响力的强大工具，尽管能够生成多样化且不受控制的输入响应，但其容易受到对抗攻击的威胁。针对现有防御方法在不同攻击类型之间难以泛化的痛点，近期在表示工程领域的研究为我们提供了新的思路。本研究提出了一种基于对比表示学习（CRL）的防御框架，将模型防御问题转化为对比学习问题。我们的方法通过结合三元组损失和对抗性难负挖掘对模型进行微调，有效实现了良性与有害表示之间的分离。实验结果表明，与现有基于表示工程的防御方法相比，本方法在多个模型上均表现出更优的防御效果，显著增强了模型对输入级和嵌入空间攻击的鲁棒性，同时保持了标准性能的稳定。我们的代码可在 https://github.com/samuelsimko/crl-llm-defense 获取。

> Large Language Models (LLMs) are powerful tools with profound societal impacts, yet their ability to generate responses to diverse and uncontrolled inputs leaves them vulnerable to adversarial attacks. While existing defenses often struggle to generalize across varying attack types, recent advancements in representation engineering offer promising alternatives. In this work, we propose a defense framework that formulates model defense as a contrastive representation learning (CRL) problem. Our method finetunes a model using a triplet-based loss combined with adversarial hard negative mining to encourage separation between benign and harmful representations. Our experimental results across multiple models demonstrate that our approach outperforms prior representation engineering-based defenses, improving robustness against both input-level and embedding-space attacks without compromising standard performance. Our code is available at https://github.com/samuelsimko/crl-llm-defense

[Arxiv](https://arxiv.org/abs/2506.11938)