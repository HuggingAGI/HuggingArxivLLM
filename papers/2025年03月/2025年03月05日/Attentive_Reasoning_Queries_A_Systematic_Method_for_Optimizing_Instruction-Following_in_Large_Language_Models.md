# # 注意推理查询：优化大型语言模型的指令遵循能力的系统化方法

发布时间：2025年03月05日

`LLM理论

理由：这篇论文提出了一种新的结构化推理方法（ARQs），旨在提高大型语言模型（LLMs）在复杂场景下的指令遵循能力和推理效率。虽然提到了在 Parlant 框架中的应用测试，但核心贡献在于对 LLMs 的推理机制和性能提升的理论探讨，属于 LLM 理论的范畴。` `客户服务` `智能代理`

> Attentive Reasoning Queries: A Systematic Method for Optimizing Instruction-Following in Large Language Models

# 摘要

> 我们提出了一种名为专注推理查询 (Attentive Reasoning Queries, ARQs) 的新型结构化推理方法，通过领域专用的推理蓝图显著提升了大型语言模型 (LLMs) 的指令遵循能力。尽管 LLMs 在各种任务中展现出了非凡的能力，但在多轮对话中持续遵循复杂且特定于具体使用场景的指令时，它们往往表现不佳，这对关键业务应用构成了挑战。ARQs 通过引导 LLMs 完成系统化的推理步骤来解决这一局限性，这些步骤通过有针对性的查询重新确立关键指令，并在整个完成过程中促进中间推理。在 Parlant 中进行了大量测试，这是一个旨在构建可靠客户交互代理的框架，ARQs 在此框架中诞生于实际需求，结果在 87 个测试场景中达到了 90.2% 的成功率，超过了链式思维推理 (86.1%) 和直接响应生成 (81.5%)。ARQs 在解决一些顽固的失败模式（如指南的重新应用和幻觉预防）方面表现尤为出色。我们的分析还表明，当精心设计时，ARQs 可能比自由形式推理更具计算效率。这些发现证明，结构化推理方法为控制 LLMs 在复杂场景下处理信息和做出决策提供了有效的机制。

> We present Attentive Reasoning Queries (ARQs), a novel structured reasoning approach that significantly improves instruction-following in Large Language Models through domain-specialized reasoning blueprints. While LLMs demonstrate remarkable capabilities across diverse tasks, they often fail to maintain adherence to complex, use-case-specific instructions during multi-turn conversations, presenting challenges for business-critical applications. ARQs address this limitation by guiding LLMs through systematic reasoning steps with targeted queries that reinstate critical instructions and facilitate intermediate reasoning throughout the completion process. In extensive testing within Parlant, our framework for reliable customer-facing agents in which ARQs were born out of necessity, they achieved a 90.2% success rate across 87 test scenarios, outperforming both Chain-of-Thought reasoning (86.1%) and direct response generation (81.5%). ARQs showed particular strength in addressing persistent failure modes like guideline re-application and hallucination prevention. Our analysis also revealed that ARQs can potentially be more computationally efficient than free-form reasoning when carefully designed. These findings demonstrate that structured reasoning approaches provide effective mechanisms for controlling how LLMs process information and make decisions in complex scenarios.

[Arxiv](https://arxiv.org/abs/2503.03669)