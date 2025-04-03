# PiCo：突破多模态大型语言模型的限制——图像代码上下文化方法

发布时间：2025年04月02日

`LLM应用` `AI安全` `代码安全`

> PiCo: Jailbreaking Multimodal Large Language Models via $\textbf{Pi}$ctorial $\textbf{Co}$de Contextualization

# 摘要

> 多模态大型语言模型（MLLMs）通过整合视觉和其他模态显著提升了AI的能力，但也带来了新的安全风险。我们提出了一种名为PiCo的新颖越狱框架，它通过分层策略利用视觉模态的漏洞和代码训练数据的特性，逐步突破MLLMs的多层级防御。PiCo采用基于token的字体攻击来绕过输入过滤，并在编程指令中嵌入恶意意图以规避运行时监控。为全面评估攻击效果，我们还提出了一种新指标，用于衡量模型在攻击后输出的毒性及有用性。实验显示，PiCo在Gemini-Pro Vision和GPT-4上的平均攻击成功率分别达到84.13%和52.66%，超越了现有方法。这些结果突显了当前防御机制的不足，强调了为保护MLLMs开发更 robust 安全策略的必要性。

> Multimodal Large Language Models (MLLMs), which integrate vision and other modalities into Large Language Models (LLMs), significantly enhance AI capabilities but also introduce new security vulnerabilities. By exploiting the vulnerabilities of the visual modality and the long-tail distribution characteristic of code training data, we present PiCo, a novel jailbreaking framework designed to progressively bypass multi-tiered defense mechanisms in advanced MLLMs. PiCo employs a tier-by-tier jailbreak strategy, using token-level typographic attacks to evade input filtering and embedding harmful intent within programming context instructions to bypass runtime monitoring. To comprehensively assess the impact of attacks, a new evaluation metric is further proposed to assess both the toxicity and helpfulness of model outputs post-attack. By embedding harmful intent within code-style visual instructions, PiCo achieves an average Attack Success Rate (ASR) of 84.13% on Gemini-Pro Vision and 52.66% on GPT-4, surpassing previous methods. Experimental results highlight the critical gaps in current defenses, underscoring the need for more robust strategies to secure advanced MLLMs.

[Arxiv](https://arxiv.org/abs/2504.01444)