# 智能合约验证的便捷之道：利用驯服的大型语言模型合成形式模型

发布时间：2025年01月22日

`LLM应用

理由：该论文摘要描述了如何利用大型语言模型（LLM）来自动生成形式化模型，以加速区块链软件的正确性验证。这属于LLM在实际应用中的使用，特别是用于软件验证和形式化模型的生成。因此，将其分类为“LLM应用”是合适的。` `区块链` `软件验证`

> Accessible Smart Contracts Verification: Synthesizing Formal Models with Tamed LLMs

# 摘要

> 区块链系统所谓的“无需信任”，实际上是将所有信任都寄托在软件上。因此，确保区块链软件的正确性至关重要——漏洞可能导致数百万的损失甚至企业倒闭。形式化方法是验证软件正确性的强有力手段，但其应用往往耗时且需要专业知识。我们的研究通过自动化生成形式化模型——软件系统的数学抽象——来克服这一难题。我们采用三步法进行模型合成：首先将代码转换为模型框架；接着利用大型语言模型（LLM）填补细节；最后在语法和语义层面迭代修复模型。这一方法大幅缩短了形式化模型的创建时间，并提升了依赖这些模型的软件验证方法的普及性。我们的研究旨在加速形式化模型在智能合约正确性审计中的应用。

> When blockchain systems are said to be trustless, what this really means is that all the trust is put into software. Thus, there are strong incentives to ensure blockchain software is correct -- vulnerabilities here cost millions and break businesses. One of the most powerful ways of establishing software correctness is by using formal methods. Approaches based on formal methods, however, induce a significant overhead in terms of time and expertise required to successfully employ them. Our work addresses this critical disadvantage by automating the creation of a formal model -- a mathematical abstraction of the software system -- which is often a core task when employing formal methods. We perform model synthesis in three phases: we first transpile the code into model stubs; then we "fill in the blanks" using a large language model (LLM); finally, we iteratively repair the generated model, on both syntactical and semantical level. In this way, we significantly reduce the amount of time necessary to create formal models and increase accessibility of valuable software verification methods that rely on them. The practical context of our work was reducing the time-to-value of using formal models for correctness audits of smart contracts.

[Arxiv](https://arxiv.org/abs/2501.12972)