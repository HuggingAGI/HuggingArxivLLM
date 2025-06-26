# 基于LLMs的路径感知符号执行：生成与理解测试

发布时间：2025年06月23日

`LLM应用` `软件工程` `测试生成`

> Generating and Understanding Tests via Path-Aware Symbolic Execution with LLMs

# 摘要

> 符号执行作为一种广受欢迎的测试生成技术，通过约束求解系统地探索程序路径。然而，其在建模目标代码（包括库函数）和底层约束求解器的能力方面存在根本性限制。因此，许多涉及复杂特性的路径仍未被充分分析或建模。尽管大型语言模型（LLMs）在生成多样且有效的测试输入方面展现出潜力，但它们缺乏系统性枚举程序路径的机制，常常无法覆盖微妙的边界情况。我们发现，直接将完整程序提示 LLM 会导致遗漏有趣的路径覆盖。

本文中，我们介绍了 PALM，一个结合符号路径枚举与 LLM 辅助测试生成的测试生成系统。PALM 通过 AST 级别分析静态枚举可能的路径，并将每个路径转换为嵌入断言的可执行变体，以指定目标路径。这避免了将路径约束转换为 SMT 公式，而是构建 LLM 可以解释的程序变体。重要的是，PALM 是首个提供交互式前端的系统，可以可视化路径覆盖和生成的测试，根据测试所锻炼的具体路径组装测试。

一项包含 12 名参与者的用户研究表明，通过验证和可视化路径配置文件，PALM 的前端帮助用户更好地理解路径覆盖，并识别哪些路径实际上被 PALM 生成的测试所锻炼。

> Symbolic execution is a widely used technique for test generation, offering systematic exploration of program paths through constraint solving. However, it is fundamentally constrained by the capability to model the target code including library functions in terms of symbolic constraint and the capability of underlying constraint solvers. As a result, many paths involving complex features remain unanalyzed or insufficiently modeled. Recent advances in large language models (LLMs) have shown promise in generating diverse and valid test inputs. Yet, LLMs lack mechanisms for systematically enumerating program paths and often fail to cover subtle corner cases. We observe that directly prompting an LLM with the full program leads to missed coverage of interesting paths. In this paper, we present PALM, a test generation system that combines symbolic path enumeration with LLM-assisted test generation. PALM statically enumerates possible paths through AST-level analysis and transforms each into an executable variant with embedded assertions that specify the target path. This avoids the need to translate path constraints into SMT formulae, by instead constructing program variants that LLM can interpret. Importantly, PALM is the first to provide an interactive frontend that visualizes path coverage alongside generated tests, assembling tests based on the specific paths they exercise. A user study with 12 participants demonstrates that PALM's frontend helps users better understand path coverage and identify which paths are actually exercised by PALM-generated tests, through verification and visualization of their path profiles.

[Arxiv](https://arxiv.org/abs/2506.19287)