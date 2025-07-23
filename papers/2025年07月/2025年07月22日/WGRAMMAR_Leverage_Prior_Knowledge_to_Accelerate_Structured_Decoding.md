# # WGRAMMAR：利用已有知识加速结构化解码

发布时间：2025年07月22日

`LLM应用

摘要中的论文探讨了如何优化大型语言模型生成结构化输出的效率，属于应用层面的改进，因此归类为LLM应用。` `软件开发`

> WGRAMMAR: Leverage Prior Knowledge to Accelerate Structured Decoding

# 摘要

> 结构化解码让大型语言模型 (LLMs) 能够生成下游系统所需的格式化输出，如 HTML 或 JSON。然而，现有方法因语法编译、状态跟踪和掩码创建而面临效率瓶颈。我们发现，许多实际任务中蕴含了对输出结构的强先验知识。基于此，我们提出将约束分解为静态和动态两部分——离线预编译静态结构，并在运行时使用语法片段动态生成参数。我们摒弃了传统的下推自动机方法，转而采用一组组合算子来建模规则格式，从而实现更低的转换延迟。我们推出了 wgrammar，这是一个轻量级的解码引擎，集成了领域感知的简化、约束分解和掩码缓存功能，与现有系统相比实现了最高 250 倍的速度提升。wgrammar 的源代码现已公开，访问地址为 https://github.com/wrran/wgrammar。

> Structured decoding enables large language models (LLMs) to generate outputs in formats required by downstream systems, such as HTML or JSON. However, existing methods suffer from efficiency bottlenecks due to grammar compilation, state tracking, and mask creation. We observe that many real-world tasks embed strong prior knowledge about output structure. Leveraging this, we propose a decomposition of constraints into static and dynamic components -- precompiling static structures offline and instantiating dynamic arguments at runtime using grammar snippets. Instead of relying on pushdown automata, we employ a compositional set of operators to model regular formats, achieving lower transition latency. We introduce wgrammar, a lightweight decoding engine that integrates domain-aware simplification, constraint decomposition, and mask caching, achieving up to 250x speedup over existing systems. wgrammar's source code is publicly available at https://github.com/wrran/wgrammar.

[Arxiv](https://arxiv.org/abs/2507.16768)