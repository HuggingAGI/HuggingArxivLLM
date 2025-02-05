# 隐形痕迹：利用混合指纹识别技术揭示生成式AI应用中的底层LLMs

发布时间：2025年02月03日

`LLM应用

理由：这篇论文主要讨论了如何通过指纹识别技术来识别大型语言模型（LLMs）的底层机器学习模型，以确保AI集成应用的安全性和透明度。虽然涉及到了多代理系统和模型更新等复杂场景，但核心内容仍然是关于如何在实际应用中识别和监控LLMs，因此应归类为LLM应用。` `人工智能`

> Invisible Traces: Using Hybrid Fingerprinting to identify underlying LLMs in GenAI Apps

# 摘要

> 指纹识别是通过分析AI系统（如大型语言模型，LLMs）的独特特征或模式来识别其底层机器学习（ML）模型的过程，类似于人类指纹。LLMs的指纹识别对于确保AI集成应用的安全性和透明度至关重要。尽管现有方法主要依赖与应用程序的直接交互来推断模型身份，但在涉及多代理系统、频繁模型更新和受限访问模型内部的实际场景中，这些方法往往失效。本文提出了一种新颖的指纹识别框架，通过整合静态和动态指纹识别技术来解决这些挑战。我们的方法能够识别架构特征和行为特征，从而在动态环境中实现准确且稳健的LLMs指纹识别。我们还揭示了传统指纹识别方法无效的新威胁场景，弥合了理论技术与实际应用之间的差距。为了验证框架的有效性，我们设计了一个广泛的评估设置，模拟现实世界条件，并展示了该方法在识别和监控Gen-AI应用中的LLMs方面的卓越表现。结果表明，该框架能够适应多样且不断变化的部署环境。

> Fingerprinting refers to the process of identifying underlying Machine Learning (ML) models of AI Systemts, such as Large Language Models (LLMs), by analyzing their unique characteristics or patterns, much like a human fingerprint. The fingerprinting of Large Language Models (LLMs) has become essential for ensuring the security and transparency of AI-integrated applications. While existing methods primarily rely on access to direct interactions with the application to infer model identity, they often fail in real-world scenarios involving multi-agent systems, frequent model updates, and restricted access to model internals. In this paper, we introduce a novel fingerprinting framework designed to address these challenges by integrating static and dynamic fingerprinting techniques. Our approach identifies architectural features and behavioral traits, enabling accurate and robust fingerprinting of LLMs in dynamic environments. We also highlight new threat scenarios where traditional fingerprinting methods are ineffective, bridging the gap between theoretical techniques and practical application. To validate our framework, we present an extensive evaluation setup that simulates real-world conditions and demonstrate the effectiveness of our methods in identifying and monitoring LLMs in Gen-AI applications. Our results highlight the framework's adaptability to diverse and evolving deployment contexts.

[Arxiv](https://arxiv.org/abs/2501.18712)