# 基于大型语言模型的代理实现C语言到Rust语言的代码转换

发布时间：2025年05月20日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）进行C到Rust的代码翻译，属于LLMs在具体任务中的应用。` `软件开发` `编程语言`

> Large Language Model-Powered Agent for C to Rust Code Translation

# 摘要

> C语言在系统级软件开发中扮演着基础性角色，但其手动内存管理机制常常引发内存安全问题。为此，一种现代系统编程语言Rust应运而生，以其内存安全特性成为C语言的理想替代方案。借助LLMs生成能力的突飞猛进，针对海量遗留C代码的自动化翻译工作正在吸引越来越多的关注。尽管已取得一定成果，现有基于LLMs的方法仍存在局限：它们仅将LLMs的作用局限于静态的提示-响应模式，未能充分发挥其能动的问题解决能力。将LLMs的能动性引入C到Rust翻译面临独特挑战，这一任务与传统的LLMs代理应用场景（如数学或常识问答）存在显著差异。首先，C到Rust的并行数据集稀缺，限制了上下文学习中合适代码翻译示例的获取。其次，与数学或常识问答不同，C到Rust所需的中间步骤缺乏明确界定。第三，如何组织和级联这些中间步骤以构建正确的翻译轨迹仍是一个待解难题。针对这些挑战，我们提出了一种创新的中间步骤——基于虚拟模糊测试的等价测试（VFT），以及一个能动规划框架——由LLMs驱动的C到Rust代码翻译代理（LAC2R）。VFT能够引导LLMs识别导致原始C函数与其Rust对应函数行为差异的输入参数，并生成具有诊断价值的信息以优化不安全的Rust代码。LAC2R则通过MCTS系统性地组织LLMs诱导的中间步骤，确保翻译的正确性。实验结果表明，LAC2R在大规模、真实世界的基准测试中展现出高效的C到Rust翻译能力。

> The C programming language has been foundational in building system-level software. However, its manual memory management model frequently leads to memory safety issues. In response, a modern system programming language, Rust, has emerged as a memory-safe alternative. Moreover, automating the C-to-Rust translation empowered by the rapid advancements of the generative capabilities of LLMs is gaining growing interest for large volumes of legacy C code. Despite some success, existing LLM-based approaches have constrained the role of LLMs to static prompt-response behavior and have not explored their agentic problem-solving capability. Applying the LLM agentic capability for the C-to-Rust translation introduces distinct challenges, as this task differs from the traditional LLM agent applications, such as math or commonsense QA domains. First, the scarcity of parallel C-to-Rust datasets hinders the retrieval of suitable code translation exemplars for in-context learning. Second, unlike math or commonsense QA, the intermediate steps required for C-to-Rust are not well-defined. Third, it remains unclear how to organize and cascade these intermediate steps to construct a correct translation trajectory. To address these challenges in the C-to-Rust translation, we propose a novel intermediate step, the Virtual Fuzzing-based equivalence Test (VFT), and an agentic planning framework, the LLM-powered Agent for C-to-Rust code translation (LAC2R). The VFT guides LLMs to identify input arguments that induce divergent behaviors between an original C function and its Rust counterpart and to generate informative diagnoses to refine the unsafe Rust code. LAC2R uses the MCTS to systematically organize the LLM-induced intermediate steps for correct translation. We experimentally demonstrated that LAC2R effectively conducts C-to-Rust translation on large-scale, real-world benchmarks.

[Arxiv](https://arxiv.org/abs/2505.15858)