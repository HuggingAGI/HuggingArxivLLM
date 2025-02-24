# # 大型语言模型编写Alloy公式的有效性研究

发布时间：2025年02月21日

`LLM应用` `软件工程`

> On the Effectiveness of Large Language Models in Writing Alloy Formulas

# 摘要

> 声明式规范对开发安全可靠的软件系统至关重要，但编写规范仍然充满挑战。本文通过受控实验研究了大型语言模型（LLMs）在Alloy语言中编写声明式公式的能力。实验分为三个层面：利用LLMs根据自然语言描述生成完整Alloy公式；根据给定公式生成等价替代方案；以及通过合成运算符和表达式完成公式草稿。实验使用了11个典型规范，并测试了ChatGPT和DeepSeek两个模型。结果表明，LLMs在生成公式、提供多种解决方案以及根据自然语言描述完善草稿方面表现优异。这一研究展示了LLMs在规范编写中的巨大潜力，为提升软件开发质量提供了新思路。

> Declarative specifications have a vital role to play in developing safe and dependable software systems. Writing specifications correctly, however, remains particularly challenging. This paper presents a controlled experiment on using large language models (LLMs) to write declarative formulas in the well-known language Alloy. Our use of LLMs is three-fold. One, we employ LLMs to write complete Alloy formulas from given natural language descriptions (in English). Two, we employ LLMs to create alternative but equivalent formulas in Alloy with respect to given Alloy formulas. Three, we employ LLMs to complete sketches of Alloy formulas and populate the holes in the sketches by synthesizing Alloy expressions and operators so that the completed formulas accurately represent the desired properties (that are given in natural language). We conduct the experimental evaluation using 11 well-studied subject specifications and employ two popular LLMs, namely ChatGPT and DeepSeek. The experimental results show that the LLMs generally perform well in synthesizing complete Alloy formulas from input properties given in natural language or in Alloy, and are able to enumerate multiple unique solutions. Moreover, the LLMs are also successful at completing given sketches of Alloy formulas with respect to natural language descriptions of desired properties (without requiring test cases). We believe LLMs offer a very exciting advance in our ability to write specifications, and can help make specifications take a pivotal role in software development and enhance our ability to build robust software.

[Arxiv](https://arxiv.org/abs/2502.15441)