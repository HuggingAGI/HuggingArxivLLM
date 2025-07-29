# # PrismRAG: 基于抗干扰能力与策略化推理增强 RAG 的事实可靠性

发布时间：2025年07月24日

`RAG` `问答系统`

> PrismRAG: Boosting RAG Factuality with Distractor Resilience and Strategized Reasoning

# 摘要

> 当检索到的上下文包含令人困惑的半相关段落，或者回答问题需要深刻上下文理解和推理时，检索增强生成（RAG）往往表现欠佳。为此，我们提出了一种名为PrismRAG的高效微调框架，该框架通过混合黄金证据与微妙干扰段落的干扰感知问答对来训练模型，并培养LLM以推理为中心的习惯，使其能够无需依赖大量人工编写的指令进行规划、推理和综合。在涵盖多种应用场景的12个开放域RAG问答基准测试中，PrismRAG将平均事实准确性提高了5.4%，超越了现有最优解决方案。

> Retrieval-augmented generation (RAG) often falls short when retrieved context includes confusing semi-relevant passages, or when answering questions require deep contextual understanding and reasoning. We propose an efficient fine-tuning framework, called PrismRAG, that (i) trains the model with distractor-aware QA pairs mixing gold evidence with subtle distractor passages, and (ii) instills reasoning-centric habits that make the LLM plan, rationalize, and synthesize without relying on extensive human engineered instructions. Evaluated across 12 open-book RAG QA benchmarks spanning diverse application domains and scenarios, PrismRAG improves average factuality by 5.4%, outperforming state-of-the-art solutions.

[Arxiv](https://arxiv.org/abs/2507.18857)