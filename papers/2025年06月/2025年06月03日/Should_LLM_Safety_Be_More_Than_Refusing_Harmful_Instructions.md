# # LLM 安全性：仅仅拒绝有害指令就够了吗？

发布时间：2025年06月03日

`LLM理论`

> Should LLM Safety Be More Than Refusing Harmful Instructions?

# 摘要

> 本文系统性地评估了大型语言模型 (LLMs) 在处理长尾分布的加密文本时的行为及其安全性影响。我们提出了一个二维安全评估框架：(1) 指令拒绝能力，即模型识别并拒绝有害加密指令的能力；(2) 生成安全性，即模型抑制生成潜在有害内容的能力。通过全面实验，我们发现具备解密能力的模型可能面临泛化不匹配攻击：其安全机制在至少一个维度上失效，导致产生不安全响应或过度拒绝。基于这些发现，我们评估了多种 LLM 之前和之后的安全防护措施，并探讨了它们的优缺点。这项研究有助于深入理解 LLM 在长尾文本场景下的安全性，并为开发更健壮的安全机制提供了指导方向。

> This paper presents a systematic evaluation of Large Language Models' (LLMs) behavior on long-tail distributed (encrypted) texts and their safety implications. We introduce a two-dimensional framework for assessing LLM safety: (1) instruction refusal-the ability to reject harmful obfuscated instructions, and (2) generation safety-the suppression of generating harmful responses. Through comprehensive experiments, we demonstrate that models that possess capabilities to decrypt ciphers may be susceptible to mismatched-generalization attacks: their safety mechanisms fail on at least one safety dimension, leading to unsafe responses or over-refusal. Based on these findings, we evaluate a number of pre-LLM and post-LLM safeguards and discuss their strengths and limitations. This work contributes to understanding the safety of LLM in long-tail text scenarios and provides directions for developing robust safety mechanisms.

[Arxiv](https://arxiv.org/abs/2506.02442)