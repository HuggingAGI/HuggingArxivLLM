# 基于预填的越狱：突破大型语言模型安全边界的创新方法

发布时间：2025年04月28日

`LLM应用` `模型安全` `攻击方法`

> Prefill-Based Jailbreak: A Novel Approach of Bypassing LLM Safety Boundary

# 摘要

> 大型语言模型（LLMs）旨在生成有益且安全的内容，但对抗攻击（即越狱攻击）可能绕过其安全机制，诱导模型生成有害内容或泄露敏感信息。因此，研究越狱攻击方法对于揭示LLMs的系统性漏洞至关重要，并为开发者持续改进安全措施提供指导。本文提出了一种基于LLMs预填功能的新型越狱攻击方法。与传统越狱方法不同，本方法通过直接操纵后续标记的概率分布，绕过模型的安全机制，从而控制输出。我们提出了两种攻击变体：静态预填（SP），采用通用预填文本；以及优化预填（OP），通过迭代优化预填文本以提升攻击成功率。实验结果表明，在AdvBench基准上，针对六种先进LLMs，本方法显著提升了攻击成功率。其中，OP方法在某些模型上实现了高达99.82%的成功率，远超基线方法。这项研究揭示了预填功能的潜在安全风险，强调了建立强大内容验证机制的重要性。本文所有代码和数据均公开可用。

> Large Language Models (LLMs) are designed to generate helpful and safe content. However, adversarial attacks, commonly referred to as jailbreak, can bypass their safety protocols, prompting LLMs to generate harmful content or reveal sensitive data. Consequently, investigating jailbreak methodologies is crucial for exposing systemic vulnerabilities within LLMs, ultimately guiding the continuous implementation of security enhancements by developers. In this paper, we introduce a novel jailbreak attack method that leverages the prefilling feature of LLMs, a feature designed to enhance model output constraints. Unlike traditional jailbreak methods, the proposed attack circumvents LLMs' safety mechanisms by directly manipulating the probability distribution of subsequent tokens, thereby exerting control over the model's output. We propose two attack variants: Static Prefilling (SP), which employs a universal prefill text, and Optimized Prefilling (OP), which iteratively optimizes the prefill text to maximize the attack success rate. Experiments on six state-of-the-art LLMs using the AdvBench benchmark validate the effectiveness of our method and demonstrate its capability to substantially enhance attack success rates when combined with existing jailbreak approaches. The OP method achieved attack success rates of up to 99.82% on certain models, significantly outperforming baseline methods. This work introduces a new jailbreak attack method in LLMs, emphasizing the need for robust content validation mechanisms to mitigate the adversarial exploitation of prefilling features. All code and data used in this paper are publicly available.

[Arxiv](https://arxiv.org/abs/2504.21038)