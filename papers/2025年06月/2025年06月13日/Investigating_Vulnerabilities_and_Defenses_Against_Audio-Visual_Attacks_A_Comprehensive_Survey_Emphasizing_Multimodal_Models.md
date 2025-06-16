# 研究抵御视听攻击的漏洞与防御机制：全面综述：着重探讨多模态模型

发布时间：2025年06月13日

`LLM应用` `多模态`

> Investigating Vulnerabilities and Defenses Against Audio-Visual Attacks: A Comprehensive Survey Emphasizing Multimodal Models

# 摘要

> 多模态大型语言模型（MLLMs）成功跨越了音频-视觉与自然语言处理之间的鸿沟，在多个音频-视觉任务中达到了当前最优的性能水平。尽管MLLMs展现出卓越的能力，但高质量音频-视觉训练数据和计算资源的匮乏，使得研究者不得不依赖第三方数据和开源MLLMs，这一现象在当前研究中日益显著。这种繁荣背后却隐藏着巨大的安全风险。实证研究表明，最新的MLLMs可以被操控以生成恶意或有害内容，这种操控仅通过指令或输入即可实现，包括对抗性扰动和恶意查询，从而有效绕过模型内置的安全机制。为了更深入地理解基于音频-视觉的多模态模型固有的安全漏洞，一系列调查研究了各种类型的攻击，包括对抗攻击和后门攻击。虽然现有的音频-视觉攻击综述提供了全面的概述，但它们仅限于特定类型的攻击，缺乏对各种攻击类型的统一审查。为了解决这一问题并洞察该领域的最新趋势，本文对音频-视觉攻击进行了全面而系统的综述，涵盖对抗攻击、后门攻击和越狱攻击。此外，本文还回顾了最新音频-视觉MLLMs中各种类型的攻击，这一维度在现有综述中明显缺失。基于全面深入的综述，本文概述了未来在音频-视觉攻击与防御研究中所面临的挑战和新兴趋势。

> Multimodal large language models (MLLMs), which bridge the gap between audio-visual and natural language processing, achieve state-of-the-art performance on several audio-visual tasks. Despite the superior performance of MLLMs, the scarcity of high-quality audio-visual training data and computational resources necessitates the utilization of third-party data and open-source MLLMs, a trend that is increasingly observed in contemporary research. This prosperity masks significant security risks. Empirical studies demonstrate that the latest MLLMs can be manipulated to produce malicious or harmful content. This manipulation is facilitated exclusively through instructions or inputs, including adversarial perturbations and malevolent queries, effectively bypassing the internal security mechanisms embedded within the models. To gain a deeper comprehension of the inherent security vulnerabilities associated with audio-visual-based multimodal models, a series of surveys investigates various types of attacks, including adversarial and backdoor attacks. While existing surveys on audio-visual attacks provide a comprehensive overview, they are limited to specific types of attacks, which lack a unified review of various types of attacks. To address this issue and gain insights into the latest trends in the field, this paper presents a comprehensive and systematic review of audio-visual attacks, which include adversarial attacks, backdoor attacks, and jailbreak attacks. Furthermore, this paper also reviews various types of attacks in the latest audio-visual-based MLLMs, a dimension notably absent in existing surveys. Drawing upon comprehensive insights from a substantial review, this paper delineates both challenges and emergent trends for future research on audio-visual attacks and defense.

[Arxiv](https://arxiv.org/abs/2506.11521)