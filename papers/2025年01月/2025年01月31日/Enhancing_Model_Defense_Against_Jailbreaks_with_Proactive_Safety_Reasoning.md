# 利用主动安全推理提升模型抵御越狱攻击的能力

发布时间：2025年01月31日

`LLM应用

理由：该论文主要讨论了如何利用大型语言模型（LLMs）的增强推理能力来防御越狱威胁，并提出了一种新的防御策略——安全思维链（SCoT）。这属于LLM在实际应用中的改进和优化，因此归类为LLM应用。` `人工智能` `网络安全`

> Enhancing Model Defense Against Jailbreaks with Proactive Safety Reasoning

# 摘要

> 大型语言模型（LLMs）在众多应用中扮演着关键角色，但它们仍面临越狱威胁，可能导致生成不当内容。传统的防御手段，如拒绝和对抗训练，往往难以应对边缘情况或罕见领域，使得LLMs依然易受复杂攻击。我们提出了一种创新防御策略——安全思维链（SCoT），它利用LLMs的增强推理能力，主动评估有害输入，而非简单阻止。SCoT通过增强拒绝训练数据集，在生成答案前深入分析每个请求的意图。这种主动推理方式提升了LLMs在面对安全对齐语料库未涵盖的有害查询和场景时的泛化能力，并生成详细拒绝说明，明确指出违规之处。对比评估显示，SCoT显著优于现有防御方法，有效降低了对分布外问题和对抗性操纵的脆弱性，同时保持了强大的通用能力。

> Large language models (LLMs) are vital for a wide range of applications yet remain susceptible to jailbreak threats, which could lead to the generation of inappropriate responses. Conventional defenses, such as refusal and adversarial training, often fail to cover corner cases or rare domains, leaving LLMs still vulnerable to more sophisticated attacks. We propose a novel defense strategy, Safety Chain-of-Thought (SCoT), which harnesses the enhanced \textit{reasoning capabilities} of LLMs for proactive assessment of harmful inputs, rather than simply blocking them. SCoT augments any refusal training datasets to critically analyze the intent behind each request before generating answers. By employing proactive reasoning, SCoT enhances the generalization of LLMs across varied harmful queries and scenarios not covered in the safety alignment corpus. Additionally, it generates detailed refusals specifying the rules violated. Comparative evaluations show that SCoT significantly surpasses existing defenses, reducing vulnerability to out-of-distribution issues and adversarial manipulations while maintaining strong general capabilities.

[Arxiv](https://arxiv.org/abs/2501.19180)