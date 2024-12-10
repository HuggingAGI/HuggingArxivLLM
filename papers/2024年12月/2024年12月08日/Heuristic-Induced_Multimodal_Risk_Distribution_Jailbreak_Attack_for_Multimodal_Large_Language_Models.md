# 针对多模态大型语言模型的启发式诱导多模态风险分布越狱攻击

发布时间：2024年12月08日

`LLM应用` `多模态` `语言模型安全`

> Heuristic-Induced Multimodal Risk Distribution Jailbreak Attack for Multimodal Large Language Models

# 摘要

> 随着多模态大型语言模型（MLLMs）的迅猛发展，其安全性问题愈发受到学术界和业界的关注。尽管 MLLMs 易遭受越狱攻击，然而设计有效的多模态越狱攻击面临独特挑战，尤其是考虑到商业模型中不同模态所采取的各异保护措施。以往的工作将风险集中于单一模态，致使越狱表现有限。在本文中，我们提出一种名为 HIMRD 的启发式诱导多模态风险分布越狱攻击方法，它包含两个要素：多模态风险分布策略和启发式诱导搜索策略。多模态风险分布策略用于把有害指令在多个模态间进行分割，以有效避开 MLLMs 的安全防护。启发式诱导搜索策略确定了两类提示：有助于 MLLM 重构恶意提示的增强理解提示，以及提高肯定输出概率、减少拒绝的诱导提示，从而成功实现越狱攻击。大量实验表明，该方法有效揭示了 MLLMs 中的漏洞，在七个热门开源 MLLMs 中的平均攻击成功率达 90%，在三个热门闭源 MLLMs 中的平均攻击成功率约为 68%。我们的代码即将上线。警告：本文包含冒犯性和有害示例，敬请读者谨慎阅读。

> With the rapid advancement of multimodal large language models (MLLMs), concerns regarding their security have increasingly captured the attention of both academia and industry. Although MLLMs are vulnerable to jailbreak attacks, designing effective multimodal jailbreak attacks poses unique challenges, especially given the distinct protective measures implemented across various modalities in commercial models. Previous works concentrate risks into a single modality, resulting in limited jailbreak performance. In this paper, we propose a heuristic-induced multimodal risk distribution jailbreak attack method, called HIMRD, which consists of two elements: multimodal risk distribution strategy and heuristic-induced search strategy. The multimodal risk distribution strategy is used to segment harmful instructions across multiple modalities to effectively circumvent MLLMs' security protection. The heuristic-induced search strategy identifies two types of prompts: the understanding-enhancing prompt, which helps the MLLM reconstruct the malicious prompt, and the inducing prompt, which increases the likelihood of affirmative outputs over refusals, enabling a successful jailbreak attack. Extensive experiments demonstrate that this approach effectively uncovers vulnerabilities in MLLMs, achieving an average attack success rate of 90% across seven popular open-source MLLMs and an average attack success rate of around 68% in three popular closed-source MLLMs. Our code will coming soon. Warning: This paper contains offensive and harmful examples, reader discretion is advised.

[Arxiv](https://arxiv.org/abs/2412.05934)