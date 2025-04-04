# # ERPO: 通过优化事前推理偏好，提升安全对齐

发布时间：2025年04月03日

`LLM应用` `人工智能安全` `人工智能`

> ERPO: Advancing Safety Alignment via Ex-Ante Reasoning Preference Optimization

# 摘要

> 大型语言模型的最新进展加速了通用人工智能的发展，但其生成有害内容的潜在风险带来了严峻的安全挑战。现有的对齐方法往往难以覆盖多样化的安全场景，且容易受到对抗攻击。本研究提出了一种名为事前推理偏好优化（ERPO）的新颖安全对齐框架，通过思维链赋予模型明确的事前推理能力，并通过嵌入预定义的安全规则为安全判断提供清晰依据。具体而言，我们的方法包含三个阶段：首先，通过构建的推理模块进行有监督微调（SFT）为模型赋予事前推理能力；其次，通过直接偏好优化（DPO）提升安全性、实用性和效率；最后，通过长度控制的迭代偏好优化策略降低推理延迟。在多个开源大型语言模型上的实验表明，ERPO显著提升了安全性能，同时保持了响应效率。

> Recent advancements in large language models (LLMs) have accelerated progress toward artificial general intelligence, yet their potential to generate harmful content poses critical safety challenges. Existing alignment methods often struggle to cover diverse safety scenarios and remain vulnerable to adversarial attacks. In this work, we propose Ex-Ante Reasoning Preference Optimization (ERPO), a novel safety alignment framework that equips LLMs with explicit preemptive reasoning through Chain-of-Thought and provides clear evidence for safety judgments by embedding predefined safety rules. Specifically, our approach consists of three stages: first, equipping the model with Ex-Ante reasoning through supervised fine-tuning (SFT) using a constructed reasoning module; second, enhancing safety, usefulness, and efficiency via Direct Preference Optimization (DPO); and third, mitigating inference latency with a length-controlled iterative preference optimization strategy. Experiments on multiple open-source LLMs demonstrate that ERPO significantly enhances safety performance while maintaining response efficiency.

[Arxiv](https://arxiv.org/abs/2504.02725)