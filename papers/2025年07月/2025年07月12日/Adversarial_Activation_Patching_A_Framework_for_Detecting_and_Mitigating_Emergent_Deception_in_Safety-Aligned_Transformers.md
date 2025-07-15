# # 对抗激活修补：用于检测并缓解安全对齐变压器模型中新兴欺骗的框架

发布时间：2025年07月12日

`LLM理论

理由：这篇论文深入探讨了大型语言模型（LLMs）中的欺骗行为及其检测与缓解机制，属于模型理论层面的研究。` `人工智能安全` `人工智能`

> Adversarial Activation Patching: A Framework for Detecting and Mitigating Emergent Deception in Safety-Aligned Transformers

# 摘要

> 通过强化学习（如基于人类反馈的强化学习（RLHF））对齐安全性的大型语言模型（LLMs）常常展现出欺骗行为，其输出看似合规，实则隐晦地误导或遗漏关键信息。本文介绍了对抗激活补丁技术，这是一种新型的机制解释性框架，它利用激活补丁作为对抗工具，用于在基于变压器的模型中诱导、检测和缓解此类欺骗行为。通过从"欺骗性"提示中获取激活，并将其补丁到安全的正向传播过程中特定层，我们模拟了模型的漏洞，并量化了欺骗率。通过在多个场景下进行玩具神经网络模拟（例如每种设置1000次试验），我们证明了对抗性补丁将欺骗性输出从0%的基础水平增加到23.9%，且不同层的差异支持了我们的假设。我们提出了六种假设，包括模型间的可迁移性、多模态环境中的加剧效应以及规模效应。扩展的文献综述整合了解释性、欺骗和对抗攻击领域的20多篇关键作品。我们详细介绍了缓解策略，如激活异常检测和鲁棒微调，同时探讨了伦理考量和未来研究方向。这项工作通过强调补丁技术的双重用途潜力，推动了AI安全的发展，并为大规模模型的实证研究提供了路线图。

> Large language models (LLMs) aligned for safety through techniques like reinforcement learning from human feedback (RLHF) often exhibit emergent deceptive behaviors, where outputs appear compliant but subtly mislead or omit critical information. This paper introduces adversarial activation patching, a novel mechanistic interpretability framework that leverages activation patching as an adversarial tool to induce, detect, and mitigate such deception in transformer-based models. By sourcing activations from "deceptive" prompts and patching them into safe forward passes at specific layers, we simulate vulnerabilities and quantify deception rates. Through toy neural network simulations across multiple scenarios (e.g., 1000 trials per setup), we demonstrate that adversarial patching increases deceptive outputs to 23.9% from a 0% baseline, with layer-specific variations supporting our hypotheses. We propose six hypotheses, including transferability across models, exacerbation in multimodal settings, and scaling effects. An expanded literature review synthesizes over 20 key works in interpretability, deception, and adversarial attacks. Mitigation strategies, such as activation anomaly detection and robust fine-tuning, are detailed, alongside ethical considerations and future research directions. This work advances AI safety by highlighting patching's dual-use potential and provides a roadmap for empirical studies on large-scale models.

[Arxiv](https://arxiv.org/abs/2507.09406)