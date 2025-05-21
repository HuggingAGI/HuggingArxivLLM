# # 面向功能保证的选择性代码生成

发布时间：2025年05月19日

`LLM应用` `软件开发`

> Selective Code Generation for Functional Guarantees

# 摘要

> 大型语言模型（LLMs）在复杂任务（如数学推理和软件开发）中展现出与人类相当的能力，而代码生成模型作为其重要分支，在解决这些问题中发挥着核心作用。然而，尽管LLMs的幻觉现象已引起AI社区的广泛关注，但代码生成模型的幻觉问题却鲜少被深入研究。一个关键挑战在于，与自然语言不同，代码的独特形式使其难以判断生成代码是否具备预期功能。尽管有限的单元测试被尝试用于解决这一问题，但其规模扩展成本极高。我们提出了一种基于动态代码分析工具自动生成单元测试的方法，巧妙利用了代码的可执行特性。通过从真实代码生成的单元测试来衡量生成代码的功能正确性，我们设计了一种\emph{选择性代码生成器}，它能够智能地避免对不确定生成做出回答，从而在非放弃回答的情况下通过控制假发现率来管理代码幻觉的发生。这一学习算法不仅提供了可控性保证，还显著提升了代码生成的可信度。最后，我们创新性地提出了\emph{FuzzEval}评估范式，将生成的单元测试同时用于评估与学习，从而实现精确的代码评估。实验结果表明，我们的选择性代码生成器在开放和封闭代码生成器中均表现出显著优势，充分展现了生成单元测试、代码幻觉可控性以及通过选择性代码生成器实现的高效选择策略的综合优势。

> Large language models (LLMs) show human-level performance and their specialized descendants, code generation models, play core roles in solving complex tasks, including mathematical reasoning and software development. On the downside, the hallucination of LLMs mainly hinders their applicability to systems requiring higher safety standards, thus drawing the attention of the AI community. However, the hallucination of code generation models is rarely considered. One critical bottleneck in considering code hallucination is the intricate property of code to identify whether generated code has the intended functionality due to its un-natural form, different to natural languages. Handful of unit tests have been considered to address this issue, but scaling-up its size is extremely expensive. We address this core bottleneck by automatically generating unit tests using dynamic code analysis tools, which leverages the \emph{executable nature} of code. Given generated unit tests from true code for measuring functional correctness of generated code, we propose to learn a \emph{selective code generator}, which abstains from answering for unsure generation, to control the rate of code hallucination among non-abstaining answers in terms of a false discovery rate. This learning algorithm provides a controllability guarantee, providing trustworthiness of code generation. Finally, we propose to use generated unit tests in evaluation as well as in learning for precise code evaluation, calling this evaluation paradigm \emph{FuzzEval}. We demonstrate the efficacy of our selective code generator over open and closed code generators, showing clear benefit of leveraging generated unit tests along with the controllability of code hallucination and reasonable selection efficiency via our selective code generator.

[Arxiv](https://arxiv.org/abs/2505.13553)