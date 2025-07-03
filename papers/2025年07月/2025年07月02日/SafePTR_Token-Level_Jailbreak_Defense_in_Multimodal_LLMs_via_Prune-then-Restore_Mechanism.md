# # SafePTR: 通过剪裁后恢复机制实现的多模态大语言模型token级别越狱防御

发布时间：2025年07月02日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型的安全漏洞及其防御方法，属于将LLM应用于实际场景并解决具体问题的范畴，因此归类为LLM应用。` `人工智能安全` `多模态模型`

> SafePTR: Token-Level Jailbreak Defense in Multimodal LLMs via Prune-then-Restore Mechanism

# 摘要

> 多模态大型语言模型（MLLMs）通过整合视觉输入扩展了 LLMs 的能力，使其支持视觉推理。然而，这种整合也带来了新的漏洞，使 MLLMs 易受多模态越狱攻击，阻碍了其安全部署。现有的防御方法，如图像到文本翻译、安全提示和多模态安全微调，试图通过将多模态输入与 LLMs 内置的安全措施对齐来解决问题。然而，这些方法未能揭示多模态漏洞的根本原因，特别是有害的多模态令牌如何触发 MLLMs 的越狱行为。因此，它们仍然容易受到文本驱动的多模态越狱攻击，通常表现出过度防御的行为，并带来了沉重的训练开销。

为了解决这一问题，我们对有害的多模态令牌在 MLLMs 中如何、何时以及哪些能够绕过安全措施进行了全面分析。令人惊讶的是，我们发现早期到中层的不到 1% 的令牌负责诱发不安全行为，这表明精确移除一小部分有害令牌（无需进行安全微调）仍能有效提高抵御越狱攻击的安全性。受到这一发现的启发，我们提出了 Safe Prune-then-Restore（SafePTR），这是一种无需训练的防御框架。它通过在易受攻击的层选择性地修剪有害令牌，同时在后续层恢复良性特征，从而显著提升了 MLLMs 的安全性，同时保持了效率。无需额外的计算开销，SafePTR 在不损害实用性的同时，达到了缓解越狱风险的最先进性能。

> By incorporating visual inputs, Multimodal Large Language Models (MLLMs) extend LLMs to support visual reasoning. However, this integration also introduces new vulnerabilities, making MLLMs susceptible to multimodal jailbreak attacks and hindering their safe deployment.Existing defense methods, including Image-to-Text Translation, Safe Prompting, and Multimodal Safety Tuning, attempt to address this by aligning multimodal inputs with LLMs' built-in safeguards.Yet, they fall short in uncovering root causes of multimodal vulnerabilities, particularly how harmful multimodal tokens trigger jailbreak in MLLMs? Consequently, they remain vulnerable to text-driven multimodal jailbreaks, often exhibiting overdefensive behaviors and imposing heavy training overhead.To bridge this gap, we present an comprehensive analysis of where, how and which harmful multimodal tokens bypass safeguards in MLLMs. Surprisingly, we find that less than 1% tokens in early-middle layers are responsible for inducing unsafe behaviors, highlighting the potential of precisely removing a small subset of harmful tokens, without requiring safety tuning, can still effectively improve safety against jailbreaks. Motivated by this, we propose Safe Prune-then-Restore (SafePTR), an training-free defense framework that selectively prunes harmful tokens at vulnerable layers while restoring benign features at subsequent layers.Without incurring additional computational overhead, SafePTR significantly enhances the safety of MLLMs while preserving efficiency. Extensive evaluations across three MLLMs and five benchmarks demonstrate SafePTR's state-of-the-art performance in mitigating jailbreak risks without compromising utility.

[Arxiv](https://arxiv.org/abs/2507.01513)