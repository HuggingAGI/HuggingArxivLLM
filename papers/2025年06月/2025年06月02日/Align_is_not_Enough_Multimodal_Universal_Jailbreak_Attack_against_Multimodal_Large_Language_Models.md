# 对齐不够：针对多模态大型语言模型的多模态通用越狱攻击

发布时间：2025年06月02日

`LLM应用` `模型安全` `多模态`

> Align is not Enough: Multimodal Universal Jailbreak Attack against Multimodal Large Language Models

# 摘要

> 大型语言模型（LLMs）已发展成为多模态大型语言模型（MLLMs），通过整合视觉信息和其他类型的数据，显著提升了其能力，使其更贴近人类智能的多模态处理特性。尽管取得了进展，但这些模型生成不 desirable 内容的问题依然严峻，特别是文本基的 jailbreak 攻击暴露了其脆弱性，对现有安全协议构成了重大挑战。鉴于多模态整合为 MLLMs 带来的独特安全风险，我们提出了一种统一的多模态通用 jailbreak 攻击框架，利用迭代的图像-文本互动和基于迁移的策略，生成通用的对抗后缀和图像。我们的研究不仅揭示了图像-文本模态的互动可作为关键漏洞，还证实了多模态通用 jailbreak 攻击能在不同 MLLMs 中引发更高质量的不 desirable 生成。通过评估 LLaVA、Yi-VL、MiniGPT4、MiniGPT-v2 和 InstructBLIP 等 MLLMs 的不 desirable 上下文生成，我们揭示了显著的多模态安全对齐问题，凸显了现有安全机制在应对复杂多模态攻击时的不足。这项研究强调了在 MLLMs 中建立稳健安全措施的迫切需求，呼吁对安全协议进行全面审查和增强，以缓解多模态能力相关的潜在风险。

> Large Language Models (LLMs) have evolved into Multimodal Large Language Models (MLLMs), significantly enhancing their capabilities by integrating visual information and other types, thus aligning more closely with the nature of human intelligence, which processes a variety of data forms beyond just text. Despite advancements, the undesirable generation of these models remains a critical concern, particularly due to vulnerabilities exposed by text-based jailbreak attacks, which have represented a significant threat by challenging existing safety protocols. Motivated by the unique security risks posed by the integration of new and old modalities for MLLMs, we propose a unified multimodal universal jailbreak attack framework that leverages iterative image-text interactions and transfer-based strategy to generate a universal adversarial suffix and image. Our work not only highlights the interaction of image-text modalities can be used as a critical vulnerability but also validates that multimodal universal jailbreak attacks can bring higher-quality undesirable generations across different MLLMs. We evaluate the undesirable context generation of MLLMs like LLaVA, Yi-VL, MiniGPT4, MiniGPT-v2, and InstructBLIP, and reveal significant multimodal safety alignment issues, highlighting the inadequacy of current safety mechanisms against sophisticated multimodal attacks. This study underscores the urgent need for robust safety measures in MLLMs, advocating for a comprehensive review and enhancement of security protocols to mitigate potential risks associated with multimodal capabilities.

[Arxiv](https://arxiv.org/abs/2506.01307)