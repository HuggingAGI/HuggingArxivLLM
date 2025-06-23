# SemAgent：语义感知的程序修复代理

发布时间：2025年06月19日

`LLM应用` `软件工程` `自动程序修复`

> SemAgent: A Semantics Aware Program Repair Agent

# 摘要

> 大型语言模型（LLMs）在自动程序修复（APR）等软件工程任务中表现卓越。特别是在仓库级问题解决基准测试（如SWE-Bench）方面，已有大量研究。尽管进展显著，但现有代理系统在修复过程中往往过度聚焦于可疑代码行，缺乏对问题、代码及执行语义的深入理解，导致生成的补丁过于拟合特定问题，即使更通用的修复更优。为解决此问题，我们提出了SemAgent，一种基于工作流的新方法，通过整合问题、代码和执行语义，生成全面的修复补丁。我们的方法通过以下步骤实现：首先，利用执行语义检索相关上下文；其次，通过抽象理解问题语义；然后，在此抽象下隔离代码语义；最后，在两阶段架构中应用这些理解：修复阶段提出细粒度修复，审查阶段基于推断的问题语义过滤相关修复。实验结果显示，SemAgent在SWEBench-Lite基准测试中达到44.66%的解决率，超越所有其他工作流方法，较基线提升7.66%。特别在需要多行推理和处理边缘情况的问题上，SemAgent表现优异，证明将语义分析纳入修复流程可显著提升修复质量和通用性。

> Large Language Models (LLMs) have shown impressive capabilities in downstream software engineering tasks such as Automated Program Repair (APR). In particular, there has been a lot of research on repository-level issue-resolution benchmarks such as SWE-Bench. Although there has been significant progress on this topic, we notice that in the process of solving such issues, existing agentic systems tend to hyper-localize on immediately suspicious lines of code and fix them in isolation, without a deeper understanding of the issue semantics, code semantics, or execution semantics. Consequently, many existing systems generate patches that overfit to the user issue, even when a more general fix is preferable. To address this limitation, we introduce SemAgent, a novel workflow-based procedure that leverages issue, code, and execution semantics to generate patches that are complete - identifying and fixing all lines relevant to the issue. We achieve this through a novel pipeline that (a) leverages execution semantics to retrieve relevant context, (b) comprehends issue-semantics via generalized abstraction, (c) isolates code-semantics within the context of this abstraction, and (d) leverages this understanding in a two-stage architecture: a repair stage that proposes fine-grained fixes, followed by a reviewer stage that filters relevant fixes based on the inferred issue-semantics. Our evaluations show that our methodology achieves a solve rate of 44.66% on the SWEBench-Lite benchmark beating all other workflow-based approaches, and an absolute improvement of 7.66% compared to our baseline, which lacks such deep semantic understanding. We note that our approach performs particularly well on issues requiring multi-line reasoning (and editing) and edge-case handling, suggesting that incorporating issue and code semantics into APR pipelines can lead to robust and semantically consistent repairs.

[Arxiv](https://arxiv.org/abs/2506.16650)