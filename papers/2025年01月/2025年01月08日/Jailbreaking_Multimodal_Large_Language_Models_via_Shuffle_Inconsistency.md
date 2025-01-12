# 利用洗牌不一致性破解多模态大型语言模型

发布时间：2025年01月08日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）在商业应用中的安全问题，特别是越狱攻击及其防御机制。论文提出了一种新的攻击方法（SI-Attack），并展示了其在商业MLLMs上的应用效果。因此，这篇论文属于LLM应用类别，因为它关注的是如何在实际应用中改进和评估LLM的安全性。` `人工智能` `网络安全`

> Jailbreaking Multimodal Large Language Models via Shuffle Inconsistency

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）在商业应用中表现出色并已广泛应用，但其安全机制仍存在潜在漏洞。越狱攻击作为一种红队方法，旨在绕过安全机制并揭示MLLMs的潜在风险。现有的越狱方法通常依赖复杂的优化或精心设计的图像和文本提示来绕过模型的安全机制，尽管取得了一定进展，但在商业闭源MLLMs上的攻击成功率较低。与以往研究不同，我们通过实验发现，MLLMs在理解能力和安全能力之间存在“混洗不一致性”：从理解能力看，MLLMs能很好地理解混洗后的有害文本-图像指令；但从安全能力看，它们容易被混洗后的有害指令绕过，导致有害响应。基于这一发现，我们创新性地提出了SI-Attack，一种文本-图像越狱攻击方法。该方法通过基于查询的黑盒优化，利用毒性判断模型的反馈选择最具危害性的混洗输入，从而克服混洗的随机性。实验表明，SI-Attack在三个基准测试中显著提升了攻击性能，尤其对GPT-4o和Claude-3.5-Sonnet等商业MLLMs的攻击成功率有显著提高。

> Multimodal Large Language Models (MLLMs) have achieved impressive performance and have been put into practical use in commercial applications, but they still have potential safety mechanism vulnerabilities. Jailbreak attacks are red teaming methods that aim to bypass safety mechanisms and discover MLLMs' potential risks. Existing MLLMs' jailbreak methods often bypass the model's safety mechanism through complex optimization methods or carefully designed image and text prompts. Despite achieving some progress, they have a low attack success rate on commercial closed-source MLLMs. Unlike previous research, we empirically find that there exists a Shuffle Inconsistency between MLLMs' comprehension ability and safety ability for the shuffled harmful instruction. That is, from the perspective of comprehension ability, MLLMs can understand the shuffled harmful text-image instructions well. However, they can be easily bypassed by the shuffled harmful instructions from the perspective of safety ability, leading to harmful responses. Then we innovatively propose a text-image jailbreak attack named SI-Attack. Specifically, to fully utilize the Shuffle Inconsistency and overcome the shuffle randomness, we apply a query-based black-box optimization method to select the most harmful shuffled inputs based on the feedback of the toxic judge model. A series of experiments show that SI-Attack can improve the attack's performance on three benchmarks. In particular, SI-Attack can obviously improve the attack success rate for commercial MLLMs such as GPT-4o or Claude-3.5-Sonnet.

[Arxiv](https://arxiv.org/abs/2501.04931)