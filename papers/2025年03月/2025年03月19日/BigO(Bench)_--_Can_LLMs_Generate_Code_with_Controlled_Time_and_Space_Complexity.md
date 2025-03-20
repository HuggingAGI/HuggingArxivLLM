# BigO(Bench) -- 大型语言模型能否生成时间和空间复杂度可控的代码？

发布时间：2025年03月19日

`LLM应用

理由：这篇论文专注于评估生成式语言模型在代码复杂度理解和生成方面的应用，设计了一个基准测试工具BigO(Bench)，并分析了模型的表现，属于LLM的应用研究。` `软件工程`

> BigO(Bench) -- Can LLMs Generate Code with Controlled Time and Space Complexity?

# 摘要

> 我们推出了BigO(Bench)这一全新编码基准测试，专注于评估生成式语言模型对代码时间和空间复杂度的理解与生成能力。现有评估往往忽视了模型在计算复杂度约束下理解和生成代码的能力，而BigO(Bench)正是为此而设计。该基准测试包含一套工具，能够从性能剖析数据中推断任何Python函数的算法复杂度，无论是人类还是LLM生成的代码均适用。此外，BigO(Bench)还整合了3,105个编程问题和1,190,250个来自编程竞赛的解决方案，所有内容均标注了基于复杂度框架推断出的时间和空间复杂度标签，并附带了大量输入规模对应的运行时间和内存占用数据。通过对多个先进语言模型在该基准测试上的表现进行评估，我们揭示了它们在处理复杂度要求方面的优缺点。值得注意的是，尽管在代码生成方面，基于token空间推理的模型表现卓越，但在复杂度理解方面则略显不足，这表明它们可能难以很好地泛化到那些在训练过程中未获得奖励的任务中。

> We introduce BigO(Bench), a novel coding benchmark designed to evaluate the capabilities of generative language models in understanding and generating code with specified time and space complexities. This benchmark addresses the gap in current evaluations that often overlook the ability of models to comprehend and produce code constrained by computational complexity. BigO(Bench) includes tooling to infer the algorithmic complexity of any Python function from profiling measurements, including human- or LLM-generated solutions. BigO(Bench) also includes of set of 3,105 coding problems and 1,190,250 solutions from Code Contests annotated with inferred (synthetic) time and space complexity labels from the complexity framework, as well as corresponding runtime and memory footprint values for a large set of input sizes. We present results from evaluating multiple state-of-the-art language models on this benchmark, highlighting their strengths and weaknesses in handling complexity requirements. In particular, token-space reasoning models are unrivaled in code generation but not in complexity understanding, hinting that they may not generalize well to tasks for which no reward was given at training time.

[Arxiv](https://arxiv.org/abs/2503.15242)