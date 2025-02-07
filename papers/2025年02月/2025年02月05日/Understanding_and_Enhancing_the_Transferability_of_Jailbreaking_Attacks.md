# 理解与提升越狱攻击的可迁移性

发布时间：2025年02月05日

`LLM理论

理由：这篇论文主要探讨了越狱攻击对大型语言模型（LLMs）意图感知的影响，并提出了感知重要性扁平化（PiF）方法来提高专有LLMs的安全性。研究内容涉及LLMs的内部机制和对抗性攻击的理论分析，属于对LLMs的理论研究，因此分类为LLM理论。` `网络安全` `人工智能`

> Understanding and Enhancing the Transferability of Jailbreaking Attacks

# 摘要

> # 摘要
越狱攻击能够有效操纵开源的大型语言模型（LLMs）生成有害响应，但其迁移性有限，难以持续破坏专有LLMs。为了可靠识别专有LLMs的漏洞，本研究通过分析越狱攻击对模型意图感知的影响，探讨了其迁移性。通过引入对抗性序列，这些攻击能够转移源LLM对原始输入中恶意意图标记的注意力，阻碍其意图识别并引发有害响应。然而，这些对抗性序列无法误导目标LLM的意图感知，使其能够重新聚焦于恶意意图标记并避免响应。我们的分析进一步揭示了对抗性序列中固有的分布依赖性，其有效性源于对源LLM参数的过拟合，导致对目标LLMs的迁移性有限。为此，我们提出了感知重要性扁平化（PiF）方法，该方法将模型的注意力均匀分散到原始输入中的中性意图标记上，从而在不依赖过拟合对抗性序列的情况下掩盖恶意意图标记。大量实验表明，PiF为专有LLMs提供了高效且有效的红队评估。

> Jailbreaking attacks can effectively manipulate open-source large language models (LLMs) to produce harmful responses. However, these attacks exhibit limited transferability, failing to disrupt proprietary LLMs consistently. To reliably identify vulnerabilities in proprietary LLMs, this work investigates the transferability of jailbreaking attacks by analysing their impact on the model's intent perception. By incorporating adversarial sequences, these attacks can redirect the source LLM's focus away from malicious-intent tokens in the original input, thereby obstructing the model's intent recognition and eliciting harmful responses. Nevertheless, these adversarial sequences fail to mislead the target LLM's intent perception, allowing the target LLM to refocus on malicious-intent tokens and abstain from responding. Our analysis further reveals the inherent distributional dependency within the generated adversarial sequences, whose effectiveness stems from overfitting the source LLM's parameters, resulting in limited transferability to target LLMs. To this end, we propose the Perceived-importance Flatten (PiF) method, which uniformly disperses the model's focus across neutral-intent tokens in the original input, thus obscuring malicious-intent tokens without relying on overfitted adversarial sequences. Extensive experiments demonstrate that PiF provides an effective and efficient red-teaming evaluation for proprietary LLMs.

[Arxiv](https://arxiv.org/abs/2502.03052)