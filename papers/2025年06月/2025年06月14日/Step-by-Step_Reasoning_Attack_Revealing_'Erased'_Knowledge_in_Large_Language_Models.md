# 一步步推理攻击：揭露大型语言模型中被隐藏的知识

发布时间：2025年06月14日

`LLM理论` `法律合规` `隐私保护`

> Step-by-Step Reasoning Attack: Revealing 'Erased' Knowledge in Large Language Models

# 摘要

> 大型语言模型中的知识擦除对于确保符合数据和AI法规、保护用户隐私、缓解偏见和错误信息至关重要。现有的遗忘方法旨在通过移除特定知识同时保持整体模型性能，使知识擦除过程更高效和有效，特别是在保留信息方面。然而，观察发现，遗忘技术往往抑制知识并使其隐藏在表面之下，因此可以通过适当的提示重新检索。在本研究中，我们证明逐步推理可以作为恢复这些隐藏信息的后门。我们引入了一种基于逐步推理的黑盒攻击方法Sleek，系统地揭示遗忘失败的情况。我们的攻击框架包含三个核心组件：(1) 利用基于LLM生成查询构建的逐步推理策略生成对抗提示，(2) 成功召回被擦除内容并暴露本应保留知识的不公平抑制的攻击机制，(3) 将提示分类为直接、间接和暗示，以识别哪些查询类型最能利用遗忘漏洞。通过在四种最先进的遗忘技术和两种广泛使用的LLM上的广泛评估，我们表明现有方法无法确保可靠的知识移除。在生成的对抗提示中，62.5%成功检索到被遗忘的哈利波特事实，而50%揭示了对保留知识的不公平抑制。我们的工作突显了信息泄露的持续风险，强调了需要更强大的遗忘策略来确保擦除效果。

> Knowledge erasure in large language models (LLMs) is important for ensuring compliance with data and AI regulations, safeguarding user privacy, mitigating bias, and misinformation. Existing unlearning methods aim to make the process of knowledge erasure more efficient and effective by removing specific knowledge while preserving overall model performance, especially for retained information. However, it has been observed that the unlearning techniques tend to suppress and leave the knowledge beneath the surface, thus making it retrievable with the right prompts. In this work, we demonstrate that \textit{step-by-step reasoning} can serve as a backdoor to recover this hidden information. We introduce a step-by-step reasoning-based black-box attack, Sleek, that systematically exposes unlearning failures. We employ a structured attack framework with three core components: (1) an adversarial prompt generation strategy leveraging step-by-step reasoning built from LLM-generated queries, (2) an attack mechanism that successfully recalls erased content, and exposes unfair suppression of knowledge intended for retention and (3) a categorization of prompts as direct, indirect, and implied, to identify which query types most effectively exploit unlearning weaknesses. Through extensive evaluations on four state-of-the-art unlearning techniques and two widely used LLMs, we show that existing approaches fail to ensure reliable knowledge removal. Of the generated adversarial prompts, 62.5% successfully retrieved forgotten Harry Potter facts from WHP-unlearned Llama, while 50% exposed unfair suppression of retained knowledge. Our work highlights the persistent risks of information leakage, emphasizing the need for more robust unlearning strategies for erasure.

[Arxiv](https://arxiv.org/abs/2506.17279)