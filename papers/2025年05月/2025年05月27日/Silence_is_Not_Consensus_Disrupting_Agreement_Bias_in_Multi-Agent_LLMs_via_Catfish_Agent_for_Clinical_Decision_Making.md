# 沉默非共识：鲶鱼智能体颠覆多智能体LLMs的一致偏见，助力临床决策

发布时间：2025年05月27日

`Agent` `问答系统`

> Silence is Not Consensus: Disrupting Agreement Bias in Multi-Agent LLMs via Catfish Agent for Clinical Decision Making

# 摘要

> 大型语言模型（LLMs）在临床问答领域展现出了强大的潜力，而多智能体框架通过协作推理进一步提升了诊断的准确性。然而，我们在实际应用中发现了一个普遍存在的问题：Silent Agreement。具体来说，智能体往往在没有充分分析的情况下过早达成诊断共识，特别是在复杂或模糊的案例中。为了解决这一问题，我们提出了一种全新的概念——Catfish Agent。这是一种角色专用的LLM，旨在通过注入结构化的异议来打破这种沉默的共识。受组织心理学中的“鲶鱼效应”启发，Catfish Agent被设计用于挑战正在形成的共识，从而激发更深入的推理过程。我们提出了两种机制来实现有效且情境感知的干预：(i) 一种基于案例难度调节智能体参与度的复杂性感知干预，以及(ii) 一种平衡批判与协作的语气校准干预。在九个医学问答和三个医学视觉问答基准上的评估结果显示，我们的方法在性能上始终优于现有的单智能体和多智能体LLM框架，包括GPT-4o和DeepSeek-R1等领先的商业模型。

> Large language models (LLMs) have demonstrated strong potential in clinical question answering, with recent multi-agent frameworks further improving diagnostic accuracy via collaborative reasoning. However, we identify a recurring issue of Silent Agreement, where agents prematurely converge on diagnoses without sufficient critical analysis, particularly in complex or ambiguous cases. We present a new concept called Catfish Agent, a role-specialized LLM designed to inject structured dissent and counter silent agreement. Inspired by the ``catfish effect'' in organizational psychology, the Catfish Agent is designed to challenge emerging consensus to stimulate deeper reasoning. We formulate two mechanisms to encourage effective and context-aware interventions: (i) a complexity-aware intervention that modulates agent engagement based on case difficulty, and (ii) a tone-calibrated intervention articulated to balance critique and collaboration. Evaluations on nine medical Q&A and three medical VQA benchmarks show that our approach consistently outperforms both single- and multi-agent LLMs frameworks, including leading commercial models such as GPT-4o and DeepSeek-R1.

[Arxiv](https://arxiv.org/abs/2505.21503)