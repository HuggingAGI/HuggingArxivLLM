# 为功能性保证选择性生成代码

发布时间：2025年05月19日

`LLM应用` `软件开发` `软件工程`

> Selective Code Generation for Functional Guarantees

# 摘要

> 大型语言模型（LLMs）在复杂任务中表现出与人类相当的能力，其衍生的代码生成模型在数学推理和软件开发等领域发挥着重要作用。然而，LLMs的幻觉现象限制了其在高安全标准系统中的应用，但代码生成模型的幻觉问题却未得到足够关注。一个关键挑战在于代码的复杂性使其难以验证生成代码的功能正确性，这与自然语言不同。尽管单元测试曾被用于解决此问题，但其扩展成本高昂。我们提出通过动态代码分析工具自动生成单元测试，利用代码的\emph{可执行性}特性来解决这一瓶颈。基于真实代码生成的单元测试，我们设计了一种\emph{选择性代码生成器}，在生成不确定时主动弃用，从而以错误发现率为标准控制代码幻觉率。该算法确保了代码生成的可控性和可信度。最后，我们提出将生成的单元测试用于评估和训练，形成名为\emph{FuzzEval}的评估范式。实验表明，我们的选择性代码生成器在开放和封闭生成器中均表现出色，证明了生成单元测试与代码幻觉可控性结合的有效性。

> Large language models (LLMs) show human-level performance and their specialized descendants, code generation models, play core roles in solving complex tasks, including mathematical reasoning and software development. On the downside, the hallucination of LLMs mainly hinders their applicability to systems requiring higher safety standards, thus drawing the attention of the AI community. However, the hallucination of code generation models is rarely considered. One critical bottleneck in considering code hallucination is the intricate property of code to identify whether generated code has the intended functionality due to its un-natural form, different to natural languages. Handful of unit tests have been considered to address this issue, but scaling-up its size is extremely expensive. We address this core bottleneck by automatically generating unit tests using dynamic code analysis tools, which leverages the \emph{executable nature} of code. Given generated unit tests from true code for measuring functional correctness of generated code, we propose to learn a \emph{selective code generator}, which abstains from answering for unsure generation, to control the rate of code hallucination among non-abstaining answers in terms of a false discovery rate. This learning algorithm provides a controllability guarantee, providing trustworthiness of code generation. Finally, we propose to use generated unit tests in evaluation as well as in learning for precise code evaluation, calling this evaluation paradigm \emph{FuzzEval}. We demonstrate the efficacy of our selective code generator over open and closed code generators, showing clear benefit of leveraging generated unit tests along with the controllability of code hallucination and reasonable selection efficiency via our selective code generator.

[Arxiv](https://arxiv.org/abs/2505.13553)