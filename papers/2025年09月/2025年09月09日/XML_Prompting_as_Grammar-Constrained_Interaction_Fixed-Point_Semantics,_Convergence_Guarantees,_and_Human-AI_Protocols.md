# XML提示作为语法约束交互：不动点语义、收敛性保证及人机AI协议

发布时间：2025年09月09日

`LLM理论` `基础理论`

> XML Prompting as Grammar-Constrained Interaction: Fixed-Point Semantics, Convergence Guarantees, and Human-AI Protocols

# 摘要

> 借助XML标签的结构化提示已成为现实系统中引导大型语言模型（LLMs）生成可解析、符合格式规范输出的高效手段。我们提出了一种以逻辑为核心的XML提示处理框架，它统一了（i）语法约束解码、（ii）分层提示格上的不动点语义，以及（iii）收敛的人机AI交互循环。我们在细化序下构建了XML树的完备格模型，并证明单调的提示到提示算子存在最小不动点（Knaster-Tarski定理），该不动点可刻画稳态协议；在树的任务感知收缩度量下，我们进一步证明了迭代引导的巴拿赫式收敛性。通过XML模式的上下文无关文法（CFGs）实例化这些结论后，我们展示了约束解码在确保输出格式正确的同时，如何保持任务性能。我们还提供了一系列多层人机AI交互方案，展示了实际部署模式，包括多轮“计划→验证→修订”流程和智能体工具调用。最后，我们给出了数学上完备的证明，并将该框架与语法对齐解码、验证链和程序化提示等最新技术进展相结合。

> Structured prompting with XML tags has emerged as an effective way to steer large language models (LLMs) toward parseable, schema-adherent outputs in real-world systems. We develop a logic-first treatment of XML prompting that unifies (i) grammar-constrained decoding, (ii) fixed-point semantics over lattices of hierarchical prompts, and (iii) convergent human-AI interaction loops. We formalize a complete lattice of XML trees under a refinement order and prove that monotone prompt-to-prompt operators admit least fixed points (Knaster-Tarski) that characterize steady-state protocols; under a task-aware contraction metric on trees, we further prove Banach-style convergence of iterative guidance. We instantiate these results with context-free grammars (CFGs) for XML schemas and show how constrained decoding guarantees well-formedness while preserving task performance. A set of multi-layer human-AI interaction recipes demonstrates practical deployment patterns, including multi-pass "plan $\to$ verify $\to$ revise" routines and agentic tool use. We provide mathematically complete proofs and tie our framework to recent advances in grammar-aligned decoding, chain-of-verification, and programmatic prompting.

[Arxiv](https://arxiv.org/abs/2509.08182)