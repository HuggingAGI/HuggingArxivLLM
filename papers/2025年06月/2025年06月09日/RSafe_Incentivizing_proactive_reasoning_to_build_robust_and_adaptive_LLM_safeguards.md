# RSafe：激励主动推理，构建稳健且自适应的大型语言模型防护机制

发布时间：2025年06月09日

`LLM应用` `内容安全` `人工智能安全`

> RSafe: Incentivizing proactive reasoning to build robust and adaptive LLM safeguards

# 摘要

> 尽管进行了刻意的安全对齐努力，大型语言模型（LLMs）仍然表现出漏洞，对用户和社会构成重大风险。为了防御违反政策内容的风险，通过外部监护模型进行系统级内容审核作为一种预防策略应运而生，这些监护模型旨在监控LLMs的输入和输出，并阻止潜在有害内容的生成。现有的训练监护模型的方法严重依赖于大量人工整理的数据集，并且难以应对分布外的威胁，例如新兴有害类别或越狱攻击。为了解决这些局限性，我们提出了RSafe，这是一种基于自适应推理的安全保障机制，通过引导式安全推理提供符合规定安全策略范围内的强大保护。RSafe分为两个阶段运行：1）引导推理，其中它通过基于政策的逐步推理分析输入内容的安全风险；2）强化对齐，其中基于规则的强化学习优化其推理路径，以与准确的安全预测保持一致。这种两阶段的训练范式使RSafe能够内化安全原则，从而在面对未见或对抗性的安全违规场景时，具备推广安全防护能力。在推理过程中，RSafe接受用户指定的安全策略，提供符合特定安全需求的增强型安全保护。

> Large Language Models (LLMs) continue to exhibit vulnerabilities despite deliberate safety alignment efforts, posing significant risks to users and society. To safeguard against the risk of policy-violating content, system-level moderation via external guard models-designed to monitor LLM inputs and outputs and block potentially harmful content-has emerged as a prevalent mitigation strategy. Existing approaches of training guard models rely heavily on extensive human curated datasets and struggle with out-of-distribution threats, such as emerging harmful categories or jailbreak attacks. To address these limitations, we propose RSafe, an adaptive reasoning-based safeguard that conducts guided safety reasoning to provide robust protection within the scope of specified safety policies. RSafe operates in two stages: 1) guided reasoning, where it analyzes safety risks of input content through policy-guided step-by-step reasoning, and 2) reinforced alignment, where rule-based RL optimizes its reasoning paths to align with accurate safety prediction. This two-stage training paradigm enables RSafe to internalize safety principles to generalize safety protection capability over unseen or adversarial safety violation scenarios. During inference, RSafe accepts user-specified safety policies to provide enhanced safeguards tailored to specific safety requirements.

[Arxiv](https://arxiv.org/abs/2506.07736)