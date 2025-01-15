# 文本扩散红队测试：通过邻近约束揭示大型语言模型的有害行为

发布时间：2025年01月14日

`LLM应用

理由：这篇论文主要讨论了如何利用自动化红队测试方法来检测大型语言模型（LLM）的漏洞，并提出了一种新的红队方法DART。该研究聚焦于LLM在实际应用中的安全性评估，属于LLM在实际场景中的应用研究，因此应归类为LLM应用。` `网络安全` `人工智能`

> Text-Diffusion Red-Teaming of Large Language Models: Unveiling Harmful Behaviors with Proximity Constraints

# 摘要

> # 摘要
近期研究提出了自动化红队测试方法，用于检测目标大型语言模型（LLM）的漏洞。这些方法利用红队LLM来揭示导致目标LLM产生有害行为的输入。本文探讨了实现针对性安全评估的红队策略，并提出了一种带有邻近约束的优化框架，要求发现的提示与给定数据集中的参考提示相似。该数据集作为提示模板，将测试用例的搜索范围限定在特定主题、写作风格或有害行为类型上。我们发现，现有的自回归模型在此场景下表现不佳，因此提出了一种受文本扩散模型启发的黑盒红队方法：DART（用于审计和红队的扩散）。DART通过在嵌入空间中扰动参考提示，直接控制变化量，从而修改提示。我们通过对比基于模型微调及零-shot和少-shot提示的现有方法，系统评估了DART的有效性。结果表明，DART在发现与参考提示接近的有害输入方面表现显著优于现有方法。

> Recent work has proposed automated red-teaming methods for testing the vulnerabilities of a given target large language model (LLM). These methods use red-teaming LLMs to uncover inputs that induce harmful behavior in a target LLM. In this paper, we study red-teaming strategies that enable a targeted security assessment. We propose an optimization framework for red-teaming with proximity constraints, where the discovered prompts must be similar to reference prompts from a given dataset. This dataset serves as a template for the discovered prompts, anchoring the search for test-cases to specific topics, writing styles, or types of harmful behavior. We show that established auto-regressive model architectures do not perform well in this setting. We therefore introduce a black-box red-teaming method inspired by text-diffusion models: Diffusion for Auditing and Red-Teaming (DART). DART modifies the reference prompt by perturbing it in the embedding space, directly controlling the amount of change introduced. We systematically evaluate our method by comparing its effectiveness with established methods based on model fine-tuning and zero- and few-shot prompting. Our results show that DART is significantly more effective at discovering harmful inputs in close proximity to the reference prompt.

[Arxiv](https://arxiv.org/abs/2501.08246)