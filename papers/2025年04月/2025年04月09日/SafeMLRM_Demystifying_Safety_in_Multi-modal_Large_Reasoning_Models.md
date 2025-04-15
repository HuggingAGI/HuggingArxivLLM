# SafeMLRM: 探索多模态大型推理模型的安全性

发布时间：2025年04月09日

`LLM应用` `人工智能`

> SafeMLRM: Demystifying Safety in Multi-modal Large Reasoning Models

# 摘要

> 多模态大推理模型（MLRMs）——一种配备推理能力的多模态语言模型（MLLMs）增强版——的快速发展彻底改变了多种应用场景。然而，这些模型的安全性问题仍未得到充分探索。尽管之前的研究揭示了单模态推理模型的关键漏洞，但MLRMs由于其跨模态推理路径，带来了独特的安全风险。本研究通过大规模实证研究，首次系统性地对比分析了MLRMs与其基础MLLMs的安全性差异。我们的实验发现了三个关键结论：

（1）**推理税**：获得推理能力会灾难性地破坏继承的安全对齐。在对抗攻击下，MLRMs的越狱攻击成功率比基础MLLMs高出37.44%。

（2）**安全盲区**：尽管安全性能下降普遍存在，某些特定场景（例如非法活动）的攻击率竟高出平均水平25倍——远超平均3.4倍的增长幅度，揭示了场景特异性漏洞及其令人担忧的跨模型和跨数据集一致性。

（3）**自发纠错机制**：尽管推理与答案的安全性紧密相关，MLRMs仍展现出初步的自我纠错能力——16.9%的越狱推理步骤被安全答案所覆盖，暗示了潜在的内在防护机制。

这些发现凸显了场景感知型安全审计的紧迫性，以及放大MLRMs自我纠错潜力的机制需求。为了推动相关研究，我们开源了OpenSafeMLRM，首个专注于MLRM安全评估的工具包，为主流模型、数据集和越狱方法提供了统一接口。我们的工作呼吁立即行动，增强推理增强型AI的安全性，确保其变革潜力与伦理保障相辅相成。


> The rapid advancement of multi-modal large reasoning models (MLRMs) -- enhanced versions of multimodal language models (MLLMs) equipped with reasoning capabilities -- has revolutionized diverse applications. However, their safety implications remain underexplored. While prior work has exposed critical vulnerabilities in unimodal reasoning models, MLRMs introduce distinct risks from cross-modal reasoning pathways. This work presents the first systematic safety analysis of MLRMs through large-scale empirical studies comparing MLRMs with their base MLLMs. Our experiments reveal three critical findings: (1) The Reasoning Tax: Acquiring reasoning capabilities catastrophically degrades inherited safety alignment. MLRMs exhibit 37.44% higher jailbreaking success rates than base MLLMs under adversarial attacks. (2) Safety Blind Spots: While safety degradation is pervasive, certain scenarios (e.g., Illegal Activity) suffer 25 times higher attack rates -- far exceeding the average 3.4 times increase, revealing scenario-specific vulnerabilities with alarming cross-model and datasets consistency. (3) Emergent Self-Correction: Despite tight reasoning-answer safety coupling, MLRMs demonstrate nascent self-correction -- 16.9% of jailbroken reasoning steps are overridden by safe answers, hinting at intrinsic safeguards. These findings underscore the urgency of scenario-aware safety auditing and mechanisms to amplify MLRMs' self-correction potential. To catalyze research, we open-source OpenSafeMLRM, the first toolkit for MLRM safety evaluation, providing unified interface for mainstream models, datasets, and jailbreaking methods. Our work calls for immediate efforts to harden reasoning-augmented AI, ensuring its transformative potential aligns with ethical safeguards.

[Arxiv](https://arxiv.org/abs/2504.08813)