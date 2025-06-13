# ELFuzz：利用大型语言模型驱动的合成技术，在模糊器空间中实现高效输入生成

发布时间：2025年06月11日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLM）在模糊测试中的应用，提出了一种名为ELFuzz的方法，通过LLM自动生成测试用例以提高测试效率和效果。因此，它属于LLM应用类别。` `软件工程` `网络安全`

> ELFuzz: Efficient Input Generation via LLM-driven Synthesis Over Fuzzer Space

# 摘要

> 基于生成的模糊测试通过输入语法和语义约束生成测试用例，用于测试系统和软件。然而，构建这些规范需要大量人工 effort。本文提出ELFuzz（通过大型语言模型进行模糊测试的进化），它利用基于LLM的合成，在模糊测试器空间中自动为待测系统（SUT）生成定制的模糊测试器。总体而言，ELFuzz从最小的种子模糊测试器开始，通过完全自动化的基于LLM的进化推进合成过程，同时以覆盖率为指导。与之前的方法相比，ELFuzz可以1）无缝扩展到真实规模的系统——在我们的评估中达到1,791,104行代码——以及2）生成高效的模糊测试器，以人类可理解的方式捕获有趣的语法规则和语义约束。我们的评估将ELFuzz与领域专家手动编写的规范和最新方法合成的规范进行了比较。结果显示，ELFuzz的覆盖率提高了434.8%，触发的人工注入的漏洞数量增加了174.0%。我们还使用ELFuzz对cvc5的最新版本进行了为期14天的真实世界模糊测试活动，并令人鼓舞的是，它发现了五个零日漏洞（其中三个是可以利用的）。此外，我们进行了一项消融研究，结果显示，ELFuzz的关键组件——模糊测试器空间模型——对ELFuzz的有效性贡献最大（高达62.5%）。对ELFuzz合成的模糊测试器的进一步分析证实，它们以人类可理解的方式捕获了有趣的语法规则和语义约束。结果表明，ELFuzz在模糊测试中具有巨大的潜力，能够实现更自动化、高效和可扩展的输入生成。

> Generation-based fuzzing produces appropriate testing cases according to specifications of input grammars and semantic constraints to test systems and software. However, these specifications require significant manual efforts to construct. This paper proposes a new approach, ELFuzz (Evolution Through Large Language Models for Fuzzing), that automatically synthesizes generation-based fuzzers tailored to a system under test (SUT) via LLM-driven synthesis over fuzzer space. At a high level, it starts with minimal seed fuzzers and propels the synthesis by fully automated LLM-driven evolution with coverage guidance. Compared to previous approaches, ELFuzz can 1) seamlessly scale to SUTs of real-world sizes -- up to 1,791,104 lines of code in our evaluation -- and 2) synthesize efficient fuzzers that catch interesting grammatical structures and semantic constraints in a human-understandable way. Our evaluation compared ELFuzz with specifications manually written by domain experts and synthesized by state-of-the-art approaches. It shows that ELFuzz achieves up to 434.8% more coverage and triggers up to 174.0% more artificially injected bugs. We also used ELFuzz to conduct a real-world fuzzing campaign on the newest version of cvc5 for 14 days, and encouragingly, it found five 0-day bugs (three are exploitable). Moreover, we conducted an ablation study, which shows that the fuzzer space model, the key component of ELFuzz, contributes the most (up to 62.5%) to the effectiveness of ELFuzz. Further analysis of the fuzzers synthesized by ELFuzz confirms that they catch interesting grammatical structures and semantic constraints in a human-understandable way. The results present the promising potential of ELFuzz for more automated, efficient, and extensible input generation for fuzzing.

[Arxiv](https://arxiv.org/abs/2506.10323)