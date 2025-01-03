# PRISM: 大型语言模型偏见审计方法论

发布时间：2024年10月24日

`LLM理论

理由：这篇论文主要探讨了如何审计大型语言模型（LLMs）以揭示其偏见和偏好，并提出了一种新的审计方法PRISM。研究内容涉及LLMs的内部机制和行为模式，属于对LLMs的理论性研究和分析，因此应归类为LLM理论。` `人工智能`

> PRISM: A Methodology for Auditing Biases in Large Language Models

# 摘要

> # 摘要
审计大型语言模型（LLMs）以揭示其偏见和偏好，是构建负责任人工智能（AI）的新兴挑战。尽管已有多种方法试图揭示这些模型的偏好，但LLM训练者采取了反制措施，导致LLMs隐藏、混淆或直接拒绝透露其在某些议题上的立场。本文提出PRISM，一种灵活的、基于查询的审计方法，通过任务驱动的查询提示间接引出这些立场，而非直接询问偏好。为验证其有效性，我们在政治指南针测试中应用PRISM，评估了来自七个提供商的二十一个LLMs的政治倾向。结果显示，LLMs默认倾向于经济左倾和社会自由主义（与先前研究一致），同时揭示了这些模型愿意表达的立场范围——部分模型更为受限且不合作，而另一些则更为中立和客观。总之，PRISM能够更可靠地探测和审计LLMs，揭示其偏好、偏见和限制。

> Auditing Large Language Models (LLMs) to discover their biases and preferences is an emerging challenge in creating Responsible Artificial Intelligence (AI). While various methods have been proposed to elicit the preferences of such models, countermeasures have been taken by LLM trainers, such that LLMs hide, obfuscate or point blank refuse to disclosure their positions on certain subjects. This paper presents PRISM, a flexible, inquiry-based methodology for auditing LLMs - that seeks to illicit such positions indirectly through task-based inquiry prompting rather than direct inquiry of said preferences. To demonstrate the utility of the methodology, we applied PRISM on the Political Compass Test, where we assessed the political leanings of twenty-one LLMs from seven providers. We show LLMs, by default, espouse positions that are economically left and socially liberal (consistent with prior work). We also show the space of positions that these models are willing to espouse - where some models are more constrained and less compliant than others - while others are more neutral and objective. In sum, PRISM can more reliably probe and audit LLMs to understand their preferences, biases and constraints.

[Arxiv](https://arxiv.org/abs/2410.18906)