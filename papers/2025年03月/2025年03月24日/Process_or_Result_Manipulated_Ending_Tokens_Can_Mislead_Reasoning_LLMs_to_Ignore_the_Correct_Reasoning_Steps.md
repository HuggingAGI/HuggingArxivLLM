# 过程还是结果？操控结尾标记，可能会误导推理型 LLM 忽略正确的推理步骤。

发布时间：2025年03月24日

`LLM理论` `人工智能` `模型安全`

> Process or Result? Manipulated Ending Tokens Can Mislead Reasoning LLMs to Ignore the Correct Reasoning Steps

# 摘要

> 近期，推理型大型语言模型（LLMs）通过长链式思维链在数学推理能力上取得显著提升，其推理标记赋予了自我修正能力，从而增强了整体的鲁棒性。这激发了我们的研究兴趣：推理型LLMs在面对输入推理链中的细微错误时，究竟有多脆弱？我们提出了“妥协思维”（CPT）这一概念，即当模型接收到包含篡改计算结果的推理标记时，往往忽视正确推理步骤，转而采用错误结果。通过在多个推理型LLMs上进行系统性评估，我们设计了三种逐渐明确的提示方法来衡量CPT抗性，发现模型在识别和纠正这些篡改方面存在显著困难。值得注意的是，与现有研究认为结构改动对模型性能的影响更大不同，我们发现局部结尾标记的篡改对推理结果的影响远大于结构改动。此外，我们还发现DeepSeek-R1中存在一个安全漏洞，即被篡改的推理标记会导致推理完全停止。本研究不仅加深了我们对推理鲁棒性的理解，还强调了推理密集型应用中的安全考量。

> Recent reasoning large language models (LLMs) have demonstrated remarkable improvements in mathematical reasoning capabilities through long Chain-of-Thought. The reasoning tokens of these models enable self-correction within reasoning chains, enhancing robustness. This motivates our exploration: how vulnerable are reasoning LLMs to subtle errors in their input reasoning chains? We introduce "Compromising Thought" (CPT), a vulnerability where models presented with reasoning tokens containing manipulated calculation results tend to ignore correct reasoning steps and adopt incorrect results instead. Through systematic evaluation across multiple reasoning LLMs, we design three increasingly explicit prompting methods to measure CPT resistance, revealing that models struggle significantly to identify and correct these manipulations. Notably, contrary to existing research suggesting structural alterations affect model performance more than content modifications, we find that local ending token manipulations have greater impact on reasoning outcomes than structural changes. Moreover, we discover a security vulnerability in DeepSeek-R1 where tampered reasoning tokens can trigger complete reasoning cessation. Our work enhances understanding of reasoning robustness and highlights security considerations for reasoning-intensive applications.

[Arxiv](https://arxiv.org/abs/2503.19326)