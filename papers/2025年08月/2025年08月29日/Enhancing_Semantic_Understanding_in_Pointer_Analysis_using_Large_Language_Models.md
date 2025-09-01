# 利用大型语言模型增强指针分析的语义理解

发布时间：2025年08月29日

`LLM应用` `基础理论`

> Enhancing Semantic Understanding in Pointer Analysis using Large Language Models

# 摘要

> 指针分析的研究已历经四十余载，然而现有框架仍受错误信息传播问题的困扰。其主要局限在于对代码语义理解不足，进而导致对用户定义函数的处理过于保守。大型语言模型（LLMs）的近期进展为弥合这一差距带来了新的契机。本文提出LMPA（LLM增强型指针分析），旨在将LLMs集成到指针分析中，以同时提升精度与可扩展性。LMPA通过识别与系统API相似的用户定义函数并对其建模，有效缓解了错误的跨调用上下文传播问题。此外，该方法还通过推断初始指向集、引入结合自然语言的新型摘要策略，进一步优化了基于摘要的分析。最后，本文探讨了实现该愿景面临的关键挑战。

> Pointer analysis has been studied for over four decades. However, existing frameworks continue to suffer from the propagation of incorrect facts. A major limitation stems from their insufficient semantic understanding of code, resulting in overly conservative treatment of user-defined functions. Recent advances in large language models (LLMs) present new opportunities to bridge this gap. In this paper, we propose LMPA (LLM-enhanced Pointer Analysis), a vision that integrates LLMs into pointer analysis to enhance both precision and scalability. LMPA identifies user-defined functions that resemble system APIs and models them accordingly, thereby mitigating erroneous cross-calling-context propagation. Furthermore, it enhances summary-based analysis by inferring initial points-to sets and introducing a novel summary strategy augmented with natural language. Finally, we discuss the key challenges involved in realizing this vision.

[Arxiv](https://arxiv.org/abs/2508.21454)