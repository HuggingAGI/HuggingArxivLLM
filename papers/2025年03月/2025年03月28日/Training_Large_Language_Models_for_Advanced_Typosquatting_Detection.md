# ## 训练大型语言模型用于高级拼写劫持检测

发布时间：2025年03月28日

`LLM应用` `网络安全` `网络威胁`

> Training Large Language Models for Advanced Typosquatting Detection

# 摘要

> 打字错误欺骗是一种长期存在的网络威胁，它利用用户输入URL时的失误来进行欺骗、传播恶意软件和实施钓鱼攻击。随着域名和新顶级域名的激增，打字错误欺骗技术变得更加复杂和狡猾，对个人、企业和国家网络安全基础设施构成了重大风险。传统检测方法主要关注已知的模仿模式，但在识别更复杂的攻击方面存在漏洞。本研究提出了一种基于大型语言模型（LLMs）的全新方法，以提升打字错误欺骗的检测能力。通过在字符级变换和基于模式的启发式方法上训练LLM，而非依赖特定领域的数据，我们开发出一种更加灵活且稳健的检测机制。实验结果表明，经过适当微调的Phi-4 14B模型在所有测试模型中表现最优，仅需几千个训练样本即可达到98%的准确率。这项研究凸显了大型语言模型在网络安全应用中的潜力，特别是在缓解基于域名的欺骗战术方面，并为优化威胁检测的机器学习策略提供了重要见解。


> Typosquatting is a long-standing cyber threat that exploits human error in typing URLs to deceive users, distribute malware, and conduct phishing attacks. With the proliferation of domain names and new Top-Level Domains (TLDs), typosquatting techniques have grown more sophisticated, posing significant risks to individuals, businesses, and national cybersecurity infrastructure. Traditional detection methods primarily focus on well-known impersonation patterns, leaving gaps in identifying more complex attacks. This study introduces a novel approach leveraging large language models (LLMs) to enhance typosquatting detection. By training an LLM on character-level transformations and pattern-based heuristics rather than domain-specific data, a more adaptable and resilient detection mechanism develops. Experimental results indicate that the Phi-4 14B model outperformed other tested models when properly fine tuned achieving a 98% accuracy rate with only a few thousand training samples. This research highlights the potential of LLMs in cybersecurity applications, specifically in mitigating domain-based deception tactics, and provides insights into optimizing machine learning strategies for threat detection.

[Arxiv](https://arxiv.org/abs/2503.22406)