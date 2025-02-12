# # 在Ada/SPARK软件验证背景下验证LLM生成的代码

发布时间：2025年02月11日

`LLM应用` `软件工程` `代码生成`

> Verifying LLM-Generated Code in the Context of Software Verification with Ada/SPARK

# 摘要

> 大型语言模型（LLMs）展现了卓越的代码生成能力，但生成代码的正确性无法被天然信任。本文探讨了采用Ada语言的SPARK框架进行形式化软件验证，以确保LLM生成代码的可靠性。我们介绍了一款名为Marmaragan的工具，该工具利用LLM为现有程序生成SPARK注释，从而实现代码的形式化验证。该工具在精选的SPARK程序集上进行了基准测试，通过选择性移除注释来测试特定能力。Marmaragan与GPT-4o在基准测试中的表现令人鼓舞，成功为50.7%的基准案例生成了正确注释。结果为未来结合LLMs的强大功能与形式化软件验证的可靠性奠定了研究基础。

> Large language models (LLMs) have demonstrated remarkable code generation capabilities, but the correctness of the generated code cannot be inherently trusted. This paper explores the feasibility of using formal software verification, specifically the SPARK framework for Ada, to ensure the reliability of LLM-generated code. We present Marmaragan, a tool that leverages an LLM in order to generate SPARK annotations for existing programs, enabling formal verification of the code. The tool is benchmarked on a curated set of SPARK programs, with annotations selectively removed to test specific capabilities. The performance of Marmaragan with GPT-4o on the benchmark is promising, with correct annotations having been generated for 50.7% of the benchmark cases. The results establish a foundation for future work on combining the power of LLMs with the reliability of formal software verification.

[Arxiv](https://arxiv.org/abs/2502.07728)