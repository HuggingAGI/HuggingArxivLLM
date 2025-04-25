# 基于大语言模型的符号执行，实现结构化测试输入的高效生成

发布时间：2025年04月24日

`LLM应用

这篇论文探讨了大型语言模型（LLM）在符号执行引擎中的应用，旨在改进测试输入的生成。论文提出了Cottontail引擎，利用LLM进行路径约束选择和约束求解，生成有效的测试输入，从而提升测试覆盖率和发现漏洞的能力。这属于将LLM技术应用于特定领域的实际问题，因此归类为LLM应用。` `软件工程` `测试自动化`

> Large Language Model-Driven Concolic Execution for Highly Structured Test Input Generation

# 摘要

> 如何通过符号执行生成高度结构化的测试输入，以便系统性地测试解析程序？现有的符号执行引擎在以下方面受到显著限制：无法感知输入结构的路径约束选择，导致测试努力的浪费或遗漏覆盖范围；约束求解能力有限，生成许多语法无效的测试输入；依赖手动获取高度结构化的种子输入，导致测试不连续。

本文提出了一种全新的基于大型语言模型（LLM）的符号执行引擎——Cottontail，以克服上述限制。首先，我们构建了一种更完整的程序路径表示，名为表达式结构覆盖树（ESCT），用于选择感知结构的路径约束。随后，设计了一种基于“Solve-Complete”范式的LLM驱动约束求解器，以智能方式求解路径约束，从而生成不仅满足约束条件，而且符合输入语法的测试输入。最后，采用基于历史的种子获取方法，在测试开始前或测试饱和后获取新的高度结构化的测试输入。

我们在SymCC的基础上实现了Cottontail，并对四个不同格式（XML、SQL、JavaScript和JSON）的八个经过广泛测试的开源库进行了评估。实验结果令人鼓舞：与现有最先进的方法（SymCC和Marco）相比，Cottontail在行覆盖方面分别高出14.15%和14.31%。此外，Cottontail发现了6个之前未知的漏洞（六个新的CVE已分配）。我们已将这些问题报告给开发者，其中4个已修复。


> How can we perform concolic execution to generate highly structured test inputs for systematically testing parsing programs? Existing concolic execution engines are significantly restricted by (1) input structure-agnostic path constraint selection, leading to the waste of testing effort or missing coverage; (2) limited constraint-solving capability, yielding many syntactically invalid test inputs; (3) reliance on manual acquisition of highly structured seed inputs, resulting in non-continuous testing.
  This paper proposes Cottontail, a new Large Language Model (LLM)-driven concolic execution engine, to mitigate the above limitations. A more complete program path representation, named Expressive Structural Coverage Tree (ESCT), is first constructed to select structure-aware path constraints. Later, an LLM-driven constraint solver based on a Solve-Complete paradigm is designed to solve the path constraints smartly to get test inputs that are not only satisfiable to the constraints but also valid to the input syntax. Finally, a history-guided seed acquisition is employed to obtain new highly structured test inputs either before testing starts or after testing is saturated.
  We implemented Cottontail on top of SymCC and evaluated eight extensively tested open-source libraries across four different formats (XML, SQL, JavaScript, and JSON). The experimental result is promising: it shows that Cottontail outperforms state-of-the-art approaches (SymCC and Marco) by 14.15% and 14.31% in terms of line coverage. Besides, Cottontail found 6 previously unknown vulnerabilities (six new CVEs have been assigned). We have reported these issues to developers, and 4 out of them have been fixed so far.

[Arxiv](https://arxiv.org/abs/2504.17542)