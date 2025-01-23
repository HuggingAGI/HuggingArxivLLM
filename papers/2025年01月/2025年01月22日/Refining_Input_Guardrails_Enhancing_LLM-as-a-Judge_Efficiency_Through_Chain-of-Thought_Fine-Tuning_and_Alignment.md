# 优化输入护栏：通过思维链微调与对齐提升LLM评判效率

发布时间：2025年01月22日

`LLM应用

理由：这篇论文主要探讨了如何通过微调和思维链（CoT）响应对齐来增强大型语言模型（LLMs）的输入审核能力，以提升对话式AI系统的安全性。这属于LLM在实际应用中的改进和优化，因此归类为“LLM应用”。` `人工智能` `网络安全`

> Refining Input Guardrails: Enhancing LLM-as-a-Judge Efficiency Through Chain-of-Thought Fine-Tuning and Alignment

# 摘要

> 大型语言模型（LLMs）展现了强大的能力，广泛应用于对话式AI等领域。然而，确保这些产品的安全性和可靠性至关重要，尤其是防范恶意用户交互带来的风险和声誉损害。本研究深入探讨了如何通过微调和思维链（CoT）响应对齐来增强LLMs的输入审核能力。我们利用少量训练数据，系统研究了多种调优方法，使模型能够作为代理防御机制，有效检测恶意输入并给出判断依据，从而防止对话代理被滥用。我们严格评估了不同调优策略的泛化能力和鲁棒性，实验结果表明，即使在数据有限的情况下，针对各类有害输入的对齐过程仍具有显著潜力。这些技术大幅提升了对话式AI系统的安全性，为构建更安全、可信的AI交互提供了可行框架。

> Large Language Models (LLMs) have demonstrated powerful capabilities that render them valuable in different applications, including conversational AI products. It is paramount to ensure the security and reliability of these products by mitigating their vulnerabilities towards malicious user interactions, which can lead to the exposure of great risks and reputational repercussions. In this work, we present a comprehensive study on the efficacy of fine-tuning and aligning Chain-of-Thought (CoT) responses of different LLMs that serve as input moderation guardrails. We systematically explore various tuning methods by leveraging a small set of training data to adapt these models as proxy defense mechanisms to detect malicious inputs and provide a reasoning for their verdicts, thereby preventing the exploitation of conversational agents. We rigorously evaluate the efficacy and robustness of different tuning strategies to generalize across diverse adversarial and malicious query types. Our experimental results outline the potential of alignment processes tailored to a varied range of harmful input queries, even with constrained data resources. These techniques significantly enhance the safety of conversational AI systems and provide a feasible framework for deploying more secure and trustworthy AI-driven interactions.

[Arxiv](https://arxiv.org/abs/2501.13080)