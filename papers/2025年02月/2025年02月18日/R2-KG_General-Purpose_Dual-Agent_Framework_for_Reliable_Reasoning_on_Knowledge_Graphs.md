# R2-KG：通用双智能体框架，助力可靠的知识图谱推理

发布时间：2025年02月18日

`LLM应用` `知识图谱` `问答系统`

> R2-KG: General-Purpose Dual-Agent Framework for Reliable Reasoning on Knowledge Graphs

# 摘要

> 近期研究通过结合大型语言模型 (LLMs) 与知识图谱 (KGs)，显著提升了推理能力，不仅无需额外训练即可提高推理准确性，还有效遏制了幻觉现象。然而，现有框架通常过于 rigid，难以适应 KG 或任务的变化，且高度依赖高容量 LLMs 来实现可靠推理。为解决这些问题，我们提出 R2-KG——一个即插即用的双代理框架，将推理过程拆分为两个角色：Operator（低容量 LLM）负责收集证据， Supervisor（高容量 LLM）负责做出最终判断。这种设计在保持强大推理准确性的同时，显著降低了 LLM 推理成本。此外，R2-KG 引入了 Abstention 机制，仅在从 KG 中收集到足够证据时才生成答案，大大提升了推理可靠性。实验结果表明，R2-KG 在多个基于 KG 的推理任务中，无论作为 Operator 使用的 LLM 能力如何，均在准确性和可靠性方面显著超越基线模型。进一步实验显示，配备严格自我一致性策略的单代理版 R2-KG，在降低推理成本的同时，可靠性远超基线水平。然而，其在复杂 KG 中的 abstention 率较高。我们的研究证实，R2-KG 是一个灵活且经济高效的基于 KG 推理解决方案，既能减少对高容量 LLMs 的依赖，又确保了推理的可信度。

> Recent studies have combined Large Language Models (LLMs) with Knowledge Graphs (KGs) to enhance reasoning, improving inference accuracy without additional training while mitigating hallucination. However, existing frameworks are often rigid, struggling to adapt to KG or task changes. They also rely heavily on powerful LLMs for reliable (i.e., trustworthy) reasoning. To address this, We introduce R2-KG, a plug-and-play, dual-agent framework that separates reasoning into two roles: an Operator (a low-capacity LLM) that gathers evidence and a Supervisor (a high-capacity LLM) that makes final judgments. This design is cost-efficient for LLM inference while still maintaining strong reasoning accuracy. Additionally, R2-KG employs an Abstention mechanism, generating answers only when sufficient evidence is collected from KG, which significantly enhances reliability. Experiments across multiple KG-based reasoning tasks show that R2-KG consistently outperforms baselines in both accuracy and reliability, regardless of the inherent capability of LLMs used as the Operator. Further experiments reveal that the single-agent version of R2-KG, equipped with a strict self-consistency strategy, achieves significantly higher-than-baseline reliability while reducing inference cost. However, it also leads to a higher abstention rate in complex KGs. Our findings establish R2-KG as a flexible and cost-effective solution for KG-based reasoning. It reduces reliance on high-capacity LLMs while ensuring trustworthy inference.

[Arxiv](https://arxiv.org/abs/2502.12767)