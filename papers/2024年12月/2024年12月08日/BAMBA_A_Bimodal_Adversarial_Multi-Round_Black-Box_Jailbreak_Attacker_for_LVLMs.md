# BAMBA：一种针对 LVLMs 的双模态对抗多轮黑盒越狱攻击者

发布时间：2024年12月08日

`LLM应用` `人工智能` `网络安全`

> BAMBA: A Bimodal Adversarial Multi-Round Black-Box Jailbreak Attacker for LVLMs

# 摘要

> LVLMs 应用广泛，然而在越狱攻击下易产生非法或不道德的回应。要让它们在现实应用中得以负责地部署，搞清楚其脆弱性很关键。当下工作存在四大问题：单轮攻击的局限性、双模态协同不够、对黑箱模型的可迁移性差以及依赖提示工程。为应对这些局限，我们提出 BAMBA，这是针对 LVLMs 的双模态对抗多轮黑箱越狱攻击者。我们先是利用图像优化器从有害语料库中学习恶意特征，接着通过双模态优化器借助文本 - 图像交互来深化这些特征，生成用于越狱的对抗性文本和图像。在各类 LVLMs 和数据集上的实验表明，BAMBA 比其他基线表现更优。

> LVLMs are widely used but vulnerable to illegal or unethical responses under jailbreak attacks. To ensure their responsible deployment in real-world applications, it is essential to understand their vulnerabilities. There are four main issues in current work: single-round attack limitation, insufficient dual-modal synergy, poor transferability to black-box models, and reliance on prompt engineering. To address these limitations, we propose BAMBA, a bimodal adversarial multi-round black-box jailbreak attacker for LVLMs. We first use an image optimizer to learn malicious features from a harmful corpus, then deepen these features through a bimodal optimizer through text-image interaction, generating adversarial text and image for jailbreak. Experiments on various LVLMs and datasets demonstrate that BAMBA outperforms other baselines.

[Arxiv](https://arxiv.org/abs/2412.05892)