# 一模通用：对抗大语言模型的健壮越狱提示生成

发布时间：2025年05月23日

`LLM应用` `人工智能安全`

> One Model Transfer to All: On Robust Jailbreak Prompts Generation against LLMs

# 摘要

> 大型语言模型（LLMs）的安全对齐正日益受到越狱攻击的威胁。这些攻击能够操纵模型生成有害或意外内容，研究它们对于发现模型漏洞至关重要。然而，现有越狱策略往往无法跟上防御机制（如防御后缀）的快速发展，导致其对防御模型效果有限。为此，我们提出了一种名为ArrAttack的新攻击方法，专门针对经过防御的LLMs。

ArrAttack的核心优势在于能够自动生成能够绕过各种防御措施的鲁棒越狱提示。这一能力由一个通用的鲁棒性判断模型提供支持，该模型经过训练后，可对具有多种防御机制的任何目标模型进行鲁棒性评估。通过这一模型，我们能够快速开发出一个高效的恶意输入提示转换器，将其转化为有效的攻击。

大量实验表明，ArrAttack在攻击效果上显著优于现有方法，展现出在白盒和黑盒模型（包括GPT-4和Claude-3）之间的强大可迁移性。我们的工作不仅填补了越狱攻击与防御之间的研究空白，还为生成鲁棒越狱提示提供了全新视角。我们已在GitHub上开源了代码库，地址为https://github.com/LLBao/ArrAttack。

> Safety alignment in large language models (LLMs) is increasingly compromised by jailbreak attacks, which can manipulate these models to generate harmful or unintended content. Investigating these attacks is crucial for uncovering model vulnerabilities. However, many existing jailbreak strategies fail to keep pace with the rapid development of defense mechanisms, such as defensive suffixes, rendering them ineffective against defended models. To tackle this issue, we introduce a novel attack method called ArrAttack, specifically designed to target defended LLMs. ArrAttack automatically generates robust jailbreak prompts capable of bypassing various defense measures. This capability is supported by a universal robustness judgment model that, once trained, can perform robustness evaluation for any target model with a wide variety of defenses. By leveraging this model, we can rapidly develop a robust jailbreak prompt generator that efficiently converts malicious input prompts into effective attacks. Extensive evaluations reveal that ArrAttack significantly outperforms existing attack strategies, demonstrating strong transferability across both white-box and black-box models, including GPT-4 and Claude-3. Our work bridges the gap between jailbreak attacks and defenses, providing a fresh perspective on generating robust jailbreak prompts. We make the codebase available at https://github.com/LLBao/ArrAttack.

[Arxiv](https://arxiv.org/abs/2505.17598)