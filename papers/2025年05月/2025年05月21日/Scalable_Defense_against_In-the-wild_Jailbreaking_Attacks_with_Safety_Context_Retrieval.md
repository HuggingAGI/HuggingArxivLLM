# 基于安全上下文检索的可扩展越狱攻击防御方案

发布时间：2025年05月21日

`LLM应用` `模型安全`

> Scalable Defense against In-the-wild Jailbreaking Attacks with Safety Context Retrieval

# 摘要

> 大型语言模型（LLMs）易受越狱攻击影响，攻击者通过精心设计的提示词诱导模型生成有害或不道德的响应。这一威胁引发了人们对LLMs实际应用安全性和可靠性的严重担忧。现有防御机制虽能在一定程度上缓解风险，但新型越狱方法的出现暴露了静态防御框架的局限性。本研究通过上下文检索的视角，探索抵御不断演变的越狱威胁的方法。首先，我们发现即使针对特定越狱攻击的少量安全对齐示例，也能显著提升模型的鲁棒性。基于此，我们利用增强生成（RAG）技术，提出了安全上下文检索（SCR），这是一种针对LLMs的可扩展且健壮的越狱防护范式。我们的实验表明，SCR在防御已知和新兴越狱战术方面表现卓越，为LLM安全领域贡献了全新范式。我们的代码将在论文发表后开放。

> Large Language Models (LLMs) are known to be vulnerable to jailbreaking attacks, wherein adversaries exploit carefully engineered prompts to induce harmful or unethical responses. Such threats have raised critical concerns about the safety and reliability of LLMs in real-world deployment. While existing defense mechanisms partially mitigate such risks, subsequent advancements in adversarial techniques have enabled novel jailbreaking methods to circumvent these protections, exposing the limitations of static defense frameworks. In this work, we explore defending against evolving jailbreaking threats through the lens of context retrieval. First, we conduct a preliminary study demonstrating that even a minimal set of safety-aligned examples against a particular jailbreak can significantly enhance robustness against this attack pattern. Building on this insight, we further leverage the retrieval-augmented generation (RAG) techniques and propose Safety Context Retrieval (SCR), a scalable and robust safeguarding paradigm for LLMs against jailbreaking. Our comprehensive experiments demonstrate how SCR achieves superior defensive performance against both established and emerging jailbreaking tactics, contributing a new paradigm to LLM safety. Our code will be available upon publication.

[Arxiv](https://arxiv.org/abs/2505.15753)