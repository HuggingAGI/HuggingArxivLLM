# 大型语言模型安全性：优化表示方法

发布时间：2025年04月02日

`LLM理论` `语言模型`

> Representation Bending for Large Language Model Safety

# 摘要

> 大型语言模型（LLMs）作为强大的工具崭露头角，但其内在的安全风险——从有害内容生成到广泛的社会危害——带来了巨大挑战。这些风险可能因最近的对抗攻击、微调漏洞以及LLMs在高风险环境中的普及而加剧。现有的增强安全性的技术，如基于人类反馈的微调或对抗训练，仍存在漏洞，因为它们仅针对特定威胁，通常无法在未见攻击中泛化，或需要手动系统级防御。本文介绍了一种名为RepBend的新方法，它从根本上破坏LLMs中导致有害行为的潜在表示，提供了一种可扩展的解决方案，以增强（可能是内在的）安全性。RepBend将“激活引导”理念引入基于损失的微调，通过简单的向量算术在推理过程中引导模型行为。通过广泛的评估，RepBend实现了最先进的性能，超越了之前的方法，如断路器、RMU和NPO，在各种越狱基准测试中将攻击成功率降低了高达95%，同时对模型的可用性和一般能力几乎没有影响。

> Large Language Models (LLMs) have emerged as powerful tools, but their inherent safety risks - ranging from harmful content generation to broader societal harms - pose significant challenges. These risks can be amplified by the recent adversarial attacks, fine-tuning vulnerabilities, and the increasing deployment of LLMs in high-stakes environments. Existing safety-enhancing techniques, such as fine-tuning with human feedback or adversarial training, are still vulnerable as they address specific threats and often fail to generalize across unseen attacks, or require manual system-level defenses. This paper introduces RepBend, a novel approach that fundamentally disrupts the representations underlying harmful behaviors in LLMs, offering a scalable solution to enhance (potentially inherent) safety. RepBend brings the idea of activation steering - simple vector arithmetic for steering model's behavior during inference - to loss-based fine-tuning. Through extensive evaluation, RepBend achieves state-of-the-art performance, outperforming prior methods such as Circuit Breaker, RMU, and NPO, with up to 95% reduction in attack success rates across diverse jailbreak benchmarks, all with negligible reduction in model usability and general capabilities.

[Arxiv](https://arxiv.org/abs/2504.01550)