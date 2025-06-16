# 迭代式AI代码生成中的安全性下降现象 -- 系统性分析悖论现象
在迭代式AI代码生成过程中，安全性下降的现象 -- 对这一悖论的系统性分析

发布时间：2025年05月19日

`LLM应用` `软件开发` `信息安全`

> Security Degradation in Iterative AI Code Generation -- A Systematic Analysis of the Paradox

# 摘要

> 大型语言模型（LLMs）在代码生成领域的广泛应用彻底改变了软件开发，然而，人们对安全漏洞在迭代LLM反馈中的演变却关注甚少。本研究通过一项包含400个代码样本、跨越40轮"改进"的受控实验，分析了AI生成代码中的安全性下降问题，采用了四种不同的提示策略。研究发现，仅经过五次迭代，关键漏洞的数量就增加了37.6%，并且不同提示方法下出现了明显的漏洞模式。这一发现挑战了迭代LLM优化能提升代码安全性的假设，并突显了人类专业知识在循环中的关键作用。我们为开发者提出了实用的指导方针，强调在LLM迭代之间进行 robust 人工验证的必要性，以防止在看似有益的代码"改进"过程中意外引入新的安全问题。

> The rapid adoption of Large Language Models(LLMs) for code generation has transformed software development, yet little attention has been given to how security vulnerabilities evolve through iterative LLM feedback. This paper analyzes security degradation in AI-generated code through a controlled experiment with 400 code samples across 40 rounds of "improvements" using four distinct prompting strategies. Our findings show a 37.6% increase in critical vulnerabilities after just five iterations, with distinct vulnerability patterns emerging across different prompting approaches. This evidence challenges the assumption that iterative LLM refinement improves code security and highlights the essential role of human expertise in the loop. We propose practical guidelines for developers to mitigate these risks, emphasizing the need for robust human validation between LLM iterations to prevent the paradoxical introduction of new security issues during supposedly beneficial code "improvements".

[Arxiv](https://arxiv.org/abs/2506.11022)