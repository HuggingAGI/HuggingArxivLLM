# 多模态 AI 中的视觉错误模式：一种统计手段

发布时间：2024年11月26日

`LLM应用` `人工智能` `多模态语言模型`

> Visual Error Patterns in Multi-Modal AI: A Statistical Approach

# 摘要

> 人工智能（AI）在诸多领域取得了变革性成就，给医疗、教育、人机交互等领域带来了革命性变化。然而，驱动 AI 性能的机制通常不为人知，在大型语言模型（LLMs）方面尤其如此，近年来其发展速度空前。像 GPT-4o 这类多模态大型语言模型（MLLMs）就是这种发展的典型代表，它整合了文本、音频和视觉输入，实现了不同领域的交互。尽管这些模型能力出众，但很大程度上仍是“黑箱”，对于其内部如何处理多模态信息，人们知之甚少。这种不透明性带来了诸多重大挑战，如系统性偏差、错误关联和意外行为等，需要深入研究。理解 MLLMs 的决策过程，对于减轻这些挑战以及确保其在关键应用中的可靠部署，既有益又必要。本研究之所以聚焦 GPT-4o，是因其先进的多模态能力，能够同时处理文本和视觉信息，这使其成为探究机器驱动和人类驱动的视觉感知之间异同的理想模型。虽然 GPT-4o 在处理涉及结构化和完整数据的任务时表现出色，但其依赖自下而上的处理方式（即对感官输入进行逐个特征分析），在解读复杂或模糊的刺激时面临挑战。这一局限与人类视觉形成鲜明对比，人类视觉通过高级认知过程，在解决模糊性和重构不完整信息方面表现卓越。

> Artificial Intelligence (AI) has achieved transformative success across a wide range of domains, revolutionizing fields such as healthcare, education, and human-computer interaction. However, the mechanisms driving AI's performance often remain opaque, particularly in the context of large language models (LLMs), which have advanced at an unprecedented pace in recent years. Multi-modal large language models (MLLMs) like GPT-4o exemplify this evolution, integrating text, audio, and visual inputs to enable interaction across diverse domains. Despite their remarkable capabilities, these models remain largely "black boxes," offering limited insight into how they process multi-modal information internally. This lack of transparency poses significant challenges, including systematic biases, flawed associations, and unintended behaviors, which require careful investigation. Understanding the decision-making processes of MLLMs is both beneficial and essential for mitigating these challenges and ensuring their reliable deployment in critical applications. GPT-4o was chosen as the focus of this study for its advanced multi-modal capabilities, which allow simultaneous processing of textual and visual information. These capabilities make it an ideal model for investigating the parallels and distinctions between machine-driven and human-driven visual perception. While GPT-4o performs effectively in tasks involving structured and complete data, its reliance on bottom-up processing, which involves a feature-by-feature analysis of sensory inputs, presents challenges when interpreting complex or ambiguous stimuli. This limitation contrasts with human vision, which is remarkably adept at resolving ambiguity and reconstructing incomplete information through high-level cognitive processes.

[Arxiv](https://arxiv.org/abs/2412.00083)