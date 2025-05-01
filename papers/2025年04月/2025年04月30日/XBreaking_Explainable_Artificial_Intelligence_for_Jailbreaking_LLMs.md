# # XBreaking：用于越狱大型语言模型的可解释人工智能
XBreaking 是一种可解释的人工智能技术，旨在揭示大型语言模型（LLMs）的潜在漏洞并提供透明的越狱方法。

发布时间：2025年04月30日

`LLM理论` `网络安全` `人工智能`

> XBreaking: Explainable Artificial Intelligence for Jailbreaking LLMs

# 摘要

> 大型语言模型是现代AI驱动IT领域的核心参与者。然而，其安全威胁可能阻碍其在政府机构和医疗机构等关键场景中的可靠应用。为此，商用大型语言模型通常会采用复杂的审查机制以消除潜在的有害输出。针对这一情况，大型语言模型的越狱攻击对这些保护机制构成了重大威胁，此前已有许多方法在不同领域证明了其有效性。现有的越狱提案大多采用生成并测试的策略来构造恶意输入。为了更深入理解审查机制并设计针对性的越狱攻击，我们提出了一种可解释的AI解决方案，通过比较分析被审查和未被审查模型的行为，推导出独特的可利用对齐模式。基于此，我们提出了一种名为XBreaking的新越狱攻击方法，该方法利用这些独特模式，通过有针对性的噪声注入来突破大型语言模型的安全约束。我们的全面实验不仅揭示了审查机制的重要见解，还验证了我们的攻击方法的有效性和性能表现。


> Large Language Models are fundamental actors in the modern IT landscape dominated by AI solutions. However, security threats associated with them might prevent their reliable adoption in critical application scenarios such as government organizations and medical institutions. For this reason, commercial LLMs typically undergo a sophisticated censoring mechanism to eliminate any harmful output they could possibly produce. In response to this, LLM Jailbreaking is a significant threat to such protections, and many previous approaches have already demonstrated its effectiveness across diverse domains. Existing jailbreak proposals mostly adopt a generate-and-test strategy to craft malicious input. To improve the comprehension of censoring mechanisms and design a targeted jailbreak attack, we propose an Explainable-AI solution that comparatively analyzes the behavior of censored and uncensored models to derive unique exploitable alignment patterns. Then, we propose XBreaking, a novel jailbreak attack that exploits these unique patterns to break the security constraints of LLMs by targeted noise injection. Our thorough experimental campaign returns important insights about the censoring mechanisms and demonstrates the effectiveness and performance of our attack.

[Arxiv](https://arxiv.org/abs/2504.21700)