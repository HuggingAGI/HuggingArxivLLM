# # 当安全检测器失效时：利用隐写术对大型语言模型实施隐蔽越狱攻击

发布时间：2025年05月22日

`LLM应用` `人工智能安全` `网络安全`

> When Safety Detectors Aren't Enough: A Stealthy and Effective Jailbreak Attack on LLMs via Steganographic Techniques

# 摘要

> 越狱攻击对大型语言模型（LLMs）构成了严重威胁，它们通过绕过内置安全机制，导致有害输出。研究这些攻击对于识别模型漏洞和提升安全性至关重要。本文从“隐秘性”这一新颖视角，系统性地综述了越狱方法。我们发现现有攻击手段难以同时实现“有害隐秘性”（隐藏有害内容）和“语言隐秘性”（保持语言自然性）。基于此，我们提出了StegoAttack——一种完全隐秘的越狱攻击方法。该方法采用隐写术，将恶意查询隐藏于良性且语义连贯的文本中。随后，攻击通过提示LLM提取隐藏查询，并以加密方式回应。此方法有效隐藏恶意意图，同时保持自然性，可规避内置及外部安全机制。我们在主要供应商的四个安全对齐LLMs上评估了StegoAttack，并将其与八种最先进方法进行基准测试。StegoAttack实现了92.00%的平均攻击成功率（ASR），较最强基线高出11.0%。即使在外部检测（如Llama Guard）下，其ASR下降不足1%。此外，它在隐秘性检测指标上取得了最优综合得分，充分展现了其高效性和卓越的隐秘能力。代码可在https://anonymous.4open.science/r/StegoAttack-Jail66获取。


> Jailbreak attacks pose a serious threat to large language models (LLMs) by bypassing built-in safety mechanisms and leading to harmful outputs. Studying these attacks is crucial for identifying vulnerabilities and improving model security. This paper presents a systematic survey of jailbreak methods from the novel perspective of stealth. We find that existing attacks struggle to simultaneously achieve toxic stealth (concealing toxic content) and linguistic stealth (maintaining linguistic naturalness). Motivated by this, we propose StegoAttack, a fully stealthy jailbreak attack that uses steganography to hide the harmful query within benign, semantically coherent text. The attack then prompts the LLM to extract the hidden query and respond in an encrypted manner. This approach effectively hides malicious intent while preserving naturalness, allowing it to evade both built-in and external safety mechanisms. We evaluate StegoAttack on four safety-aligned LLMs from major providers, benchmarking against eight state-of-the-art methods. StegoAttack achieves an average attack success rate (ASR) of 92.00%, outperforming the strongest baseline by 11.0%. Its ASR drops by less than 1% even under external detection (e.g., Llama Guard). Moreover, it attains the optimal comprehensive scores on stealth detection metrics, demonstrating both high efficacy and exceptional stealth capabilities. The code is available at https://anonymous.4open.science/r/StegoAttack-Jail66

[Arxiv](https://arxiv.org/abs/2505.16765)