# # 区分语言编码与问题解决：基于 PseudoEval 对大型语言模型进行基准测试

发布时间：2025年02月26日

`LLM应用` `软件工程` `计算机科学`

> Isolating Language-Coding from Problem-Solving: Benchmarking LLMs with PseudoEval

# 摘要

> 现有的大型语言模型（LLMs）代码生成基准，如HumanEval和MBPP，用于研究LLMs的端到端性能。这些基准通过将自然语言的问题描述作为输入，并对特定编程语言生成的代码进行评估。然而，评估分数对代码生成的瓶颈问题提供的线索有限——LLMs是难以应对问题解决能力，还是语言编码能力？为了解答这一问题，我们构建了PseudoEval，这是一个多语言代码生成基准，提供用伪代码编写的解决方案作为输入。通过这种方式，可以隔离并识别不同编程语言中代码生成的瓶颈。我们的研究得出了几个有趣的发现：LLMs在Python编程中的瓶颈在于问题解决能力，而Rust则在语言编码能力上相对更为吃力。此外，问题解决能力可能在不同编程语言之间迁移，而语言编码能力则需要更多的语言特定努力，尤其是对于训练不足的编程语言。最后，我们发布了构建PseudoEval的pipeline，以促进对现有基准的扩展。PseudoEval可在以下链接获取：https://anonymous.4open.science/r/PseudocodeACL25-7B74。


> Existing code generation benchmarks for Large Language Models (LLMs) such as HumanEval and MBPP are designed to study LLMs' end-to-end performance, where the benchmarks feed a problem description in natural language as input and examine the generated code in specific programming languages. However, the evaluation scores revealed in this way provide a little hint as to the bottleneck of the code generation -- whether LLMs are struggling with their problem-solving capability or language-coding capability. To answer this question, we construct PseudoEval, a multilingual code generation benchmark that provides a solution written in pseudocode as input. By doing so, the bottleneck of code generation in various programming languages could be isolated and identified. Our study yields several interesting findings. For example, we identify that the bottleneck of LLMs in Python programming is problem-solving, while Rust is struggling relatively more in language-coding. Also, our study indicates that problem-solving capability may transfer across programming languages, while language-coding needs more language-specific effort, especially for undertrained programming languages. Finally, we release the pipeline of constructing PseudoEval to facilitate the extension to existing benchmarks. PseudoEval is available at: https://anonymous.4open.science/r/PseudocodeACL25-7B74.

[Arxiv](https://arxiv.org/abs/2502.19149)