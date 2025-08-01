# Seed-Prover：展现大型语言模型在自动定理证明中深度与广度兼具的推理能力。

发布时间：2025年07月31日

`LLM应用`

> Seed-Prover: Deep and Broad Reasoning for Automated Theorem Proving

# 摘要

> 大型语言模型（LLMs）借助长链式思维的强化学习，展现出了强大的数学推理能力。然而，仅使用自然语言时，由于缺乏明确的监督信号，它们在定理证明方面仍面临挑战。专用领域特定语言如Lean通过形式化验证提供清晰的监督信号，从而支持有效的强化学习训练。在此工作中，我们提出了	extbf{Seed-Prover}，一种基于引理的全证明推理模型。Seed-Prover能够根据Lean反馈、已证明的引理和自我总结，迭代地完善其证明过程。为了解决国际数学奥林匹克（IMO）级别的竞赛问题，我们设计了三种推理策略，能够在深度和广度上进行有效推理。Seed-Prover成功证明了78.1%的形式化过去IMO问题，完全解决了MiniF2F，且在PutnamBench上超过了50%，远超之前的最先进水平。针对Lean中缺乏几何支持的问题，我们引入了	extbf{Seed-Geometry}几何推理引擎，其性能优于之前的几何形式化引擎。我们利用这两个系统参加了2025年的IMO比赛，并成功证明了6个问题中的5个。这项工作在自动化数学推理领域取得了重大进展，证明了形式化验证与长链式推理相结合的有效性。

> LLMs have demonstrated strong mathematical reasoning abilities by leveraging reinforcement learning with long chain-of-thought, yet they continue to struggle with theorem proving due to the lack of clear supervision signals when solely using natural language. Dedicated domain-specific languages like Lean provide clear supervision via formal verification of proofs, enabling effective training through reinforcement learning. In this work, we propose \textbf{Seed-Prover}, a lemma-style whole-proof reasoning model. Seed-Prover can iteratively refine its proof based on Lean feedback, proved lemmas, and self-summarization. To solve IMO-level contest problems, we design three test-time inference strategies that enable both deep and broad reasoning. Seed-Prover proves $78.1\%$ of formalized past IMO problems, saturates MiniF2F, and achieves over 50\% on PutnamBench, outperforming the previous state-of-the-art by a large margin. To address the lack of geometry support in Lean, we introduce a geometry reasoning engine \textbf{Seed-Geometry}, which outperforms previous formal geometry engines. We use these two systems to participate in IMO 2025 and fully prove 5 out of 6 problems. This work represents a significant advancement in automated mathematical reasoning, demonstrating the effectiveness of formal verification with long chain-of-thought reasoning.

[Arxiv](https://arxiv.org/abs/2507.23726)