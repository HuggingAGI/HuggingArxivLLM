# 基于模型编辑来突破安全对齐的大型语言模型的限制

发布时间：2024年12月11日

`LLM应用` `语言模型` `安全防护`

> Model-Editing-Based Jailbreak against Safety-aligned Large Language Models

# 摘要

> 大型语言模型（LLMs）凭借实现高级自然语言交互，变革了诸多领域，然而却易受重大漏洞影响，尤其是越狱攻击。当下的越狱技术虽有效，却常依赖输入修改，这导致其易被察觉，也限制了其隐蔽性与可扩展性。本文呈现了一种名为目标模型编辑（TME）的全新白盒方法，它能在保留模型预期功能的同时，通过最小化改变内部模型结构来绕过安全过滤器。TME 能够识别并移除嵌入模型矩阵中的安全关键转换（SCTs），让恶意查询无需输入修改就能突破限制。通过分析安全与不安全查询之间的不同激活模式，TME 借助优化过程来隔离并近似 SCTs。在 D-LLM 框架中得以实施，我们的方法在四个主流开源 LLMs 上实现了平均 84.86％的攻击成功率（ASR），保持着高性能。与现有方法不同，D-LLM 无需特定触发或有害响应集合，提供了更隐秘、更有效的越狱策略。此项工作揭示了 LLM 安全中一个隐秘且强大的威胁向量，也强调了在模型安全对齐方面需要更强有力的保障措施。

> Large Language Models (LLMs) have transformed numerous fields by enabling advanced natural language interactions but remain susceptible to critical vulnerabilities, particularly jailbreak attacks. Current jailbreak techniques, while effective, often depend on input modifications, making them detectable and limiting their stealth and scalability. This paper presents Targeted Model Editing (TME), a novel white-box approach that bypasses safety filters by minimally altering internal model structures while preserving the model's intended functionalities. TME identifies and removes safety-critical transformations (SCTs) embedded in model matrices, enabling malicious queries to bypass restrictions without input modifications. By analyzing distinct activation patterns between safe and unsafe queries, TME isolates and approximates SCTs through an optimization process. Implemented in the D-LLM framework, our method achieves an average Attack Success Rate (ASR) of 84.86% on four mainstream open-source LLMs, maintaining high performance. Unlike existing methods, D-LLM eliminates the need for specific triggers or harmful response collections, offering a stealthier and more effective jailbreak strategy. This work reveals a covert and robust threat vector in LLM security and emphasizes the need for stronger safeguards in model safety alignment.

[Arxiv](https://arxiv.org/abs/2412.08201)