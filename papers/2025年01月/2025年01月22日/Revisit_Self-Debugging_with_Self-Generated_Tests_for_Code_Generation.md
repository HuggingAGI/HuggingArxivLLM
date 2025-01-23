# 重新审视基于自生成测试的代码生成自调试

发布时间：2025年01月22日

`LLM应用

理由：这篇论文主要讨论了如何通过自我调试的方法来提升大型语言模型（LLMs）在代码生成任务中的性能。具体来说，它探讨了自生成测试的自我调试在多样化编程问题上的有效性，并提出了两种调试范式。这些内容直接涉及到LLM在实际应用中的性能优化和问题解决，因此应归类为“LLM应用”。` `软件工程`

> Revisit Self-Debugging with Self-Generated Tests for Code Generation

# 摘要

> 大型语言模型（LLMs）在代码生成领域取得了显著进展，但在处理超出其基本能力的任务时仍面临挑战。最近，自我调试的概念被提出，旨在通过测试的执行反馈来提升代码生成性能。尽管这一方法前景广阔，但现实场景中高质量测试的稀缺性限制了其应用。为此，自生成测试的自我调试成为了一种有潜力的解决方案，但其局限性和实际潜力尚未被充分探索。因此，我们研究了其在多样化编程问题上的有效性。为了深入理解，我们提出了两种调试范式：执行后调试和执行中调试。在独立的Python编程任务中，我们发现执行后调试在基础问题上表现不佳，但在竞争性问题上显示出改进潜力，这主要归因于自生成测试引入的偏差。相比之下，执行中调试通过利用执行过程中的中间状态，有效减轻了偏差，从而提升了代码生成的质量。

> Large language models (LLMs) have shown significant advancements in code generation, but still face challenges on tasks beyond their basic capabilities. Recently, the notion of self-debugging has been proposed to boost the performance of code generation by leveraging execution feedback from tests. Despite its promise, the availability of high-quality tests in real-world scenarios is limited. In this context, self-debugging with self-generated tests is a promising solution but lacks a full exploration of its limitations and practical potential. Therefore, we investigate its efficacy on diverse programming problems. To deepen our understanding, we propose two distinct paradigms for the process: post-execution and in-execution self-debugging. Within the scope of self-contained Python programming tasks, we find that post-execution self-debugging struggles on basic problems but shows potential for improvement on competitive ones, due to the bias introduced by self-generated tests. On the other hand, in-execution self-debugging enables LLMs to mitigate the bias by solely leveraging intermediate states during execution, thereby enhancing code generation.

[Arxiv](https://arxiv.org/abs/2501.12793)