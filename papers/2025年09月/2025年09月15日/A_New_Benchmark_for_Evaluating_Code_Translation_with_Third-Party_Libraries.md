# 评估第三方库代码翻译的新基准

发布时间：2025年09月15日

`LLM应用` `基础理论`

> A New Benchmark for Evaluating Code Translation with Third-Party Libraries

# 摘要

> 近年来，大型语言模型（LLMs）在代码翻译领域已被广泛研究，涵盖方法、类乃至仓库级别。但这些基准测试在第三方库（TPL）的类别与规模上多有局限，使得TPL相关错误难以显现，也制约了针对性解决方案的研发。鉴于实际编程中对TPL的依赖度极高（超过90%），揭示并分析LLMs在涉及各类TPL的代码翻译表现已势在必行。为填补这一空白，我们构建了TransLibEval——首个专注于库中心代码翻译的基准测试。该基准包含200个跨Python、Java和C++的真实任务，每个任务均明确涉及数据处理、机器学习、Web开发等多个类别的TPL，且覆盖全面的依赖关系和高覆盖率的测试套件。我们基于三类六种翻译策略（直接翻译、IR引导、检索增强），对商业类、通用类及代码专用类的七个最新LLM进行了评估。实验结果表明，与无库场景相比，性能大幅下降（平均CA降幅超60%），而不同策略则展现出各异的优势。此外，我们分析了最先进（SOTA）LLM之一GPT-4o的4831个失败案例，揭示了大量此前未被发现的第三方引用错误。这些发现凸显了库中心翻译的独特挑战，并为提升TPL感知的代码智能提供了实用指导。

> In recent years, Large Language Models (LLMs) have been widely studied in the code translation field on the method, class, and even repository levels. However, most of these benchmarks are limited in terms of Third-Party Library (TPL) categories and scales, making TPL-related errors hard to expose and hindering the development of targeted solutions. Considering the high dependence (over 90%) on TPLs in practical programming, demystifying and analyzing LLMs' code translation performance involving various TPLs becomes imperative. To address this gap, we construct TransLibEval, the first benchmark dedicated to library-centric code translation. It consists of 200 real-world tasks across Python, Java, and C++, each explicitly involving TPLs from diverse categories such as data processing, machine learning, and web development, with comprehensive dependency coverage and high-coverage test suites. We evaluate seven recent LLMs of commercial, general, and code-specialized families under six translation strategies of three categories: Direct, IR-guided, and Retrieval-augmented. Experimental results show a dramatic performance drop compared with library-free settings (average CA decline over 60%), while diverse strategies demonstrate heterogeneous advantages. Furthermore, we analyze 4,831 failed cases from GPT-4o, one of the State-of-the-Art (SOTA) LLMs, revealing numerous third-party reference errors that were obscured previously. These findings highlight the unique challenges of library-centric translation and provide practical guidance for improving TPL-aware code intelligence.

[Arxiv](https://arxiv.org/abs/2509.12087)