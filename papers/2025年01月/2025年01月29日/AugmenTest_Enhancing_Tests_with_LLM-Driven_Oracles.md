# AugmenTest: 利用LLM驱动的预言机提升测试效果

发布时间：2025年01月29日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）从软件文档中推断测试预言，并提出了AugmenTest的四种变体。这属于将LLMs应用于软件测试生成的具体场景，因此应归类为LLM应用。` `软件测试` `自动化测试`

> AugmenTest: Enhancing Tests with LLM-Driven Oracles

# 摘要

> # 摘要
自动化测试生成在确保软件可靠性和健壮性的同时，还能大幅减少工作量。尽管测试生成研究已取得显著进展，但生成有效的测试预言仍是一个难题。为此，我们提出了AugmenTest，它利用大型语言模型（LLMs）从软件文档中推断测试预言，而无需查看代码。AugmenTest有四种变体：简单提示、扩展提示、通用提示的RAG和简单提示的RAG，每种变体为LLMs提供不同级别的上下文信息。我们选取了142个Java类，生成多个变异体并从中生成测试，仅保留在变异体上通过但在原始类上失败的测试，以确保捕获错误。最终，我们得到了203个独特测试，用于评估AugmenTest。结果显示，在最保守的情况下，扩展提示的表现优于简单提示，生成正确断言的成功率达30\%，而最先进的TOGA方法仅为8.2\%。出乎意料的是，基于RAG的方法并未带来提升，其成功率仅为18.2\%。

> Automated test generation is crucial for ensuring the reliability and robustness of software applications while at the same time reducing the effort needed. While significant progress has been made in test generation research, generating valid test oracles still remains an open problem. To address this challenge, we present AugmenTest, an approach leveraging Large Language Models (LLMs) to infer correct test oracles based on available documentation of the software under test. Unlike most existing methods that rely on code, AugmenTest utilizes the semantic capabilities of LLMs to infer the intended behavior of a method from documentation and developer comments, without looking at the code. AugmenTest includes four variants: Simple Prompt, Extended Prompt, RAG with a generic prompt (without the context of class or method under test), and RAG with Simple Prompt, each offering different levels of contextual information to the LLMs. To evaluate our work, we selected 142 Java classes and generated multiple mutants for each. We then generated tests from these mutants, focusing only on tests that passed on the mutant but failed on the original class, to ensure that the tests effectively captured bugs. This resulted in 203 unique tests with distinct bugs, which were then used to evaluate AugmenTest. Results show that in the most conservative scenario, AugmenTest's Extended Prompt consistently outperformed the Simple Prompt, achieving a success rate of 30\% for generating correct assertions. In comparison, the state-of-the-art TOGA approach achieved 8.2\%. Contrary to our expectations, the RAG-based approaches did not lead to improvements, with performance of 18.2\% success rate for the most conservative scenario.

[Arxiv](https://arxiv.org/abs/2501.17461)