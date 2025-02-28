# R1-T1：通过推理学习，全面激发大型语言模型的翻译能力

发布时间：2025年02月26日

`LLM应用

摘要讨论了将推理过程融入大型语言模型以提升机器翻译的效果，属于具体的应用领域创新，因此归类为LLM应用。` `机器翻译`

> R1-T1: Fully Incentivizing Translation Capability in LLMs via Reasoning Learning

# 摘要

> 尽管近期在推理增强型大型语言模型（如DeepSeek-R1）方面取得了突破，但在机器翻译（MT）领域，将推理过程融入模型中仍然处于探索阶段。现有方法要么为特定的MT子任务设计固定的链式思维（CoT），要么依赖于与人类思维不一致的合成链式思维和容易遗忘的有监督微调（SFT），这限制了它们在多样化翻译场景中的适应性。本文提出了R1-Translator（R1-T1），一个通过强化学习（RL）实现通用MT推理的新型框架，该框架采用与人类思维一致的六种常见链式思维模式。我们的方法在三个方面实现了创新：

- 将基于推理的翻译扩展到六种语言和多样化任务（如法律/医学领域适配、习语解析）；
- 制定了六种专家整理的链式思维模板，模拟了混合人类策略，如语境感知的改写和反向翻译；
- 通过带有KL约束奖励的强化学习，实现了链式思维的自我进化发现和抗遗忘适应。

实验结果表明，在Flores-101测试集的21种语言和80种翻译方向上，翻译性能稳步提升，尤其在15种未见于训练的语言上表现显著，同时保留了其通用多语言能力，与单纯的SFT相比更具优势。

> Despite recent breakthroughs in reasoning-enhanced large language models (LLMs) like DeepSeek-R1, incorporating inference-time reasoning into machine translation (MT), where human translators naturally employ structured, multi-layered reasoning chain-of-thoughts (CoTs), is yet underexplored. Existing methods either design a fixed CoT tailored for a specific MT sub-task (e.g., literature translation), or rely on synthesizing CoTs unaligned with humans and supervised fine-tuning (SFT) prone to catastrophic forgetting, limiting their adaptability to diverse translation scenarios. This paper introduces R1-Translator (R1-T1), a novel framework to achieve inference-time reasoning for general MT via reinforcement learning (RL) with human-aligned CoTs comprising six common patterns. Our approach pioneers three innovations: (1) extending reasoning-based translation beyond MT sub-tasks to six languages and diverse tasks (e.g., legal/medical domain adaptation, idiom resolution); (2) formalizing six expert-curated CoT templates that mirror hybrid human strategies like context-aware paraphrasing and back translation; and (3) enabling self-evolving CoT discovery and anti-forgetting adaptation through RL with KL-constrained rewards. Experimental results indicate a steady translation performance improvement in 21 languages and 80 translation directions on Flores-101 test set, especially on the 15 languages unseen from training, with its general multilingual abilities preserved compared with plain SFT.

[Arxiv](https://arxiv.org/abs/2502.19735)