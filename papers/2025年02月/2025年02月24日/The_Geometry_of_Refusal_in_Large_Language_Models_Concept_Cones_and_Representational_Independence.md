# # 大型语言模型中的拒绝几何学：概念锥与表示独立性
大型语言模型中的拒绝几何学：概念锥与表示独立性

发布时间：2025年02月24日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的安全对齐机制，特别是对抗性输入如何绕过这些机制。研究深入分析了模型的拒绝机制，提出了新的表示工程方法，并揭示了模型内部的复杂结构和多维影响因素。这些内容属于对LLM内部机制和理论的深入研究，因此归类为LLM理论。` `人工智能安全` `模型治理`

> The Geometry of Refusal in Large Language Models: Concept Cones and Representational Independence

# 摘要

> 大型语言模型（LLMs）的安全对齐机制可以通过对抗性输入被绕过，但具体是如何突破安全屏障的仍不清楚。此前研究指出，模型激活空间中的单一拒绝方向决定了LLM是否会拒绝请求。本研究提出了一种基于梯度的表示工程新方法，用于识别拒绝方向。与此前研究不同，我们发现存在多个独立方向，甚至多维概念锥，共同影响拒绝行为。我们进一步证明，正交性并不必然意味着独立性，尤其是在干预情况下。为此，我们提出了一个考虑线性和非线性效应的表示独立性概念。通过这一框架，我们识别出机制上独立的拒绝方向。研究结果表明，LLMs的拒绝机制由复杂的空间结构控制，并存在功能上独立的方向，证实了多种不同机制共同驱动拒绝行为。我们的基于梯度的方法揭示了这些机制，为未来深入理解LLMs奠定了基础。

> The safety alignment of large language models (LLMs) can be circumvented through adversarially crafted inputs, yet the mechanisms by which these attacks bypass safety barriers remain poorly understood. Prior work suggests that a single refusal direction in the model's activation space determines whether an LLM refuses a request. In this study, we propose a novel gradient-based approach to representation engineering and use it to identify refusal directions. Contrary to prior work, we uncover multiple independent directions and even multi-dimensional concept cones that mediate refusal. Moreover, we show that orthogonality alone does not imply independence under intervention, motivating the notion of representational independence that accounts for both linear and non-linear effects. Using this framework, we identify mechanistically independent refusal directions. We show that refusal mechanisms in LLMs are governed by complex spatial structures and identify functionally independent directions, confirming that multiple distinct mechanisms drive refusal behavior. Our gradient-based approach uncovers these mechanisms and can further serve as a foundation for future work on understanding LLMs.

[Arxiv](https://arxiv.org/abs/2502.17420)