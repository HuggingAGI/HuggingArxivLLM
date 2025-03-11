# 超越代码生成：借助LLM的程序设计空间深入探索

发布时间：2025年03月10日

`LLM应用

论文摘要讨论了显式大型语言模型（LLM）在计算机程序迭代设计中的应用，特别是在支持程序设计的IDE中使用LLM生成和展示问题框架及替代解决方案。研究关注如何利用LLM来增强设计过程，揭示了在程序设计IDE中使用LLM的核心挑战，如信息过载和注意力管理。这些内容属于LLM的实际应用，因此归类为LLM应用。` `软件工程` `程序设计`

> Beyond Code Generation: LLM-supported Exploration of the Program Design Space

# 摘要

> 本研究聚焦于显式大型语言模型（LLM）支持在计算机程序迭代设计中的应用。程序设计与其他设计活动一样，本质上是一个在多种问题表述及其解决方案间进行迭代探索的过程。尽管 LLM 可能是助力这一探索的强效工具，但默认情况下，代码生成型 LLM 仅提供特定的点式解决方案，这会掩盖其他潜在的更优选择。为此，我们开发了一款支持程序设计的 IDE，它能够生成并展示新的问题框架及替代解决方案，追踪设计决策，并识别程序员或 LLM 所做的隐性决策。通过用户研究发现，借助我们的 IDE，用户能够更高效地结合并行化设计阶段，探索更广阔的设计空间。然而，用户也面临 LLM 引发的代码变化及信息过载的挑战。这些发现揭示了未来支持程序设计的 IDE 的核心挑战：在向 LLM 型代理提供更高层次指令时，如何审慎管理注意力，并决定何时向程序设计师呈现何种信息。

> In this work, we explore explicit Large Language Model (LLM)-powered support for the iterative design of computer programs. Program design, like other design activity, is characterized by navigating a space of alternative problem formulations and associated solutions in an iterative fashion. LLMs are potentially powerful tools in helping this exploration; however, by default, code-generation LLMs deliver code that represents a particular point solution. This obscures the larger space of possible alternatives, many of which might be preferable to the LLM's default interpretation and its generated code. We contribute an IDE that supports program design through generating and showing new ways to frame problems alongside alternative solutions, tracking design decisions, and identifying implicit decisions made by either the programmer or the LLM. In a user study, we find that with our IDE, users combine and parallelize design phases to explore a broader design space -- but also struggle to keep up with LLM-originated changes to code and other information overload. These findings suggest a core challenge for future IDEs that support program design through higher-level instructions given to LLM-based agents: carefully managing attention and deciding what information agents should surface to program designers and when.

[Arxiv](https://arxiv.org/abs/2503.06911)