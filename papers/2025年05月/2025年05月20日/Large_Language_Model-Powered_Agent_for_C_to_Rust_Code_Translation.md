# # 大型语言模型驱动的C到Rust代码转换工具

发布时间：2025年05月20日

`LLM应用` `编程语言` `系统软件`

> Large Language Model-Powered Agent for C to Rust Code Translation

# 摘要

> C语言在系统级软件开发中扮演了基础角色。然而，其手动内存管理机制常引发内存安全问题。为应对这一挑战，现代系统编程语言Rust应运而生，提供了一种内存安全的解决方案。此外，借助大型语言模型（LLMs）生成能力的快速进步，针对大量遗留C代码的自动化C到Rust翻译吸引了越来越多的关注。尽管已取得一定成功，现有基于LLM的方法仍局限于静态提示-响应行为，未能充分发挥其主动问题解决能力。将LLM的主动能力应用于C到Rust翻译面临独特挑战，因为这与传统LLM代理应用（如数学或常识问答）大不相同。首先，C到Rust平行数据集的匮乏限制了上下文学习中合适代码示例的获取。其次，与数学或常识问答不同，C到Rust翻译所需的中间步骤尚未明确。第三，如何组织和级联这些中间步骤以构建正确的翻译路径仍不明晰。为解决这些挑战，我们提出了一种创新的中间步骤——虚拟模糊测试（VFT），以及一个基于LLM的主动规划框架——C到Rust代码翻译代理（LAC2R）。VFT引导LLMs识别导致C函数与其Rust版本行为差异的输入参数，并生成诊断信息以优化不安全的Rust代码。LAC2R通过蒙特卡洛树搜索（MCTS）系统地组织LLM生成的中间步骤，确保翻译的正确性。实验结果表明，LAC2R在大规模、真实世界基准测试中成功实现了C到Rust的高效翻译。

> The C programming language has been foundational in building system-level software. However, its manual memory management model frequently leads to memory safety issues. In response, a modern system programming language, Rust, has emerged as a memory-safe alternative. Moreover, automating the C-to-Rust translation empowered by the rapid advancements of the generative capabilities of LLMs is gaining growing interest for large volumes of legacy C code. Despite some success, existing LLM-based approaches have constrained the role of LLMs to static prompt-response behavior and have not explored their agentic problem-solving capability. Applying the LLM agentic capability for the C-to-Rust translation introduces distinct challenges, as this task differs from the traditional LLM agent applications, such as math or commonsense QA domains. First, the scarcity of parallel C-to-Rust datasets hinders the retrieval of suitable code translation exemplars for in-context learning. Second, unlike math or commonsense QA, the intermediate steps required for C-to-Rust are not well-defined. Third, it remains unclear how to organize and cascade these intermediate steps to construct a correct translation trajectory. To address these challenges in the C-to-Rust translation, we propose a novel intermediate step, the Virtual Fuzzing-based equivalence Test (VFT), and an agentic planning framework, the LLM-powered Agent for C-to-Rust code translation (LAC2R). The VFT guides LLMs to identify input arguments that induce divergent behaviors between an original C function and its Rust counterpart and to generate informative diagnoses to refine the unsafe Rust code. LAC2R uses the MCTS to systematically organize the LLM-induced intermediate steps for correct translation. We experimentally demonstrated that LAC2R effectively conducts C-to-Rust translation on large-scale, real-world benchmarks.

[Arxiv](https://arxiv.org/abs/2505.15858)