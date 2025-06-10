# 迈向自然语言形式化定理证明：Mathesis

发布时间：2025年06月08日

`LLM应用` `定理证明`

> Mathesis: Towards Formal Theorem Proving from Natural Languages

# 摘要

> 大型语言模型在形式推理领域展现出了巨大潜力，但现有基于LLM的定理证明器大多受限于专家编写的正式输入，难以处理现实中的自然语言问题。为解决这一难题，我们开发了Mathesis——首个处理非正式问题陈述的端到端定理证明流水线。Mathesis包含两个关键组件：Mathesis-Autoformalizer和Mathesis-Prover。前者是首个采用强化学习提升自然语言问题形式化能力的自动形式化器，借助我们的创新性LeanScorer框架实现精准的形式化质量评估；后者则能从形式化陈述中生成正式证明。为了全面评估端到端形式化定理证明的实际应用价值，我们构建了Gaokao-Formal基准，包含488个来自中国高考的复杂问题。通过深入研究每个组件并精心设计实验，我们证明了Mathesis的有效性：其自动形式化器在Gaokao-Formal上的通过率比最佳基线高出22%，完整系统在MiniF2F上达到64%的准确率（pass@32），并在Gaokao-Formal上取得了18%的最新水平。

> Recent advances in large language models show strong promise for formal reasoning. However, most LLM-based theorem provers have long been constrained by the need for expert-written formal statements as inputs, limiting their applicability to real-world problems expressed in natural language. We tackle this gap with Mathesis, the first end-to-end theorem proving pipeline processing informal problem statements. It contributes Mathesis-Autoformalizer, the first autoformalizer using reinforcement learning to enhance the formalization ability of natural language problems, aided by our novel LeanScorer framework for nuanced formalization quality assessment. It also proposes a Mathesis-Prover, which generates formal proofs from the formalized statements. To evaluate the real-world applicability of end-to-end formal theorem proving, we introduce Gaokao-Formal, a benchmark of 488 complex problems from China's national college entrance exam. Our approach is carefully designed, with a thorough study of each component. Experiments demonstrate Mathesis's effectiveness, with the autoformalizer outperforming the best baseline by 22% in pass-rate on Gaokao-Formal. The full system surpasses other model combinations, achieving 64% accuracy on MiniF2F with pass@32 and a state-of-the-art 18% on Gaokao-Formal.

[Arxiv](https://arxiv.org/abs/2506.07047)