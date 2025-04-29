# Mem0: 打造具备可扩展长期记忆的生产级AI代理

发布时间：2025年04月27日

`LLM应用

理由：这篇论文主要讨论了如何通过记忆机制来提升大型语言模型在多轮对话中的表现，属于将LLMs应用于对话系统中的具体改进和优化。` `对话系统`

> Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory

# 摘要

> 大型语言模型 (LLMs) 在生成上下文连贯的响应方面表现出色，但固定大小的上下文窗口限制了其在多轮对话中保持一致性的能力。我们提出了 Mem0，一种可扩展的以记忆为中心的架构，通过动态提取、整合和检索当前对话中的关键信息来解决这一问题。在此基础上，我们进一步提出了一种增强版本，利用基于图的记忆表示来捕捉对话元素之间的复杂关系结构。通过在 LOCOMO 基准上的全面评估，我们系统性地将我们的方法与六种基线类别进行了比较：(i) 已有的记忆增强系统，(ii) 检索增强生成 (RAG) 具有不同块大小和 k 值，(iii) 处理完整对话历史的全上下文方法，(iv) 开源记忆解决方案，(v) 专有模型系统，以及 (vi) 专用记忆管理平台。实验结果表明，我们的方法在四个问题类别（单跳、时间、多跳和开放领域）上始终优于现有的所有记忆系统。值得注意的是，Mem0 在 LLM-as-a-Judge 评估指标上比 OpenAI 高出 26% 的相对改进，而结合图记忆的 Mem0 则比基础配置高出约 2% 的整体得分。除了提升准确性，我们的方法与全上下文方法相比还显著降低了计算开销。特别是，Mem0 实现了 91% 的 p95 延迟降低，并节省了超过 90% 的令牌成本，实现了高级推理能力和实际部署约束之间的良好平衡。我们的研究结果突显了结构化、持久化记忆机制在长期对话连贯性中的关键作用，为更可靠和高效的 LLM 驱动 AI 代理铺平了道路。

> Large Language Models (LLMs) have demonstrated remarkable prowess in generating contextually coherent responses, yet their fixed context windows pose fundamental challenges for maintaining consistency over prolonged multi-session dialogues. We introduce Mem0, a scalable memory-centric architecture that addresses this issue by dynamically extracting, consolidating, and retrieving salient information from ongoing conversations. Building on this foundation, we further propose an enhanced variant that leverages graph-based memory representations to capture complex relational structures among conversational elements. Through comprehensive evaluations on LOCOMO benchmark, we systematically compare our approaches against six baseline categories: (i) established memory-augmented systems, (ii) retrieval-augmented generation (RAG) with varying chunk sizes and k-values, (iii) a full-context approach that processes the entire conversation history, (iv) an open-source memory solution, (v) a proprietary model system, and (vi) a dedicated memory management platform. Empirical results show that our methods consistently outperform all existing memory systems across four question categories: single-hop, temporal, multi-hop, and open-domain. Notably, Mem0 achieves 26% relative improvements in the LLM-as-a-Judge metric over OpenAI, while Mem0 with graph memory achieves around 2% higher overall score than the base configuration. Beyond accuracy gains, we also markedly reduce computational overhead compared to full-context method. In particular, Mem0 attains a 91% lower p95 latency and saves more than 90% token cost, offering a compelling balance between advanced reasoning capabilities and practical deployment constraints. Our findings highlight critical role of structured, persistent memory mechanisms for long-term conversational coherence, paving the way for more reliable and efficient LLM-driven AI agents.

[Arxiv](https://arxiv.org/abs/2504.19413)