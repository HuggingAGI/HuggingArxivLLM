# 利用微调API进行优化提示注入攻击闭源权重模型

发布时间：2025年01月16日

`LLM应用

理由：这篇论文主要讨论了针对闭源大型语言模型（LLMs）的新威胁，特别是通过优化计算提示注入的攻击方法。论文涉及了LLM的实际应用场景（如微调接口的使用）以及如何利用这些接口进行攻击。因此，它属于LLM应用类别，因为它关注的是LLM在实际使用中的安全性和攻击方法，而不是LLM的理论基础或架构设计。` `人工智能` `网络安全`

> Computing Optimization-Based Prompt Injections Against Closed-Weights Models By Misusing a Fine-Tuning API

# 摘要

> 我们揭示了一种针对闭源大型语言模型（LLMs）的新威胁，攻击者可通过优化计算提示注入。具体而言，攻击者利用远程微调接口返回的类似损失信息，指导对抗性提示的搜索。该接口由LLM供应商提供，允许开发者微调LLMs以适配任务，虽具实用性，却也暴露了足够信息，使攻击者得以计算对抗性提示。通过实验分析，我们展示了Gemini微调API返回的类似损失值，并证明这些值为贪婪搜索算法优化对抗性提示提供了有效信号。基于PurpleLlama提示注入基准，我们在Google的Gemini系列LLMs上实现了65%至82%的攻击成功率。这些攻击利用了经典的效用-安全权衡——微调接口虽为开发者提供了便利，却也使LLMs面临强大攻击。

> We surface a new threat to closed-weight Large Language Models (LLMs) that enables an attacker to compute optimization-based prompt injections. Specifically, we characterize how an attacker can leverage the loss-like information returned from the remote fine-tuning interface to guide the search for adversarial prompts. The fine-tuning interface is hosted by an LLM vendor and allows developers to fine-tune LLMs for their tasks, thus providing utility, but also exposes enough information for an attacker to compute adversarial prompts. Through an experimental analysis, we characterize the loss-like values returned by the Gemini fine-tuning API and demonstrate that they provide a useful signal for discrete optimization of adversarial prompts using a greedy search algorithm. Using the PurpleLlama prompt injection benchmark, we demonstrate attack success rates between 65% and 82% on Google's Gemini family of LLMs. These attacks exploit the classic utility-security tradeoff - the fine-tuning interface provides a useful feature for developers but also exposes the LLMs to powerful attacks.

[Arxiv](https://arxiv.org/abs/2501.09798)